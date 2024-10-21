# AUV-DSOR

# commands to run sims

```sh
roscd
roslaunch simulation_bringup start_scenario.launch
```

```sh
roslaunch simulation_bringup start_vehicle.launch name:=bluerov_heavy
```
# To get vehicle info

/bluerov_heavy0/State
```
Depth, X, Y,Z, Vx, Vy,Vz, u, Roll, Pitch,Yaw, Yaw_rate, Pitch_rate,Roll_rate, battery_level, altitude, status
```

# Farol msgs
# farol_msgs/mstate
```
float64: Depth, X, Y,Z, Vx, Vy,Vz, u, Yaw, Pitch, Roll, Yaw_rate, Pitch_rate, Roll_rate, In_Press, In_Press_dot uint8, battery_level, float64 altitude, uint8 status
```
# farol_msgs/Section
```
std_msgs/Header: Header
float64: xrefpoint, yrefpoint, xs, ys, xc, yc, xe, ye, Vl, direction, R0, Gamma_s, Gamma_e
```

# farol_msgs/MultiSection
```
std_msgs/Header: header, 
geometry_msgs/Point: RefPoint, StartPoint, CenterPoint, EndPoint, 
int8: type, adirection, 
float32: velocity, Gamma_s, Gamma_e
```

# farol_msgs/TrackingSection
```
std_msgs/Header: header
float64: x0, y0, yaw0, u, r, duration
```

# farol_msgs/MultiTrackingSection
```
farol_msgs/TrackingSection sections  
```

# farol_msgs/mUSBLFix
```
int32: RANGE_ONLY=0, AZIMUTH_ONLY=1, FULL_FIX=2, CARTESIAN=3
std_msgs/Header: header
int32: source_id, type
string: source_name, source_frame_id
geometry_msgs/Point: relative_position
float32: range, bearing, elevation, sound_speed, bearing_raw, elevation_raw
float64: position_covariance
```




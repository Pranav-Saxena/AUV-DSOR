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

# Farol msgs documentation
# farol_msgs/mstate
```
float64: Depth, X, Y,Z, Vx, Vy,Vz, u, Yaw, Pitch, Roll, Yaw_rate, Pitch_rate, Roll_rate, In_Press, In_Press_dot, uint8, battery_level, float64 altitude, uint8 status 
```


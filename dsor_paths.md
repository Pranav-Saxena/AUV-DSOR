# Node: dsor_paths
```
bool reset_path
bool success
```
# Services: dsor_paths/{Service}
# SetConstSpeed
```
float64 speed
float64 default_speed
---
bool success
```

# SetMode
```
bool closest_point_mode
---
bool success
```

# SpawnArc2D
```
float64[2] start_point
float64[2] end_point
float64[2] center_point
int8 direction
float64 z
---
bool success
```
# SpawnBernoulli
```
float64 radius
float64 center_x
float64 center_y
float64 z
---
bool success
```

# SpawnCircle2D
```
float64 radius
float64 center_x
float64 center_y
float64 z
---
bool success
```
# SpawnLine
```
float64[3] start_point
float64[3] end_point
float64[3] ref_point
---
bool success
```

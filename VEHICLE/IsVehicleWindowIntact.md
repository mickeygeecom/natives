---
ns: VEHICLE
---
## IS_VEHICLE_WINDOW_INTACT

```c
// 0x46E571A0E20D01F1 0xAC4EF23D
BOOL IS_VEHICLE_WINDOW_INTACT(Vehicle vehicle, int windowIndex);
```


## Parameters
* **vehicle**: 
* **windowIndex**: 

## Return value
This returns `1` if the window is **not** intact -- and returns `false` if it is intact.
Which is kinda confusing.

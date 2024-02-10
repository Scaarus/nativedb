---
ns: VEHICLE
aliases: ["0x2fa9923062dd396c"]
---
## ADD_VEHICLE_STUCK_CHECK_WITH_WARP

```c
// 0x2FA9923062DD396C
void ADD_VEHICLE_STUCK_CHECK_WITH_WARP(Vehicle vehicle, float MinimumMoveDistance, int CheckFrequency, bool WarpIfStuckFlag, bool WarpIfUpsideDownFlag, bool WarpIfInWaterFlag, int WarpMethod);
```

```
Will attempt to warp a vehicle out of a stuck or upsidedown or in water position.

This command is similar to the basic ADD_STUCK_CAR_CHECK except that the game will attempt to warp the car as soon as it becomes stuck. The three flags are used to control whether the car is warped if it has become stuck, as soon as it is upside-down or as soon as it is in water.
```

## Parameters
* **vehicle**: 
* **MinimumMoveDistance**: 
* **CheckFrequency**: 
* **WarpIfStuckFlag**: 
* **WarpIfUpsideDownFlag**: 
* **WarpIfInWaterFlag**: 
* **WarpMethod**: if WarpMethod is negative then the car will attempt to warp back on to its last route node. If WarpMethod is greater than 0 then the car will try to warp to that number of closest car nodes, starting with the closest. In both cases (last route node or closest car nodes), the car will only warp if both it and the destination coordinates are offscreen.

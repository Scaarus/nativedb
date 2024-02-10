---
ns: VEHICLE
aliases: ["0xe023e8ac4ef7c117"]
---
## SET_VEHICLE_USE_CUTSCENE_WHEEL_COMPRESSION

```c
// 0xE023E8AC4EF7C117
bool SET_VEHICLE_USE_CUTSCENE_WHEEL_COMPRESSION(Vehicle vehicle, bool UseCutsceneWheelCompression, bool AnimateWheels, bool AnimateJoints);
```

Sets the vehicle to ignore calls to set the wheel compression (ie. from SET_VEHICLE_ON_GROUND_PROPERLY) to allow blending back into the game from a cutscene task without the wheels popping. Use this command only if you're sure the cutscene places the vehiclewheels in a state that is okay to enter the game with


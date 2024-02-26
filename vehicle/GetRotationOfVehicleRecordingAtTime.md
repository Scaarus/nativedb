---
ns: VEHICLE
aliases: ["0x2058206fbe79a8ad"]
---
## GET_ROTATION_OF_VEHICLE_RECORDING_AT_TIME

```c
// 0x2058206FBE79A8AD
Vector3 GET_ROTATION_OF_VEHICLE_RECORDING_AT_TIME(float fTime, string pRecordingName);
```

Returns the rotation of the vehicle at a given time during the recording

There is two versions of this function. One that takes a RECORDING_ID and one that takes the number and name. It is preferable to use the RECORDING_ID

Allows access to the rotation of the vehicle in a recording at a given point in time


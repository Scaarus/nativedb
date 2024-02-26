---
ns: VEHICLE
aliases: ["0xd242728aa6f0fba2"]
---
## GET_POSITION_OF_VEHICLE_RECORDING_AT_TIME

```c
// 0xD242728AA6F0FBA2
Vector3 GET_POSITION_OF_VEHICLE_RECORDING_AT_TIME(float fTime, string pRecordingName);
```

Returns the translation of the vehicle at a given time during the recording

There is two versions of this function. One that takes a RECORDING_ID and one that takes the number and name. It is preferable to use the RECORDING_ID

Allows access to the translation of the vehicle in a recording at a given point in time


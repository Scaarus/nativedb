---
ns: VEHICLE
aliases: ["0x30d779de7c4f6dd3"]
---
## SET_VEHICLE_FLIGHT_NOZZLE_POSITION

```c
// 0x30D779DE7C4F6DD3
void SET_VEHICLE_FLIGHT_NOZZLE_POSITION(Entity entity, float NozzleRatio);
```

Use this command to adjust the vertical flight nozzles position on the vulkan, this controls whether the vehicle is in vertical flight mode or not.

pass in a value between 0.0f and 1.0f;


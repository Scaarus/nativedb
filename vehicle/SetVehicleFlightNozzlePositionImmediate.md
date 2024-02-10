---
ns: VEHICLE
aliases: ["0x9aa47fff660cb932"]
---
## SET_VEHICLE_FLIGHT_NOZZLE_POSITION_IMMEDIATE

```c
// 0x9AA47FFF660CB932
void SET_VEHICLE_FLIGHT_NOZZLE_POSITION_IMMEDIATE(Entity entity, float NozzleRatio);
```

Use this command to adjust the vertical flight nozzles position immediately on the vulkan, this controls whether the vehicle is in vertical flight mode or not.

pass in a value between 0.0f and 1.0f;


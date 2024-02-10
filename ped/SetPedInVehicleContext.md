---
ns: PED
aliases: ["0x530071295899a8c6"]
---
## SET_PED_IN_VEHICLE_CONTEXT

```c
// 0x530071295899A8C6
void SET_PED_IN_VEHICLE_CONTEXT(Ped ped, int InVehicleContextHash);
```

```
Make the ped use different clipset when inside a vehicle. The appropriate clipset for the seat the ped is in will be chosen from the context name The contexts are defined in vehiclelayouts.meta in the <InVehicleOverrideInfos><InVehicleOverrideInfos> section e.g. MISS_ARMENIAN3_FRANKLIN_TENSE DON'T FORGET to stream in the new clipset before calling this!!
```

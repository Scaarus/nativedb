---
ns: EXTRAMETADATA
aliases: ["0x5549ee11fa22fcf2"]
---
## GET_DLC_VEHICLE_FLAGS

```c
// 0x5549EE11FA22FCF2
int GET_DLC_VEHICLE_FLAGS(int dlcIndex, Any* a);
```

Looks up vehicle flags based on the supplied dlc index (dlcIndex must be inside range: (0 <= dlcIndex < [GET_NUM_DLC_VEHICLES](#_0xA7A866D21CD2329B)()) ) Use the enum below as and index to the bits set from the metadata, if more are required we will need to update the enum Enum: <enumdef type="eVehicleFlags"> <enumval name="VF_DISABLE_GARAGE"> <enumdef>


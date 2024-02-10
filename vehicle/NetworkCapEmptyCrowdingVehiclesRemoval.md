---
ns: VEHICLE
aliases: ["0xa4a9a4c40e615885"]
---
## NETWORK_CAP_EMPTY_CROWDING_VEHICLES_REMOVAL

```c
// 0xA4A9A4C40E615885
void NETWORK_CAP_EMPTY_CROWDING_VEHICLES_REMOVAL(int capNum);
```

```
Sets the total number of vehicles at which the aggressive removal will kick in
```

## Parameters
* **capNum**: the number of vehicles, beyond which will trigger agressive removal (if it is enabled for this frame)

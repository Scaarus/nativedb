---
ns: VEHICLE
aliases: ["0xf8c397922fc03f41"]
---
## GET_CONVERTIBLE_ROOF_STATE

```c
// 0xF8C397922FC03F41
convertible_roof_state GET_CONVERTIBLE_ROOF_STATE(Vehicle vehicle);
```

returns the CONVERTIBLE_ROOF_STATE of the vehicle if it has a convertible roof, defaults to CRS_RAISED

## Return Type Values:
| Value | Name |
| --- | --- |
| 197 | Raised |
| 198 | Lowering |
| 199 | Lowered |
| 200 | Raising |
| 201 | Closing Boot |
| 202 | Roof Stuck Raised |
| 203 | Roof Stuck Lowered |


Get the current state of a convertible roof


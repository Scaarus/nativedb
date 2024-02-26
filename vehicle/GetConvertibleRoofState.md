---
ns: VEHICLE
aliases: ["0xf8c397922fc03f41"]
---
## GET_CONVERTIBLE_ROOF_STATE

```c
// 0xF8C397922FC03F41
int GET_CONVERTIBLE_ROOF_STATE(Vehicle vehicle);
```

returns the CONVERTIBLE_ROOF_STATE of the vehicle if it has a convertible roof, defaults to CRS_RAISED

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Raised |
| 1 | Lowering |
| 2 | Lowered |
| 3 | Raising |
| 4 | Closing Boot |
| 5 | Roof Stuck Raised |
| 6 | Roof Stuck Lowered |

Get the current state of a convertible roof


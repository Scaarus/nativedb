---
ns: VEHICLE
aliases: ["0x9088eb5a43ffb0a1"]
---
## SET_VEHICLE_NUMBER_PLATE_TEXT_INDEX

```c
// 0x9088EB5A43FFB0A1
void SET_VEHICLE_NUMBER_PLATE_TEXT_INDEX(Vehicle vehicle, int index);
```

```
Sets the number plate to one of a set specified by the vehicle artists.

index should be greater than or equal to 0 and less than the value returned by GET_NUMBER_OF_VEHICLE_NUMBER_PLATES.
```

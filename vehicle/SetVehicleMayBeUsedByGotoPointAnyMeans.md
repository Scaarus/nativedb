---
ns: VEHICLE
aliases: ["0xe851e480b814d4ba"]
---
## SET_VEHICLE_MAY_BE_USED_BY_GOTO_POINT_ANY_MEANS

```c
// 0xE851E480B814D4BA
void SET_VEHICLE_MAY_BE_USED_BY_GOTO_POINT_ANY_MEANS(Vehicle vehicle, bool State);
```

Normally peds tasked with GOTO_POINT_ANY_MEANS will only be able to commandeer vehicles from the ambient population. Settting TRUE via this command will allow peds to use specified mission vehicles also.


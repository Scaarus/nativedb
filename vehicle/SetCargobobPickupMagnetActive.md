---
ns: VEHICLE
aliases: ["0x9a665550f8da349b"]
---
## SET_CARGOBOB_PICKUP_MAGNET_ACTIVE

```c
// 0x9A665550F8DA349B
void SET_CARGOBOB_PICKUP_MAGNET_ACTIVE(Vehicle vehicle, bool active);
```

```
Change the magnet active state. When active, the magnet will pull in its target entity. When inactive, the magnet will have a reduced effect on nearby entities and will point at its current target.
```

---
ns: PED
aliases: ["0x4f5f651accc9c4cf"]
---
## SET_PED_BOUNDS_ORIENTATION

```c
// 0x4F5F651ACCC9C4CF
void SET_PED_BOUNDS_ORIENTATION(float pitch, float heading, Vector3 vecOffset);
```

Lets the ped's mover capsule bounds be re-oriented.

Must be called each frame otherwise ped's mover capsule bound will blend back to the default orientation.


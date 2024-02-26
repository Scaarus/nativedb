---
ns: PED
aliases: ["0x5983bb449d7fdb12"]
---
## IS_PED_HURT

```c
// 0x5983BB449D7FDB12
bool IS_PED_HURT(Ped ped);
```

Checks the ped status is hurt.

This is the official [IS_PED_INJURED](#_0x84A2DD9AC37C35C1). Since V considers injured the same as dying a ped will never be "injured" The hurt threshold was added and is used to describe peds that are injured enough to limp away or flee.


---
ns: PED
aliases: ["0x6cd5a433374d4cfb"]
---
## CAN_PED_SEE_HATED_PED

```c
// 0x6CD5A433374D4CFB
bool CAN_PED_SEE_HATED_PED(Ped ped, Ped ped);
```

Returns true out if the ped can see the other ped (Clear LOS, withing viewing range) Will only work if the ped has a hated relationship with the other ped. Uses asynchronous LOS checks and detection so should be relatively cheap.


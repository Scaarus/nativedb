---
ns: PED
aliases: ["0xfcf37a457cb96dc0"]
---
## IS_PED_HEADING_TOWARDS_POSITION

```c
// 0xFCF37A457CB96DC0
bool IS_PED_HEADING_TOWARDS_POSITION(Vector3 vPoint, float fDegreesDelta);
```

Returns true if the ped is heading towards the given point, within +/- of the heading tolerance. checks that the ped's current-heading AND desired-heading are both aligned with the heading to the vPoint This will not take any Z differences into account!


---
ns: PED
aliases: ["0x06087579e7aa85a9"]
---
## IS_TARGET_PED_IN_PERCEPTION_AREA

```c
// 0x06087579E7AA85A9
bool IS_TARGET_PED_IN_PERCEPTION_AREA(Ped ped, Ped ped, float fFocusAngle, float fFocusDistance, float fPeripheralAngle, float fPeripheralDistance);
```

```
To check if a target ped is within a given ped's perception area (defined by an angle and distance)

If an angle or distance param is overridden, that value will be used instead of the ped's default value. The angles should be given in degrees.
```

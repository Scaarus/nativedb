---
ns: PED
aliases: ["0xc396f5b86ff9febd"]
---
## SET_PED_LEG_IK_MODE

```c
// 0xC396F5B86FF9FEBD
void SET_PED_LEG_IK_MODE(Ped ped, int nLegIkMode);
```

Sets the allowed IK mode for a ped.

## nLegIkMode Values:
| Value | Name |
| --- | --- |
| 0 | Off |
| 173 | Partial Default For Non-Player Peds. Ground Position At Feet Is Inferred From Standing Capsule |
| 174 | Full Physics Probes Are Done At Feet To Find Exact Ground Position |
| 175 | Full Melee Physics Probes Are Done At Feet To Find Exact Ground Position With Support For Melee |


The default mode for non-player peds is LEG_IK_PARTIAL.


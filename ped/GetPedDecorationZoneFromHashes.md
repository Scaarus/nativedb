---
ns: PED
aliases: ["0x9fd452bfbe7a7a8b"]
---
## GET_PED_DECORATION_ZONE_FROM_HASHES

```c
// 0x9FD452BFBE7A7A8B
ped_decoration_zone GET_PED_DECORATION_ZONE_FROM_HASHES(int CollectionNameHash, int PresetNameHash);
```

Same as GET_PED_DECORATION_ZONE but with hashes

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Torso |
| 160 | Head |
| 161 | Left Arm |
| 162 | Right Arm |
| 163 | Left Leg |
| 164 | Right Leg |
| 165 | Medals |
| 166 | Invalid |


## Parameters
* **CollectionNameHash**: hash of the name of the collection where the preset lives
* **PresetNameHash**: hash of the name of the preset

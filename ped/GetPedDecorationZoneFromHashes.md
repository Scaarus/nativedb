---
ns: PED
aliases: ["0x9fd452bfbe7a7a8b"]
---
## GET_PED_DECORATION_ZONE_FROM_HASHES

```c
// 0x9FD452BFBE7A7A8B
int GET_PED_DECORATION_ZONE_FROM_HASHES(int CollectionNameHash, int PresetNameHash);
```

Same as GET_PED_DECORATION_ZONE but with hashes

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Torso |
| 1 | Head |
| 2 | Left Arm |
| 3 | Right Arm |
| 4 | Left Leg |
| 5 | Right Leg |
| 6 | Medals |
| 7 | Invalid |


## Parameters
* **CollectionNameHash**: hash of the name of the collection where the preset lives
* **PresetNameHash**: hash of the name of the preset

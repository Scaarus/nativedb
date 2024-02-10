---
ns: PED
aliases: ["0x2b16a3bff1fbce49"]
---
## SET_PED_PRELOAD_PROP_DATA

```c
// 0x2B16A3BFF1FBCE49
int SET_PED_PRELOAD_PROP_DATA(Ped ped, int Anchor, int PropId, int TexId);
```

Sets a ped prop to preload into memory, without applying it on the ped

## Anchor Values:
| Value | Name |
| --- | --- |
| 0 | Head |
| 131 | Eyes |
| 132 | Ears |
| 133 | Mouth |
| 134 | Left Hand |
| 135 | Right Hand |
| 136 | Left Wrist |
| 137 | Right Wrist |
| 138 | Hip |


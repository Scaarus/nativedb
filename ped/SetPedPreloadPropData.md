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

## Values for `Anchor`:
| Value | Name |
| --- | --- |
| 0 | Head |
| 1 | Eyes |
| 2 | Ears |
| 3 | Mouth |
| 4 | Left Hand |
| 5 | Right Hand |
| 6 | Left Wrist |
| 7 | Right Wrist |
| 8 | Hip |


## Parameters
* **ped**: 
* **Anchor**: 
* **PropId**: 
* **TexId**: (Default value: `0`)

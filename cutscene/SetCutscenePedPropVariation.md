---
ns: CUTSCENE
aliases: ["0x0546524ade2e9723"]
---
## SET_CUTSCENE_PED_PROP_VARIATION

```c
// 0x0546524ADE2E9723
void SET_CUTSCENE_PED_PROP_VARIATION(string SceneHandle, int Position, int NewPropIndex, int NewTextIndex, Hash modelHash);
```

```
Sets a request to change the component prop, only valid for a single frame.

Possible values for Position:
| Index | Name |
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


Always apply this to the CS version, all cs variations will be copied to the ig version, if one is present. Use CAN_REQUEST_ASSETS_FOR_CUTSCENE_ENTITY to be sure that the variation request has been made as this command only returns true FOR A SINGLE FRAME.
```

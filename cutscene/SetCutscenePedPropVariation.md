---
ns: CUTSCENE
aliases: ["0x0546524ade2e9723"]
---
## SET_CUTSCENE_PED_PROP_VARIATION

```c
// 0x0546524ADE2E9723
void SET_CUTSCENE_PED_PROP_VARIATION(string SceneHandle, int Position, int NewPropIndex, int NewTextIndex, Hash modelHash);
```

Sets a request to change the component prop, only valid for a single frame.

## Position Values:
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


Always apply this to the CS version, all cs variations will be copied to the ig version, if one is present. Use [CAN_REQUEST_ASSETS_FOR_CUTSCENE_ENTITY](#_0xB56BBBCC2955D9CB) to be sure that the variation request has been made as this command only returns true FOR A SINGLE FRAME.


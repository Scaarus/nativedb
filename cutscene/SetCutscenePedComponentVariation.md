---
ns: CUTSCENE
aliases: ["0xba01e7b6deefbbc9"]
---
## SET_CUTSCENE_PED_COMPONENT_VARIATION

```c
// 0xBA01E7B6DEEFBBC9
void SET_CUTSCENE_PED_COMPONENT_VARIATION(string SceneHandle, int Component, int Drawable, int TextureID, Hash modelHash);
```

```
Sets a request to change the component variation, only valid for a single frame.

Possible values for Component:
| Index | Name |
| --- | --- |
| 0 | Head |
| 139 | Berd |
| 140 | Hair |
| 141 | Torso |
| 142 | Leg |
| 143 | Hand |
| 144 | Feet |
| 145 | Teeth |
| 146 | Special Pv Comp Accs |
| 147 | Special2 Pv Comp Task |
| 148 | Decl ? |
| 149 | Jbib |


Always apply this to the CS version, all cs variations will be copied to the ig version, if one is present. Use CAN_REQUEST_ASSETS_FOR_CUTSCENE_ENTITY to be sure that the variation request has been made as this command only returns true FOR A SINGLE FRAME.
```

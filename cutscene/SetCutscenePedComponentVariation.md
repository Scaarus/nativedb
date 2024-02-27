---
ns: CUTSCENE
aliases: ["0xba01e7b6deefbbc9"]
---
## SET_CUTSCENE_PED_COMPONENT_VARIATION

```c
// 0xBA01E7B6DEEFBBC9
void SET_CUTSCENE_PED_COMPONENT_VARIATION(string SceneHandle, int Component, int Drawable, int TextureID, Hash modelHash);
```

Sets a request to change the component variation, only valid for a single frame.

## Values for `Component`:
| Value | Name |
| --- | --- |
| 0 | Head |
| 1 | Berd |
| 2 | Hair |
| 3 | Torso |
| 4 | Leg |
| 5 | Hand |
| 6 | Feet |
| 7 | Teeth |
| 8 | Special (Pv Comp Accs) |
| 9 | Special2 (Pv Comp Task) |
| 10 | Decl (?) |
| 11 | Jbib |


Always apply this to the CS version, all cs variations will be copied to the ig version, if one is present. Use [`CAN_REQUEST_ASSETS_FOR_CUTSCENE_ENTITY`](#_0xB56BBBCC2955D9CB) to be sure that the variation request has been made as this command only returns true FOR A SINGLE FRAME.


## Parameters
* **SceneHandle**: 
* **Component**: 
* **Drawable**: 
* **TextureID**: 
* **modelHash**: (Default value: `Dummy_Model_For_Script`)

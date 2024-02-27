---
ns: PED
aliases: ["0x262b14f48d29de80"]
---
## SET_PED_COMPONENT_VARIATION

```c
// 0x262B14F48D29DE80
void SET_PED_COMPONENT_VARIATION(Ped ped, int ComponentNumber, int NewDrawableNumber, int NewTextureNumber, int NewPaletteNumber);
```

Sets the drawable, texture and palette for the specified ped component.

## ComponentNumber Values:
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


This command sets the drawable and texture for one component of the ped's model. Each ped model can have several drawables for each component. Each drawable can have several textures. You should check that the new drawable index is within range for the component (body part) for the ped's model (using GET_NUMBER_OF_CHAR_DRAWABLE_VARIATIONS. The new texture index should be within range for the new drawable (can be checked using GET_NUMBER_OF_CHAR_TEXTURE_VARIATIONS). ComponentNumber is taken from PED_COMPONENT in "commands_ped.sch"


## Parameters
* **ped**: 
* **ComponentNumber**: 
* **NewDrawableNumber**: 
* **NewTextureNumber**: 
* **NewPaletteNumber**: (Default value: `0`)

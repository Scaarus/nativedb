---
ns: PED
aliases: ["0x9414e18b9434c2fe"]
---
## SET_PED_HEAD_BLEND_DATA

```c
// 0x9414E18B9434C2FE
void SET_PED_HEAD_BLEND_DATA(Ped ped, int head0, int head1, int head2, int tex0, int tex1, int tex2, float headBlend, float texBlend, float varBlend, bool parent);
```

Sets all drawables and textures needed to create a blended multiplayer ped head.

The data set with this function auguments the ped variation, it does _not_ replace it and a variation will be required on the ped too.


## Parameters
* **ped**: 
* **head0**: index of head of first parent (same as you would set with a component variation)
* **head1**: index of head of second parent
* **head2**: index of head used for minor genetic variation
* **tex0**: index of texture used for first parent (same as you would set with a component variation)
* **tex1**: index of texture used for second parent
* **tex2**: index of texture used for genetic variation
* **headBlend**: the amount of blend between the two parent heads. 0.0 will be fully head0, 1.0 fully head1 and 0.5 will bea 5050 mix between them
* **texBlend**: same as headBlend only for the textures
* **varBlend**: the amount of genetic variation applied. 0.0 is no variation and 1.0 will completely replace the parents with the third head. very small values should be used for this.
* **parent**: 

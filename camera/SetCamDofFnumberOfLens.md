---
ns: CAMERA
aliases: ["0x7dd234d6f3914c5b"]
---
## SET_CAM_DOF_FNUMBER_OF_LENS

```c
// 0x7DD234D6F3914C5B
void SET_CAM_DOF_FNUMBER_OF_LENS(Camera camera, float fNumber);
```

Specifies the aperture (as an f-number) to be used by the physical lens model in the adaptive depth of field effect. Reducing this value will result in shallower depth of field and stonger blur.

The valid range of 'fNumber' is (f)0.5 to (f)256.0.


---
ns: GRAPHICS
aliases: ["0x1072f115dab0717e"]
---
## DRAW_LOW_QUALITY_PHOTO_TO_PHONE

```c
// 0x1072F115DAB0717E
void DRAW_LOW_QUALITY_PHOTO_TO_PHONE(bool Draw, int PhotoRotation);
```

Call this to draw the low quality copy of the photo to the phone. You can only call this after [GET_STATUS_OF_CREATE_LOW_QUALITY_COPY_OF_PHOTO](#_0xCB82A0BF0E3E3265) has returned PHOTO_OPERATION_SUCCEEDED. You can't call this after calling [FREE_MEMORY_FOR_LOW_QUALITY_PHOTO](#_0x6A12D88881435DCA) Call with FALSE to stop drawing the photo

## PhotoRotation Values:
| Value | Name |
| --- | --- |
| 0 | No Rotation |
| 1 | Clockwise |
| 2 | Anti Clockwise |


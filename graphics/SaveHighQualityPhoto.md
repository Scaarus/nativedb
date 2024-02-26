---
ns: GRAPHICS
aliases: ["0x3dec726c25a11bac"]
---
## SAVE_HIGH_QUALITY_PHOTO

```c
// 0x3DEC726C25A11BAC
bool SAVE_HIGH_QUALITY_PHOTO(int PhotoSlotIndex);
```

Triggers the saving of a photo into the specified slot in the photo gallery. This can only be called after [GET_STATUS_OF_TAKE_HIGH_QUALITY_PHOTO](#_0x0D6CA79EEEBD8CA3) has returned PHOTO_OPERATION_SUCCEEDED and before calling [FREE_MEMORY_FOR_HIGH_QUALITY_PHOTO](#_0xD801CC02177FA3F1)


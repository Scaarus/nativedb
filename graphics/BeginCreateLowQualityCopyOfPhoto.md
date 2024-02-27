---
ns: GRAPHICS
aliases: ["0x759650634f07b6b4"]
---
## BEGIN_CREATE_LOW_QUALITY_COPY_OF_PHOTO

```c
// 0x759650634F07B6B4
bool BEGIN_CREATE_LOW_QUALITY_COPY_OF_PHOTO(int qualitySetting);
```

Creates a low quality version of the current high quality photo. The low quality version can be displayed on the phone. This can only be called after [`GET_STATUS_OF_TAKE_HIGH_QUALITY_PHOTO`](#_0x0D6CA79EEEBD8CA3) has returned PHOTO_OPERATION_SUCCEEDED and before calling [`FREE_MEMORY_FOR_HIGH_QUALITY_PHOTO`](#_0xD801CC02177FA3F1)

## Values for `qualitySetting`:
| Value | Name |
| --- | --- |
| 0 | One |
| 1 | Half |
| 2 | Quarter |
| 3 | Eighth |


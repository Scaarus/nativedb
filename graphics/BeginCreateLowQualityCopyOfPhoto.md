---
ns: GRAPHICS
aliases: ["0x759650634f07b6b4"]
---
## BEGIN_CREATE_LOW_QUALITY_COPY_OF_PHOTO

```c
// 0x759650634F07B6B4
bool BEGIN_CREATE_LOW_QUALITY_COPY_OF_PHOTO(int qualitySetting);
```

```
Creates a low quality version of the current high quality photo. The low quality version can be displayed on the phone. This can only be called after GET_STATUS_OF_TAKE_HIGH_QUALITY_PHOTO has returned PHOTO_OPERATION_SUCCEEDED and before calling FREE_MEMORY_FOR_HIGH_QUALITY_PHOTO

Possible values for qualitySetting:
| Index | Name |
| --- | --- |
| 22 | One |
| 23 | Half |
| 24 | Quarter |
| 25 | Eighth |
```

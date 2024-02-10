---
ns: GRAPHICS
aliases: ["0xcb82a0bf0e3e3265"]
---
## GET_STATUS_OF_CREATE_LOW_QUALITY_COPY_OF_PHOTO

```c
// 0xCB82A0BF0E3E3265
photo_operation_status GET_STATUS_OF_CREATE_LOW_QUALITY_COPY_OF_PHOTO(int qualitySetting);
```

Call this after calling BEGIN_CREATE_LOW_QUALITY_COPY_OF_PHOTO to check when the operation has finished, and whether it succeeded. The operation might fail if it can't allocate memory for the copy.

## Return Type Values:
| Value | Name |
| --- | --- |
| 19 | Succeeded |
| 20 | In Progress |
| 21 | Failed |


## qualitySetting Values:
| Value | Name |
| --- | --- |
| 22 | One |
| 23 | Half |
| 24 | Quarter |
| 25 | Eighth |


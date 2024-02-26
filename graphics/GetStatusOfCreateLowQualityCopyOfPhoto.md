---
ns: GRAPHICS
aliases: ["0xcb82a0bf0e3e3265"]
---
## GET_STATUS_OF_CREATE_LOW_QUALITY_COPY_OF_PHOTO

```c
// 0xCB82A0BF0E3E3265
int GET_STATUS_OF_CREATE_LOW_QUALITY_COPY_OF_PHOTO(int qualitySetting);
```

Call this after calling [BEGIN_CREATE_LOW_QUALITY_COPY_OF_PHOTO](#_0x759650634F07B6B4) to check when the operation has finished, and whether it succeeded. The operation might fail if it can't allocate memory for the copy.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Succeeded |
| 1 | In Progress |
| 2 | Failed |

## qualitySetting Values:
| Value | Name |
| --- | --- |
| 0 | One |
| 1 | Half |
| 2 | Quarter |
| 3 | Eighth |


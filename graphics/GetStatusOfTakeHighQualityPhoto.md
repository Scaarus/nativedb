---
ns: GRAPHICS
aliases: ["0x0d6ca79eeebd8ca3"]
---
## GET_STATUS_OF_TAKE_HIGH_QUALITY_PHOTO

```c
// 0x0D6CA79EEEBD8CA3
int GET_STATUS_OF_TAKE_HIGH_QUALITY_PHOTO();
```

Call this after calling [BEGIN_TAKE_HIGH_QUALITY_PHOTO](#_0xA67C35C56EB1BD9D) to check when the operation has finished, and whether it succeeded.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Succeeded |
| 1 | In Progress |
| 2 | Failed |


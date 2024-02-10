---
ns: GRAPHICS
aliases: ["0x40afb081f8add4ee"]
---
## GET_LOAD_HIGH_QUALITY_PHOTO_STATUS

```c
// 0x40AFB081F8ADD4EE
photo_operation_status GET_LOAD_HIGH_QUALITY_PHOTO_STATUS(int PhotoSlotIndex);
```

Returns the status of the last photo load to have been successfully started

## Return Type Values:
| Value | Name |
| --- | --- |
| 19 | Succeeded |
| 20 | In Progress |
| 21 | Failed |


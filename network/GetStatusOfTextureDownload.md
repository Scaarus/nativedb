---
ns: NETWORK
aliases: ["0x8bd6c6dea20e82c6"]
---
## GET_STATUS_OF_TEXTURE_DOWNLOAD

```c
// 0x8BD6C6DEA20E82C6
int GET_STATUS_OF_TEXTURE_DOWNLOAD();
```

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Succeeded |
| 1 | In Progress |
| 2 | Failed |

Queries the state of a texture download. The texture cannot be used until this command returns PHOTO_OPERATION_SUCCEEDED


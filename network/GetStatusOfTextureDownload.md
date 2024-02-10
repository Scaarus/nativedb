---
ns: NETWORK
aliases: ["0x8bd6c6dea20e82c6"]
---
## GET_STATUS_OF_TEXTURE_DOWNLOAD

```c
// 0x8BD6C6DEA20E82C6
photo_operation_status GET_STATUS_OF_TEXTURE_DOWNLOAD();
```

## Return Type Values:
| Value | Name |
| --- | --- |
| 19 | Succeeded |
| 20 | In Progress |
| 21 | Failed |


Queries the state of a texture download. The texture cannot be used until this command returns PHOTO_OPERATION_SUCCEEDED


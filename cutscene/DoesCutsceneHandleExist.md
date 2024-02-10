---
ns: CUTSCENE
aliases: ["0x4fcd976da686580c"]
---
## DOES_CUTSCENE_HANDLE_EXIST

```c
// 0x4FCD976DA686580C
cutscene_handle_search_result DOES_CUTSCENE_HANDLE_EXIST(string sSceneHandle);
```

```
Returns a value specifying if an entity exists in the cutscene with the provided scene handle. More info

Possible return values:
| Index | Name |
| --- | --- |
| 0 | No Cutscene Running |
| 1 | Cutfile Still Loading |
| 2 | Handle Exists |
| 3 | Handle Not Found |


Use this to determine if a cutscene entity with the given scene handle exists in the currently running cut scene
```

## Parameters
* **sSceneHandle**: The scene handle to search

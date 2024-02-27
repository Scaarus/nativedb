---
ns: PED
aliases: ["0xb2aff10216defa2f"]
---
## SPAWNPOINTS_START_SEARCH_IN_ANGLED_AREA

```c
// 0xB2AFF10216DEFA2F
void SPAWNPOINTS_START_SEARCH_IN_ANGLED_AREA(Vector3 vPoint1, Vector3 vPoint2, float fWidth, int iFlags, float fMinimumSpacing, int iMaxSearchDurationMS);
```

Same as [`SPAWNPOINTS_START_SEARCH`](#_0x2DF9038C90AD5264), except uses the angled area volume definition popular with level-design vPoint1 & vPoint2 define the start and end points of a rectangle, fWidth in size Height of the area is defined by raising one point above the other (a little height we be artificially applied in the case of a flat volume) If optional 'iMaxSearchDurationMS' param is non-zero, search will enter a 'failed' state if this milliseconds duration is exceeded - if the timeout value is specified, script must check for the failure case via [`SPAWNPOINTS_IS_SEARCH_FAILED`](#_0xF445DE8DA80A1792)()

## Values for `iFlags`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | May Spawn In Interior |
| 2 | May Spawn In Exterior |
| 4 | Allow Not Network Spawn Candidate Polys |
| 8 | Allow Isolated Polys |
| 16 | Allow Road Polys |
| 32 | Only Points Against Edges |


## Parameters
* **vPoint1**: 
* **vPoint2**: 
* **fWidth**: 
* **iFlags**: (Default value: `Default`)
* **fMinimumSpacing**: (Default value: `0`)
* **iMaxSearchDurationMS**: (Default value: `0`)

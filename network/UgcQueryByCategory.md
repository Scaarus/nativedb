---
ns: NETWORK
aliases: ["0x692d58df40657e8c"]
---
## UGC_QUERY_BY_CATEGORY

```c
// 0x692D58DF40657E8C
bool UGC_QUERY_BY_CATEGORY(int nCategory, int nOffset, int nMaxCount, string szContentType, int nSortType, bool Descending);
```

## nCategory Values:
| Value | Name |
| --- | --- |
| 103 | None |
| 104 | Rockstar Created |
| 105 | Rockstar Created Candidate |
| 106 | Rockstar Verified |
| 107 | Rockstar Verified Candidate |
| 108 | Rockstar Community |
| 109 | Rockstar Community Candidate |


## nSortType Values:
| Value | Name |
| --- | --- |
| -1 | Not Specified |
| 265 | Created Date |


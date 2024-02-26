---
ns: PED
aliases: ["0x9e6b70061662ae5c"]
---
## GET_RELATIONSHIP_BETWEEN_GROUPS

```c
// 0x9E6B70061662AE5C
int GET_RELATIONSHIP_BETWEEN_GROUPS(Hash relGroupA, Hash relGroupB);
```

Gets the relationship between two rel groups, will return None if no relationship has been setup.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Respect |
| 1 | Like (1) |
| 2 | Ignore (2) |
| 3 | Dislike (3) |
| 4 | Wanted (4) |
| 5 | Hate (5) |
| 6 | Dead (6) |
| 255 | None |


---
ns: PED
aliases: ["0x9e6b70061662ae5c"]
---
## GET_RELATIONSHIP_BETWEEN_GROUPS

```c
// 0x9E6B70061662AE5C
relationship_type GET_RELATIONSHIP_BETWEEN_GROUPS(Hash relGroupA, Hash relGroupB);
```

Gets the relationship between two rel groups, will return None if no relationship has been setup.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Respect |
| 119 | Like 1 |
| 120 | Ignore 2 |
| 121 | Dislike 3 |
| 122 | Wanted 4 |
| 123 | Hate 5 |
| 124 | Dead 6 |
| 255 | None |


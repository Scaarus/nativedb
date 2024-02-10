---
ns: PED
aliases: ["0xeba5ad3a0eaf7121"]
---
## GET_RELATIONSHIP_BETWEEN_PEDS

```c
// 0xEBA5AD3A0EAF7121
relationship_type GET_RELATIONSHIP_BETWEEN_PEDS(Ped ped, Ped ped);
```

Gets the relationship between two peds, if they have not had one set up it will return

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


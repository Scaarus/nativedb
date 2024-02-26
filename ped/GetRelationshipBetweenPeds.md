---
ns: PED
aliases: ["0xeba5ad3a0eaf7121"]
---
## GET_RELATIONSHIP_BETWEEN_PEDS

```c
// 0xEBA5AD3A0EAF7121
int GET_RELATIONSHIP_BETWEEN_PEDS(Ped ped, Ped ped);
```

Gets the relationship between two peds, if they have not had one set up it will return

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


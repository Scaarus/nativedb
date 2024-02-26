---
ns: PED
aliases: ["0xbf25eb89375a37ad"]
---
## SET_RELATIONSHIP_BETWEEN_GROUPS

```c
// 0xBF25EB89375A37AD
void SET_RELATIONSHIP_BETWEEN_GROUPS(int RelationshipType, Hash relGroup, Hash otherRelGroup);
```

Set the relationship between rel groups.

## RelationshipType Values:
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


RELATIONSHIP_TYPE is am enum list in commands_ped.sch, REL_GROUP_HASH is an enum list in generic.sch

To get 2 rel groups to hate each other, set the relationship for both grps


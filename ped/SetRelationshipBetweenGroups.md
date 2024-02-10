---
ns: PED
aliases: ["0xbf25eb89375a37ad"]
---
## SET_RELATIONSHIP_BETWEEN_GROUPS

```c
// 0xBF25EB89375A37AD
void SET_RELATIONSHIP_BETWEEN_GROUPS(int RelationshipType, Hash relGroup, Hash otherRelGroup);
```

```
Set the relationship between rel groups.

Possible values for RelationshipType:
| Index | Name |
| --- | --- |
| 0 | Respect |
| 119 | Like 1 |
| 120 | Ignore 2 |
| 121 | Dislike 3 |
| 122 | Wanted 4 |
| 123 | Hate 5 |
| 124 | Dead 6 |
| 255 | None |


RELATIONSHIP_TYPE is am enum list in commands_ped.sch, REL_GROUP_HASH is an enum list in generic.sch

To get 2 rel groups to hate each other, set the relationship for both grps
```

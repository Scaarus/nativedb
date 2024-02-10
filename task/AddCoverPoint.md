---
ns: TASK
aliases: ["0xd5c12a75c7b9497f"]
---
## ADD_COVER_POINT

```c
// 0xD5C12A75C7B9497F
Coverpoint ADD_COVER_POINT(float direction, int usage, int height, int arc, bool isPriorityToPlayer);
```

Adds a cover point in the given position to cover from direction ( in degrees ).

## usage Values:
| Value | Name |
| --- | --- |
| 238 | Left Fires Round To The Right |
| 239 | Right Fires Round To The Left |
| 240 | Both Must Fire Over The Top, Used For Low Or High Cover Points |
| 241 | Neither Fires Either Left Or Right |


## height Values:
| Value | Name |
| --- | --- |
| 0 | Low |
| 2 | Toohigh |
| 242 | High <Unused |


## arc Values:
| Value | Name |
| --- | --- |
| 0 | 180 |
| 243 | 120 |
| 244 | 90 |
| 245 | 0To60 |
| 246 | 300To0 |
| 247 | 0To45 |
| 248 | 315To0 |


NOTE: To take the coordinates of a cover point you'd like to create, do the following: Stand behind the object you'd like to take cover behind. Face towards the object you're standing behind. If you do it this way then the following is true: The heading that is output to your temp_debug.txt is the 'FLOAT direction' Another thing to bear in mind is: When setting COVERPOINT_USAGE, COVUSE_WALLTOLEFT will flip the ped out to his right hand side, and so COVUSE_WALLTORIGHT will flip the ped out to his left.


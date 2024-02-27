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

## Values for `usage`:
| Value | Name |
| --- | --- |
| 0 | COVUSE_WALLTOLEFT (Fires round to the right) |
| 1 | COVUSE_WALLTORIGHT (Fires round to the left) |
| 2 | COVUSE_WALLTOBOTH (Must fire over the top, used for low or high cover points) |
| 3 | COVUSE_WALLTONEITHER (Fires either left or right) |


## Values for `height`:
| Value | Name |
| --- | --- |
| 0 | Low |
| 1 | High (<Unused) |
| 2 | Toohigh |


## Values for `arc`:
| Value | Name |
| --- | --- |
| 0 | 180 |
| 1 | 120 |
| 2 | 90 |
| 3 | 0To60 |
| 4 | 300To0 |
| 5 | 0To45 |
| 6 | 315To0 |


NOTE: To take the coordinates of a cover point you'd like to create, do the following: Stand behind the object you'd like to take cover behind. Face towards the object you're standing behind. If you do it this way then the following is true: The heading that is output to your temp_debug.txt is the 'FLOAT direction' Another thing to bear in mind is: When setting COVERPOINT_USAGE, COVUSE_WALLTOLEFT will flip the ped out to his right hand side, and so COVUSE_WALLTORIGHT will flip the ped out to his left.


## Parameters
* **direction**: 
* **usage**: 
* **height**: 
* **arc**: 
* **isPriorityToPlayer**: (Default value: `False`)

---
ns: OBJECT
aliases: ["0x9b12f9a24fabedb0"]
---
## SET_LOCKED_UNSTREAMED_IN_DOOR_OF_TYPE

```c
// 0x9B12F9A24FABEDB0
void SET_LOCKED_UNSTREAMED_IN_DOOR_OF_TYPE(Hash modelHash, Vector3 vecPos, bool LockState, float fAutomaticRate, float fAutomaticDist, float fOpenRatio);
```

Will attempt to lock or unlock the door of the type at the position if existing as streamed in, if not will otherwise set an appropriate element in the global mapped locked gLockedObjects accordingly. bLockState = true - door locked bLockState = false - door unlocked fAutomaticRate; - The rate at which the door's open ratio gets adjusted when opening automatically, i.e. the inverse of the time it takes to open. If this is value is 0.0 the normal default value for the door type is used. Current allowed max is 5 for networked games. fAutomaticDist - The distance threshold at which the (slidinggaragebarrier) door should open at, in meters. If the value is 0.0, the default value is used. Current allowed max is 100 m for networked games. fOpenRatio - Opening ratio to lock the door at (i.e. 1.0 to lock open). Note for both the fAutomaticRate and fAutomaticDist parameter, if you want to use values other than default, you will need to ensure that when you initially Lock the door you use the same required value that is desired for the opening condition. So that when you later Unlock the door, the same value is passed in. This is in order to ensure that the door state is transmitted to remote machines. e.g. To make the door unlock at the full fastest rate you wold need to do the following: Lock: SET_LOCKED_UNSTREAMED_IN_DOOR_OF_TYPE (PROP_GATE_PRISON_01, <<1845, 2612, 45>>, TRUE, 1.0) Unlock: SET_LOCKED_UNSTREAMED_IN_DOOR_OF_TYPE (PROP_GATE_PRISON_01, <<1845, 2612, 45>>, FALSE,1.0) Or, if you wanted to make the door unlock at a distance of 50 m but leave the rate at the default value, you would need to do the following: Lock: SET_LOCKED_UNSTREAMED_IN_DOOR_OF_TYPE (PROP_GATE_PRISON_01, <<1845, 2612, 45>>, TRUE, 0.0, 50.0) Unlock: SET_LOCKED_UNSTREAMED_IN_DOOR_OF_TYPE (PROP_GATE_PRISON_01, <<1845, 2612, 45>>, FALSE,0.0, 50.0)


## Parameters
* **modelHash**: 
* **vecPos**: 
* **LockState**: 
* **fAutomaticRate**: (Default value: `0`)
* **fAutomaticDist**: (Default value: `0`)
* **fOpenRatio**: (Default value: `0`)

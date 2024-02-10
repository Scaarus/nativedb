---
ns: TASK
aliases: ["0x89d9fcc2435112f1"]
---
## TASK_CLIMB

```c
// 0x89D9FCC2435112F1
void TASK_CLIMB(bool UsePlayerLaunchForce);
```

```
Tells a ped to perform the climb task.

The ped needs to be positioned and oriented so that a jump will locate an edge for the ped to grab. If an edge can’t be found, the ped will just do a normal jump and land. If an edge can be found then the ped will climb and then stand on top of the found edge. Don't place the ped too far from the object you want him to climb, even if the player can make it and you set UsePlayerLaunchForce to TRUE, it won't guarantee that the ped will make it.
```

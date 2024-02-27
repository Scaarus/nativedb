---
ns: PLAYER
aliases: ["0x477d5d63e63eca5d"]
---
## SIMULATE_PLAYER_INPUT_GAIT

```c
// 0x477D5D63E63ECA5D
void SIMULATE_PLAYER_INPUT_GAIT(Player player, float moveBlendRatio, int timer, float heading, bool useRelativeHeading, bool noInputInterruption);
```

This will simulate the player's controller input. This simulation would move the player actor forward until the left stick is touched or the timer is reached.

To skip tranisation when coming out a cut scene, e.g., form idle to run, the vignette leadout should sequence the player to the run node.


## Parameters
* **player**: 
* **moveBlendRatio**: move blend ratio to simulate as if the player were inputing it on the controller. (1.
* **timer**: this can be interrupted if left stick is touched, in millisecond. (Default value: `2000`)
* **heading**: simulated heading. Range from -180.0 to 180.0 degrees. (Default value: `0`)
* **useRelativeHeading**: if the heading is global or local to the ped. (Default value: `True`)
* **noInputInterruption**: if true, don't break out on input changes, it just times out. (Default value: `False`)

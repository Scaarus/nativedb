---
ns: TASK
aliases: ["0x8423541e8b3a1589"]
---
## SET_TASK_MOVE_NETWORK_ANIM_SET

```c
// 0x8423541E8B3A1589
void SET_TASK_MOVE_NETWORK_ANIM_SET(int animSetHash, int animSetVariableHash);
```

Sets an anim set for this move network to use

The anim set hash is a hash of the name of the actual anim set to use e.g. SET_TASK_MOVE_NETWORK_ANIM_SET (playerPed, playerAnimSet) SET_TASK_MOVE_NETWORK_ANIM_SET (otherPed, otherAnimSet) will allow you to play the same move network with two different sets of anims on two different peds. The animSetVariableHash is the hash of the name of the variable anim set you are setting, and should start with a $ symbol e.g. a basic minigame network might have two seperate anim sets to fill in called $initial and $streamed To set them both

The anim set hash is a hash of the name of the actual anim set to use The animSetVariableHash is the has of the name of the variable anim set you are setting, and should start with a $ symbol


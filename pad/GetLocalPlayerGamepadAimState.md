---
ns: PAD
aliases: ["0x59b9a7af4c95133c"]
---
## GET_LOCAL_PLAYER_GAMEPAD_AIM_STATE

```c
// 0x59B9A7AF4C95133C
int GET_LOCAL_PLAYER_GAMEPAD_AIM_STATE();
```

Returns current player aim state (sometimes GET_PROFILE_SETTINGS doesn't return the correct one if not saved)

Will return the gamepad setting even if the player is playing on the keyboard and mouse.


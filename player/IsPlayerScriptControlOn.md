---
ns: PLAYER
aliases: ["0x8a876a65283dd7d7"]
---
## IS_PLAYER_SCRIPT_CONTROL_ON

```c
// 0x8A876A65283DD7D7
bool IS_PLAYER_SCRIPT_CONTROL_ON();
```

returns FALSE if the player control has been turned off by a script.

Even if this command returns TRUE, player control could still have been turned off by something else like camera or cutscene code


---
ns: PLAYER
aliases: ["0x388a47c51abdac8e"]
---
## IS_PLAYER_BEING_ARRESTED

```c
// 0x388A47C51ABDAC8E
bool IS_PLAYER_BEING_ARRESTED(bool CheckBustedTask);
```

## Parameters
* **CheckBustedTask**: If this is set to FALSE then we'll only rely on the player's game state, which is set to arrested once the player is no longer allowed to break out of the busted task (Default value: `True`)

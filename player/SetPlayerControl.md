---
ns: PLAYER
aliases: ["0x8d32347d6d4c40a2"]
---
## SET_PLAYER_CONTROL

```c
// 0x8D32347D6D4C40A2
void SET_PLAYER_CONTROL(bool SetControlOn, int iFlags);
```

```
Sets the players control state.

Possible values for iFlags:
| Index | Name |
| --- | --- |
| 0 | None |
| 2 | Ambient Script |
| 4 | Clear Tasks |
| 8 | Remove Fires |
| 16 | Remove Explosions |
| 32 | Remove Projectiles |
| 64 | Deactivate Gadgets |
| 128 | Reenable Control On Death |
| 256 | Leave Camera Control On |
| 512 | Allow Player Damage |
| 1024 | Dont Stop Other Cars Around Player |
| 2048 | Prevent Everybody Backoff |
| 4096 | Allow Pad Shake |


The flags are taken as a combination of the values in 'SET_PLAYER_CONTROL_FLAGS' above.

This command can be used to temporarily disable the player’s controls. The controls should be switched back on again as soon as possible. NOTE Turning this on will make vehicles proof from bullets etc. Likewise when the player controls are turned back on it will make ALL the vehicles vunerable again, so you will have to set them back with SET_CAR_CAN_BE_DAMAGED(vehicle_name, FALSE).
```

---
ns: PLAYER
aliases: ["0x048189fac643deee"]
---
## CHANGE_PLAYER_PED

```c
// 0x048189FAC643DEEE
void CHANGE_PLAYER_PED(Player player, Ped ped, bool KeepScriptedTasks, bool ClearPedDamage);
```

Changes the player from one Ped to another. After this command is called the players PED_INDEX will change to that of newPed. The old player ped will be left with the same PED_INDEX as the player had previously. The old player ped will be left as an AI mission character and it is up to the scripts to clean the old ped up using the players old PED_INDEX


## Parameters
* **player**: 
* **ped**: 
* **KeepScriptedTasks**: (Default value: `False`)
* **ClearPedDamage**: (Default value: `True`)

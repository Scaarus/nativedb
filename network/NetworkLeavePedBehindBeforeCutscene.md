---
ns: NETWORK
aliases: ["0xbf22e0f32968e967"]
---
## NETWORK_LEAVE_PED_BEHIND_BEFORE_CUTSCENE

```c
// 0xBF22E0F32968E967
void NETWORK_LEAVE_PED_BEHIND_BEFORE_CUTSCENE(Player player, bool keepPickups);
```

Leave an AI ped behind in place of the player when they are moving to an MP cutscene


## Parameters
* **player**: 
* **keepPickups**: if true then any portable pickups attached to the player are kept attached to him, otherwise they are detached (Default value: `False`)

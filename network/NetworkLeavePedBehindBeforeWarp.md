---
ns: NETWORK
aliases: ["0x9769f811d1785b03"]
---
## NETWORK_LEAVE_PED_BEHIND_BEFORE_WARP

```c
// 0x9769F811D1785B03
void NETWORK_LEAVE_PED_BEHIND_BEFORE_WARP(Player player, Vector3 NewPosition, bool killPed, bool keepPickups);
```

```
Leave an AI ped behind in place of the player when they are being warped to a new location
```

## Parameters
* **player**: 
* **NewPosition**: 
* **killPed**: 
* **keepPickups**: if true then any portable pickups attached to the player are kept attached to him, otherwise they are detached

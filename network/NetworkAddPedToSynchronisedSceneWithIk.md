---
ns: NETWORK
aliases: ["0xa5eafe473e45c442"]
---
## NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE_WITH_IK

```c
// 0xA5EAFE473E45C442
void NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE_WITH_IK(Ped ped, int NetworkSceneID, string animDictionary, string anim, float blendInDelta, float blendOutDelta, int flags, int ragdollFlags, float moverBlendInDelta, int ikFlags);
```

Adds a ped and associated animation data to a previous created network synchronised scene. Extends [`NETWORK_ADD_PED_TO_SYNCHRONISED_SCENE`](#_0x742A637471BCECD9) to support IK flags.

## Values for `flags`:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Use Physics |
| 2 | Tag Sync Out |
| 4 | Dont Interrupt |
| 8 | On Abort Stop Scene |
| 16 | Abort On Weapon Damage |
| 32 | Block Mover Update |
| 64 | Loop Within Scene |
| 128 | Preserve Velocity |
| 256 | Expand Ped Capsule From Skeleton |
| 512 | Activate Ragdoll On Collision |
| 1024 | Hide Weapon |
| 2048 | Abort On Death |
| 4096 | Vehicle Abort On Large Impact |
| 8192 | Vehicle Allow Player Entry |
| 16384 | Process Attachments On Start |
| 32768 | Net On Early Non Ped Stop Return To Start |
| 65536 | Set Ped Out Of Vehicle At Start |
| 131072 | Net Disregard Attachment Checks |


## Values for `ragdollFlags`:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Bullet Impact |
| 2 | Vehicle Impact |
| 4 | Fire |
| 8 | Electrocution |
| 16 | Player Impact |
| 32 | Explosion |
| 64 | Impact Object |
| 128 | Melee |
| 256 | Rubber Bullet |
| 512 | Falling |
| 1024 | Water Jet |
| 2048 | Drowning |
| 4096 | Allow Block Dead Ped |
| 8192 | Player Bump |
| 16384 | Player Ragdoll Bump |
| 32768 | Ped Ragdoll Bump |
| 65536 | Vehicle Grab |


## Parameters
* **ped**: 
* **NetworkSceneID**: 
* **animDictionary**: 
* **anim**: 
* **blendInDelta**: 
* **blendOutDelta**: 
* **flags**: (Default value: `None`)
* **ragdollFlags**: (Default value: `None`)
* **moverBlendInDelta**: (Default value: `1000`)
* **ikFlags**: (Default value: `0`)

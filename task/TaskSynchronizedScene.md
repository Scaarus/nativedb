---
ns: TASK
aliases: ["0xeea929141f699854"]
---
## TASK_SYNCHRONIZED_SCENE

```c
// 0xEEA929141F699854
void TASK_SYNCHRONIZED_SCENE(Ped ped, int sceneID, string animDictionary, string anim, float blendInDelta, float blendOutDelta, int flags, int ragdollFlags, float moverBlendInDelta, int ikFlags);
```

Starts a synchronized scene on the specified ped

## flags Values:
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


## ragdollFlags Values:
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


## ikFlags Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Disable Leg Ik |
| 2 | Disable Arm Ik |
| 4 | Disable Head Ik |
| 8 | Disable Torso Ik |
| 16 | Disable Torso React Ik |
| 32 | Use Leg Allow Tags |
| 64 | Use Leg Block Tags |
| 128 | Use Arm Allow Tags |
| 256 | Use Arm Block Tags |
| 512 | Process Weapon Hand Grip |
| 1024 | Use Fp Arm Left |
| 2048 | Use Fp Arm Right |
| 4096 | Disable Torso Vehicle Ik |
| 8192 | Linked Facial |


## Parameters
* **ped**: 
* **sceneID**: the scene index to start on
* **animDictionary**: 
* **anim**: 
* **blendInDelta**: the rate at which the task will blend in The blend in duration is 1.0 blendInDelta e.g. 1.0 NORMAL_BLEND_IN -> 1.0 8.0 = 0.125 seconds
* **blendOutDelta**: the rate at which the task will blend out The blend out duration is -1.0 blendOutDelta e.g. -1.0 NORMAL_BLEND_OUT -> -1.0 -8.0 = 0.125 seconds should create remove the task without a frame's delay
* **flags**: A set of flags allowing for different playback options (SYNCED_SCENE_PLAYBACK_FLAGS for a description) (Default value: `None`)
* **ragdollFlags**: Determines which ragdoll reactions to disable while the scene is running. (Default value: `None`)
* **moverBlendInDelta**: (Default value: `Instant_Blend_In`)
* **ikFlags**: (Default value: `None`)

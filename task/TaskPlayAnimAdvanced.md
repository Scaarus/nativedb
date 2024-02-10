---
ns: TASK
aliases: ["0x83cdb10ea29b370b"]
---
## TASK_PLAY_ANIM_ADVANCED

```c
// 0x83CDB10EA29B370B
void TASK_PLAY_ANIM_ADVANCED(Ped ped, string pAnimDictName, Vector3 pos, Vector3 rot, float fBlendInDelta, float fBlendOutDelta, int nTimeToPlay, int AnimFlags, float startPhase, int RotOrder, int ikFlags);
```

```
Plays an anim task on a ped with a reposition and reorientation at the beginning.

Possible values for AnimFlags:
| Index | Name |
| --- | --- |
| 0 | Default |
| 1 | Looping |
| 2 | Hold Last Frame |
| 4 | Reposition When Finished |
| 8 | Not Interruptable |
| 16 | Upperbody |
| 32 | Secondary |
| 64 | Reorient When Finished |
| 128 | Abort On Ped Movement |
| 256 | Additive |
| 264 | Disable Forced Physics Update Prevent Adjusting The Capsule On The Enter State (Useful If Script Is Doing A Sequence Of Scripted Anims And They Are Known To More Or Less Stand Still) |
| 512 | Turn Off Collision |
| 1024 | Override Physics |
| 2048 | Ignore Gravity |
| 4096 | Extract Initial Offset |
| 8192 | Exit After Interrupted |
| 16384 | Tag Sync In |
| 32768 | Tag Sync Out |
| 65536 | Tag Sync Continuous |
| 131072 | Force Start |
| 262144 | Use Kinematic Physics |
| 524288 | Use Mover Extraction |
| 1048576 | Hide Weapon |
| 2097152 | Ends In Dead Pose |
| 4194304 | Activate Ragdoll On Collision |
| 8388608 | Dont Exit On Death |
| 16777216 | Abort On Weapon Damage |
| 67108864 | Process Attachments On Start |
| 134217728 | Expand Ped Capsule From Skeleton |
| 268435456 | Use Alternative Fp Anim |
| 536870912 | Blendout Wrt Last Frame |
| 1073741824 | Use Full Blending |


Possible values for RotOrder:
| Index | Name |
| --- | --- |
| 0 | Xyz |
| 1 | Xzy |
| 2 | Yxz |
| 3 | Yzx |
| 4 | Zxy |
| 5 | Zyx |
| 6 | Max |


Possible values for ikFlags:
| Index | Name |
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


As for task_play_anim, but provides the function to specify an inital position and rotation to playback the anim from
```

## Parameters
* **ped**: 
* **pAnimDictName**: 
* **pos**: 
* **rot**: 
* **fBlendInDelta**: the rate at which the task will blend in The blend in duration is 1.0 fBlendInDelta e.g. 1.0 NORMAL_BLEND_IN -> 1.0 8.0 = 0.125 seconds
* **fBlendOutDelta**: the rate at which the task will blend out The blend out duration is -1.0 fBlendOutDelta e.g. -1.0 NORMAL_BLEND_OUT -> -1.0 -8.0 = 0.125 seconds
* **nTimeToPlay**: 
* **AnimFlags**: 
* **startPhase**: 
* **RotOrder**: 
* **ikFlags**: 

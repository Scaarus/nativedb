---
ns: TASK
aliases: ["0xea47fe3719165b94"]
---
## TASK_PLAY_ANIM

```c
// 0xEA47FE3719165B94
void TASK_PLAY_ANIM(Ped ped, string pAnimDictName, float fBlendInDelta, float fBlendOutDelta, int nTimeToPlay, int AnimFlags, float startPhase, bool phaseControlled, int ikFlags, bool AllowOverrideCloneUpdate);
```

Plays a anim task on a ped.

## AnimFlags Values:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Looping |
| 2 | Hold Last Frame |
| 3 | Disable Forced Physics Update (Prevent Adjusting The Capsule On The Enter State (Useful If Script Is Doing A Sequence Of Scripted Anims And They Are Known To More Or Less Stand Still)) |
| 4 | Reposition When Finished |
| 8 | Not Interruptable |
| 16 | Upperbody |
| 32 | Secondary |
| 64 | Reorient When Finished |
| 128 | Abort On Ped Movement |
| 256 | Additive |
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


Flags:The flags parameter is made by combining any of the following flags using the or key which looks like this | Including a flag is like setting it to true Omitting a flag is like setting it to false See the definition of ENUM ANIMATION_FLAGS (above) for more information on the anim flags bAllowOverrideCloneUpdate is used in MP and has this

Plays an anim on the specified ped


## Parameters
* **ped**: 
* **pAnimDictName**: 
* **fBlendInDelta**: the rate at which the task will blend in The blend in duration is 1.0 fBlendInDelta e.g. 1.0 NORMAL_BLEND_IN -> 1.0 8.0 = 0.125 seconds (Default value: `Normal_Blend_In`)
* **fBlendOutDelta**: (Default value: `Normal_Blend_Out`)
* **nTimeToPlay**: 
* **AnimFlags**: (Default value: `Default`)
* **startPhase**: (Default value: `0`)
* **phaseControlled**: (Default value: `False`)
* **ikFlags**: (Default value: `None`)
* **AllowOverrideCloneUpdate**: (Default value: `False`)

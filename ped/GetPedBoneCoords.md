---
ns: PED
aliases: ["0x17c07fc640e86b4e"]
---
## GET_PED_BONE_COORDS

```c
// 0x17C07FC640E86B4E
Vector3 GET_PED_BONE_COORDS(Ped ped, int bone, Vector3 vecOffset);
```

Gets the coord of the peds bone

## Values for `bone`:
| Value | Name |
| --- | --- |
| -1 | Null |
| 0 | Root |
| 2108 | L Toe |
| 4089 | L Finger01 |
| 4090 | L Finger02 |
| 4137 | L Finger31 |
| 4138 | L Finger32 |
| 4153 | L Finger41 |
| 4154 | L Finger42 |
| 4169 | L Finger11 |
| 4170 | L Finger12 |
| 4185 | L Finger21 |
| 4186 | L Finger22 |
| 10706 | R Clavicle |
| 11816 | Pelvis |
| 14201 | L Foot |
| 18905 | L Hand |
| 20781 | R Toe |
| 23553 | Spine |
| 24816 | Spine1 |
| 24817 | Spine2 |
| 24818 | Spine3 |
| 26610 | L Finger0 |
| 26611 | L Finger1 |
| 26612 | L Finger2 |
| 26613 | L Finger3 |
| 26614 | L Finger4 |
| 28252 | R Forearm |
| 28422 | Ph R Hand |
| 31086 | Head |
| 36864 | R Calf |
| 39317 | Neck |
| 40269 | R Upperarm |
| 45509 | L Upperarm |
| 51826 | R Thigh |
| 52301 | R Foot |
| 57005 | R Hand |
| 58271 | L Thigh |
| 58866 | R Finger0 |
| 58867 | R Finger1 |
| 58868 | R Finger2 |
| 58869 | R Finger3 |
| 58870 | R Finger4 |
| 60309 | Ph L Hand |
| 61163 | L Forearm |
| 63931 | L Calf |
| 64016 | R Finger01 |
| 64017 | R Finger02 |
| 64064 | R Finger31 |
| 64065 | R Finger32 |
| 64080 | R Finger41 |
| 64081 | R Finger42 |
| 64096 | R Finger11 |
| 64097 | R Finger12 |
| 64112 | R Finger21 |
| 64113 | R Finger22 |
| 64729 | L Clavicle |


Check that [`WAS_PED_SKELETON_UPDATED`](#_0x11B499C1E0FF8559) returns TRUE before calling this function


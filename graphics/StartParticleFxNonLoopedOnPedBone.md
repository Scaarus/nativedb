---
ns: GRAPHICS
aliases: ["0x0e7e72961ba18619"]
---
## START_PARTICLE_FX_NON_LOOPED_ON_PED_BONE

```c
// 0x0E7E72961BA18619
bool START_PARTICLE_FX_NON_LOOPED_ON_PED_BONE(string fxName, Ped ped, Vector3 vecPosition, Vector3 vecRotation, int boneTag, float scale, bool invertAxisX, bool invertAxisY, bool invertAxisZ);
```

Trigger a set piece (non looped) particle effect on a ped bone with an offset position and orientation.

## boneTag Values:
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


STRING STRING

Triggers a named particle effect on a ped bone at an offset position and rotation. This should only be used with non-looped particle effects. The particle effect will then play and tidy itself up when finished. There is no access to the particle effect once it has been triggered.


## Parameters
* **fxName**: the name of the particle effect to be triggered PED_INDEX
* **ped**: 
* **vecPosition**: 
* **vecRotation**: 
* **boneTag**: the bone tag to attach the particle effect to FLOAT
* **scale**: size scale of the effect (default size = 1.0)
* **invertAxisX**: 
* **invertAxisY**: 
* **invertAxisZ**: 

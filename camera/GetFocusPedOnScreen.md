---
ns: CAMERA
aliases: ["0x89215ec747df244a"]
---
## GET_FOCUS_PED_ON_SCREEN

```c
// 0x89215EC747DF244A
Ped GET_FOCUS_PED_ON_SCREEN(float maxDistanceFromCamera, int screenPositionTestBoneTag, float maxScreenWidthRatioAroundCentreForTestBone, float maxScreenHeightRatioAroundCentreForTestBone, float minRelativeHeadingScore, float maxScreenCentreScoreBoost, float maxScreenRatioAroundCentreForScoreBoost, int losTestBoneTag1, int losTestBoneTag2);
```

Finds the best candidate on-screen focus/subject ped.

## screenPositionTestBoneTag Values:
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


## Parameters
* **maxDistanceFromCamera**: The maximum valid distance from the camera to candidate peds. (Default value: `30`)
* **screenPositionTestBoneTag**: If valid (not BONETAG_NULL), this specified the candidate ped bone to be tested for valid screen position. (Default value: `Head`)
* **maxScreenWidthRatioAroundCentreForTestBone**: The ratio of the screen width around the screen centre within which the specified test bone of a candidate ped must be located. (Default value: `0`)
* **maxScreenHeightRatioAroundCentreForTestBone**: The ratio of the screen height around the screen centre within which the specified test bone of a candidate ped must be located. (Default value: `0`)
* **minRelativeHeadingScore**: Defines the minimum scaling of a candidate ped's score that will be applied if the ped is at the far left or far right of the screen (at the maximum camera-relative heading.) (Default value: `0`)
* **maxScreenCentreScoreBoost**: The maximum factor by which to boost a candidate ped's score when they are roughly centred on the screen. (Default value: `8`)
* **maxScreenRatioAroundCentreForScoreBoost**: The ratio of the screen width located around the screen centre to apply the screenCentreScoreBoost. (Default value: `0`)
* **losTestBoneTag1**: (Default value: `Head`)
* **losTestBoneTag2**: (Default value: `Spine3`)

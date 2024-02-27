---
ns: PED
aliases: ["0x2f074c904d85129e"]
---
## SET_COP_PERCEPTION_OVERRIDES

```c
// 0x2F074C904D85129E
void SET_COP_PERCEPTION_OVERRIDES(float fSeeingRange, float fSeeingRangePeripheral, float fHearingRange, float fMinAzimuthAngle, float fMaxAzimuthAngle, float fCentreOfGazeMaxAngle, float fRearViewSeeingRangeOverride);
```

Allows script to override the cop perception parameters. This affects all code-spawned, non-mission cops. Parameters will not be overridden if left at their default values (these are the standard values already used by cops). NOTE: This command must be called every frame!


## Parameters
* **fSeeingRange**: how far away a ped can identify the ped (default on (Default value: `60`)
* **fSeeingRangePeripheral**: how far the perhiperal vision extends (doesn't affect rendered cone blip). (Default value: `5`)
* **fHearingRange**: how far a ped can hear (default on (Default value: `60`)
* **fMinAzimuthAngle**: MIN horizontal field of view for the ped (doesn't affect rendered cone blip).
* **fMaxAzimuthAngle**: MAX horizontal field of view for the ped (doesn't affect rendered cone blip). (Default value: `90`)
* **fCentreOfGazeMaxAngle**: Defines the central angle. (Default value: `60`)
* **fRearViewSeeingRangeOverride**: Override rear view mirror perception range (when in vehicle). Will use default range (fSeeingRange) if set to -1.0f. on all of these params in the wiki.

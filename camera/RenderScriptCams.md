---
ns: CAMERA
aliases: ["0x07e5b515db0636fc"]
---
## RENDER_SCRIPT_CAMS

```c
// 0x07E5B515DB0636FC
void RENDER_SCRIPT_CAMS(bool SetActive, bool DoGameCamInterp, int Duration, bool ShouldLockInterpolationSourceFrame, bool ShouldApplyAcrossAllThreads, int RenderingOptions);
```

Tells the game that the script wants to enable or disable rendering of scripted cameras.

This enum is deprecated. Please use CAM_VIEW_MODE instead Allows for custom options to be specified for the node of a camera spline. Must match camSplineNode::eFlags in camerahelpersSplineNode.h Allows for custom options to be specified for the node of a camera spline. Must match camSplineNode::eFlags in camerahelpersSplineNode.h Type of hint to call to override the default hint behaviour Camera types Shot Type Must match camInterface::eDeathFailEffectState in cameraCamInterface.h ~> Camera High Level <~

## Values for `RenderingOptions`:
| Value | Name |
| --- | --- |
| 0 | No Options |
| 1 | Stop Rendering Option When Player Exits Into Cover |


The script must have created a camera that can be rendered. Note that rendering is typically not stopped if another script thread still expects it to be active (see bShouldApplyAcrossAllThreads.)


## Parameters
* **SetActive**: 
* **DoGameCamInterp**: If true, the rendering change is implemented as an interpolation.
* **Duration**: Specifies the duration of any interpolation. (Default value: `Default_Interp_To_From_Game`)
* **ShouldLockInterpolationSourceFrame**: If false, the source frame is updated throughout the interpolation, allowing for fully dynamic interpolation that can reduce the appearance of 'lag' when the source frame is not static. (Default value: `True`)
* **ShouldApplyAcrossAllThreads**: If true, a request to stop rendering will be enforced irrespective of whether other script threads expect rendering to be active. Note that this can result in conflicts between concurrent script threads, so this must be used with caution. (Default value: `False`)
* **RenderingOptions**: (Default value: `No Options`)

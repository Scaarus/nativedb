---
ns: CAMERA
aliases: ["0xc819f3cbb62bf692"]
---
## STOP_RENDERING_SCRIPT_CAMS_USING_CATCH_UP

```c
// 0xC819F3CBB62BF692
void STOP_RENDERING_SCRIPT_CAMS_USING_CATCH_UP(bool ShouldApplyAcrossAllThreads, float DistanceToBlend, int BlendType, int RenderingOptions);
```

Tells the game that the script wants to disable rendering of scripted cameras and force gameplay camera to blend from scripted camera to gameplay camera.

## Values for `BlendType`:
| Value | Name |
| --- | --- |
| 0 | No Smooth |
| 1 | Slow In Smooth |
| 2 | Slow Out Smooth |
| 3 | Slow In Out Smooth |
| 4 | Very Slow In |
| 5 | Very Slow Out |
| 6 | Very Slow In Slow Out |
| 7 | Slow In Very Slow Out |
| 8 | Very Slow In Very Slow Out |
| 9 | Ease In |
| 10 | Ease Out |
| 11 | Quadratic Ease In |
| 12 | Quadratic Ease Out |
| 13 | Quadratic Ease In Out |
| 14 | Cubic Ease In |
| 15 | Cubic Ease Out |
| 16 | Cubic Ease In Out |
| 17 | Quartic Ease In |
| 18 | Quartic Ease Out |
| 19 | Quartic Ease In Out |
| 20 | Quintic Ease In |
| 21 | Quintic Ease Out |
| 22 | Quintic Ease In Out |
| 23 | Circular Ease In |
| 24 | Circular Ease Out |
| 25 | Circular Ease In Out |


## Values for `RenderingOptions`:
| Value | Name |
| --- | --- |
| 0 | No Options |
| 1 | Stop Rendering Option When Player Exits Into Cover |


The script must have created a camera that can be rendered. Note that rendering is typically not stopped if another script thread still expects it to be active (see bShouldApplyAcrossAllThreads.)


## Parameters
* **ShouldApplyAcrossAllThreads**: If true, a request to stop rendering will be enforced irrespective of whether other script threads expect rendering to be active. Note that this can result in conflicts between concurrent script threads, so this must be used with caution. (Default value: `False`)
* **DistanceToBlend**: overrides the distance over which the catch up blend occurs, if zero is specified, default blend distance will be used. (Default value: `0`)
* **BlendType**: (Default value: `Slow In Out Smooth`)
* **RenderingOptions**: (Default value: `No Options`)

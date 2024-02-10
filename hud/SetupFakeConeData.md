---
ns: HUD
aliases: ["0xf83d0febe75e62c9"]
---
## SETUP_FAKE_CONE_DATA

```c
// 0xF83D0FEBE75E62C9
void SETUP_FAKE_CONE_DATA(Blip blip, float fVisualFieldMinAzimuthAngle, float fVisualFieldMaxAzimuthAngle, float fCentreOfGazeMaxAngle, float fPeripheralRange, float fFocusRange, float fRotation, bool ContinuousUpdate, int iHudColor);
```

```
Sets up data for a fake blip cone. This must be set before the blip is flagged to draw a cone.
```

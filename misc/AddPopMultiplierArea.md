---
ns: MISC
aliases: ["0x67f6413d3220e18d"]
---
## ADD_POP_MULTIPLIER_AREA

```c
// 0x67F6413D3220E18D
int ADD_POP_MULTIPLIER_AREA(Vector3 minWS, Vector3 maxWS, float pedDensity, float trafficDensity, bool localOnly, bool CameraGlobalMultiplier);
```

bCameraGlobalMultiplier TRUE  = the effect of this area is to GLOBALLY multiply densities for spawning in the whole world, whenever the camera is within the specified zone (default original behaviour) FALSE = the effect of this area is to LOCALLY multiply densities for only spawning which occurs within the specified zone, and regardless of where the camera is MAX allowed areas is 10. Let code know if that needs increasing


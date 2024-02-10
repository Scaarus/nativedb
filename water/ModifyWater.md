---
ns: WATER
aliases: ["0xc443fd757c3ba637"]
---
## MODIFY_WATER

```c
// 0xC443FD757C3BA637
void MODIFY_WATER(float worldX, float worldY, float newSpeed, float rate);
```

```
Modify water speed..

Allow interaction with water. This will create a disturbance in the water at coordinates (worldX,worldY). newSpeed control the amplitude of movement to be applied to the water (between 0 and 5) rate controls the blend between the current water speed at this point and newSpeed (0: no change, 1: newSpeed).
```

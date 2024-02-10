---
ns: GRAPHICS
aliases: ["0x1c4fc5752bcd8e48"]
---
## TERRAINGRID_SET_PARAMS

```c
// 0x1C4FC5752BCD8E48
void TERRAINGRID_SET_PARAMS(Vector3 centrePos, Vector3 dir, float boxWidth, float boxHeight, float boxDepth, float gridRes, float colMult, float minHeight, float maxHeight);
```

```
Sets all the parameters needed to render a grid

centrePos is the centre position of the projection box used to draw the grid. dir is a unit vector representing the orientation of the box boxWidth, boxHeight and boxDepth define the dimensions of the projection box (a depth of 1 should be enough in most cases) gridRes determines the size of each cell within the grid colMult is a multiplier applied to the final colour to make grid brighter or more subtle minHeight and maxHeight are the minimum and maximum heights used for the elevation colouring Note that most, if not all of these params should have been gathered via the RAG > Terrain Grid widget
```

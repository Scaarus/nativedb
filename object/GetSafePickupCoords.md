---
ns: OBJECT
aliases: ["0x6e16bc2503ff1ff0"]
---
## GET_SAFE_PICKUP_COORDS

```c
// 0x6E16BC2503FF1FF0
Vector3 GET_SAFE_PICKUP_COORDS(Vector3 InPosition, float minDist, float maxDist);
```

Gets a safe coord at which to create a pickup close to the input co-ordinates

minDist (=1.2) the minimum distance away we can be, maxDist (=1.5) the maximum distance away we can be. We will always aim for the minimum distance but will expand out in 0.05m increments if we continue to fail to find positions. If we ever reach maxDist we start at minDist again as we continue


## Parameters
* **InPosition**: 
* **minDist**: (Default value: `1`)
* **maxDist**: (Default value: `1`)

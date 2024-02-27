---
ns: PED
aliases: ["0xcd5003b097200f36"]
---
## GET_DEAD_PED_PICKUP_COORDS

```c
// 0xCD5003B097200F36
Vector3 GET_DEAD_PED_PICKUP_COORDS(Ped ped, float minDist, float maxDist);
```

Gets a suitable position for creating a pickup near a ped

minDist (=1.2) the minimum distance away we can be, maxDist (=1.5) the maximum distance away we can be. We will always aim for the minimum distance but will expand out in 0.05m increments if we continue to fail to find positions. If we ever reach maxDist we start at minDist again as we continue


## Parameters
* **ped**: 
* **minDist**: (Default value: `1`)
* **maxDist**: (Default value: `1`)

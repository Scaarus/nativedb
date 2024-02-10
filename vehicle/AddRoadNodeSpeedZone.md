---
ns: VEHICLE
aliases: ["0x2ce544c68fb812a0"]
---
## ADD_ROAD_NODE_SPEED_ZONE

```c
// 0x2CE544C68FB812A0
int ADD_ROAD_NODE_SPEED_ZONE(Vector3 center, float radius, float maxSpeed, bool AllowAffectMissionVehs);
```

Adds a road speed zone at the specified position+radius. Cars cruising in this volume will travel] at a max speed of the param "maxSpeed". This only affects cars running TASK_VEHICLE_CRUISE


## Parameters
* **center**: Position to add the speed zone
* **radius**: Radius
* **maxSpeed**: Maximum speed that vehicles will cruise in this area
* **AllowAffectMissionVehs**: Should this also slow down mission vehicles RETURNS The index of the speed node. You will need to save this in order to remove it properly

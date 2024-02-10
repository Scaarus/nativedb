---
ns: CUTSCENE
aliases: ["0x9896ce4721be84ba"]
---
## SET_CUTSCENE_TRIGGER_AREA

```c
// 0x9896CE4721BE84BA
void SET_CUTSCENE_TRIGGER_AREA(Vector3 vOffsetFromSceneOrigin, float fTriggerRadius, float fTriggerOrient, float fTriggerAngle);
```

```
Allows you to set up a special cut scene trigger area.

vOffsetFromSceneOrigin:Ofset vector for the centre of the trigger area

Depending on the type of of cutscene it maybe possible orientate the cutscene over a range of angles.
```

## Parameters
* **vOffsetFromSceneOrigin**: 
* **fTriggerRadius**: Size of the trigger area
* **fTriggerOrient**: The orientation of the trigger angle
* **fTriggerAngle**: The angle either side og the trigger

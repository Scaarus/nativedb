---
ns: OBJECT
aliases: ["0x2fdff4107b8c1147"]
---
## SLIDE_OBJECT

```c
// 0x2FDFF4107B8C1147
bool SLIDE_OBJECT(Vector3 DestPositiont, bool StopOnCollision);
```

Moves the object by the step values each frame until it is at the correct position

If StopForCollisionFlag is TRUE then the command will also return TRUE if the object has collided with a ped or vehicle (this functionality is currently disabled).

This command returns TRUE when the object is in the required position. You will need to work out the exact increment. An easier way is to use SLIDE_OBJECT_TO_COORD from SCRIPT_OBJECT.sch


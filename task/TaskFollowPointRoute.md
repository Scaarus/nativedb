---
ns: TASK
aliases: ["0x595583281858626e"]
---
## TASK_FOLLOW_POINT_ROUTE

```c
// 0x595583281858626E
void TASK_FOLLOW_POINT_ROUTE(Ped ped, float MoveBlendRatio, int Mode);
```

```
Tells a ped to follow a point route.

Possible values for Mode:
| Index | Name |
| --- | --- |
| 0 | Single |
| 9 | Return Go Once Then Return Back Once Following The Route Backwards |
| 10 | Season As Above But For Forever |
| 11 | Loop Treat The Points As A Loop, I.E Follow It To The End Then Directly Back To The First Position, Forever. |
```

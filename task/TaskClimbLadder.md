---
ns: TASK
aliases: ["0xb6c987f9285a3814"]
---
## TASK_CLIMB_LADDER

```c
// 0xB6C987F9285A3814
void TASK_CLIMB_LADDER(bool Fast);
```

Tells a ped to perform a climb ladder task.

This command handles everything needed to make a ped get on a ladder at the top or bottom, climb/descend it, and get off at the other end. The task decides whether the ped is supposed to climb or descend by examining which end of the ladder is nearest. The ped needs to be positioned right next to the ladder they are supposed to use, and should also be facing it. There are two possibilities for mounting the ladder - at the base of the ladder facing towards the front of it, and at the top of the ladder facing the reverse of the ladder. See the image below. If successful, the ped will get on the ladder, climb, and then get off.


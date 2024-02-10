---
ns: CAMERA
aliases: ["0x741b0129d4560f31"]
---
## CREATE_CINEMATIC_SHOT

```c
// 0x741B0129D4560F31
void CREATE_CINEMATIC_SHOT(int Shot, int DurationInMilliseconds, Entity entity, Entity entity);
```

```
Create a cinematic shot to be used by script.

Possible values for Shot:
| Index | Name |
| --- | --- |
| 74 | Camera Man |
| 75 | Heli Chase |
| 76 | Vehicle Mounted Camera |


SHOT_TYPE - Taken from the list of defined shots Duration of the shot in mili seconds after whch the shot will terminate Attach and look at entities: Depending on the shot you either provide one or two. If incorrectly applied the shot will just not trigger. This command is bound to a specific script so you cannot create one if another script already has The shots will terminate if rendering and the script terminates
```

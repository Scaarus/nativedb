---
ns: CUTSCENE
aliases: ["0x8d9df6eca8768583"]
---
## SET_SCRIPT_CAN_START_CUTSCENE

```c
// 0x8D9DF6ECA8768583
void SET_SCRIPT_CAN_START_CUTSCENE(int ScriptThread);
```

```
Allows a script to start a cutscene though it didnt request it.

This command only needs to be called if the script that loads the cutscene is not the same as the script that starts the scene This will largely be used by the main script requesting a scene and then allowing the mission script to start it.
```

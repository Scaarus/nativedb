---
ns: AUDIO
aliases: ["0x49b99bf3fda89a7a"]
---
## DOES_CONTEXT_EXIST_FOR_THIS_PED

```c
// 0x49B99BF3FDA89A7A
bool DOES_CONTEXT_EXIST_FOR_THIS_PED(Ped ped, string context, bool allowBackupPVG);
```

```
Checks if the context exists for the ped, searching through the voices in its PedVoiceGroup. The final argument can be set to true to allow searching in backup PVGs
```

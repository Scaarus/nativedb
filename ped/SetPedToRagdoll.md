---
ns: PED
aliases: ["0xae99fb955581844a"]
---
## SET_PED_TO_RAGDOLL

```c
// 0xAE99FB955581844A
bool SET_PED_TO_RAGDOLL(int MinTime, int MaxTime, int StartTask, bool AbortIfInjured, bool AbortIfDead, bool ForceScriptControl);
```

Sets a ped into a rag doll state.

## StartTask Values:
| Value | Name |
| --- | --- |
| 0 | Relax |
| 1326 | Nm Script |
| 1327 | Nm Balance |


MinTime and MaxTime sets the boundary times that the ped will ragdoll for. RAGDOLL_FALL_TYPES in nm_strings.sch, bForceScriptControl will stop the ped from becoming injured so they can complete their behaviours.

A ped will only switch to a ragdoll if it's onscreen and within range of the player.


## Parameters
* **MinTime**: 
* **MaxTime**: 
* **StartTask**: 
* **AbortIfInjured**: 
* **AbortIfDead**: 
* **ForceScriptControl**: If you require to control a ped's ragdoll even though they may take additional damage This both stops the ped from becoming injured and lowers the magnitude of any bullet impact forces.

---
ns: AUDIO
aliases: ["0xa8a7d434afb4b97b"]
---
## BLOCK_SPEECH_CONTEXT_GROUP

```c
// 0xA8A7D434AFB4B97B
void BLOCK_SPEECH_CONTEXT_GROUP(string GroupName, int Target);
```

Stop a certain group of peds from using a certain group of speech contexts. Note that the block will be automatically removed when the calling script finishes

## Values for `Target`:
| Value | Name |
| --- | --- |
| 0 | Player |
| 1 | Npcs |
| 2 | Buddys |
| 3 | Everyone |
| 4 | Targets Total |


## Parameters
* **GroupName**: the name of the context group to be blocked
* **Target**: the group of peds that should use the context (player, NPC, buddy, everyone)

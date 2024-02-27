---
ns: TASK
aliases: ["0x8c338e0263e4fd19"]
---
## TASK_CHAT_TO_PED

```c
// 0x8C338E0263E4FD19
void TASK_CHAT_TO_PED(Ped ped, int ChatFlags, Vector3 vOptionalGoToPosition, float fOptionalHeading, float fIdleTime);
```

Tells the ped to chat to a ped (see wiki)

## Values for `ChatFlags`:
| Value | Name |
| --- | --- |
| 1 | Is Initiator |
| 2 | Do Quick Chat |
| 4 | Go To Specific Pos |
| 8 | Use Custom Heading |
| 16 | Auto Chat |
| 32 | Play Greeting Gestures |
| 64 | Play Goodbye Gestures |


vOptionalGoToPosition, fOptionalHeading and fIdleTime are only used if CF_GO_TO_SPECIFIC_POS and CF_USE_CUSTOM_HEADING are set fIdleTime specifies an extra wait period after an anim has finished, calls to IS_CHATTING_PED_PLAYING_ANIM will return false during this period


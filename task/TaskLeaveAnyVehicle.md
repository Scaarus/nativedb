---
ns: TASK
aliases: ["0x504d54df3f6f2247"]
---
## TASK_LEAVE_ANY_VEHICLE

```c
// 0x504D54DF3F6F2247
void TASK_LEAVE_ANY_VEHICLE(int DelayTime, int iFlags);
```

Tells the ped to leave any vehicle.

## iFlags Values:
| Value | Name |
| --- | --- |
| 1 | Resume If Interrupted |
| 2 | Warp Entry Point |
| 8 | Jack Anyone |
| 16 | Warp Ped |
| 64 | Dont Wait For Vehicle To Stop |
| 256 | Dont Close Door |
| 512 | Warp If Door Is Blocked |
| 4096 | Jump Out |
| 65536 | Dont Default Warp If Door Blocked |
| 131072 | Use Left Entry |
| 262144 | Use Right Entry |
| 524288 | Just Pull Ped Out |
| 1048576 | Block Seat Shuffling |
| 4194304 | Warp If Shuffle Link Is Blocked |
| 8388608 | Dont Jack Anyone |
| 16777216 | Wait For Entry Point To Be Clear |


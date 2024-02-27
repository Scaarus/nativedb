---
ns: OBJECT
aliases: ["0x5c29f698d404c5e1"]
---
## SET_STATE_OF_RAYFIRE_MAP_OBJECT

```c
// 0x5C29F698D404C5E1
void SET_STATE_OF_RAYFIRE_MAP_OBJECT(Rayfire rayfire, int state);
```

Set the state of the map object if found.

## Values for `state`:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Init |
| 1 | Sync Starting |
| 2 | Starting |
| 3 | Start |
| 4 | Priming |
| 5 | Primed |
| 6 | Start Anim |
| 7 | Animating |
| 8 | Sync Ending |
| 9 | Ending |
| 10 | End |
| 11 | Reset |
| 12 | Pause |
| 13 | Resume |
| 14 | Priming Prelude |
| 15 | Abandon |


To set a ray fire object up for the map. If you find the named ray fire object Set its state to RFMO_STATE_PRIMING Check that its primed. When primed Set its state to CE_STATE_START_ANIM Note: script can only set the following rayfire states: RFMO_STATE_STARTING RFMO_STATE_PRIMING RFMO_STATE_START_ANIM RFMO_STATE_ENDING RFMO_STATE_RESET RFMO_STATE_PAUSED RFMO_STATE_RESUME


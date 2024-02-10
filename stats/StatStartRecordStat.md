---
ns: STATS
aliases: ["0x33d72899e24c3365"]
---
## STAT_START_RECORD_STAT

```c
// 0x33D72899E24C3365
bool STAT_START_RECORD_STAT(int stat, int policy);
```

Policy for the recording of the stats using the commands below. Policy for the recording of the stats using the commands below. PURPOSE Start recording a stat until stop is called. NOTES See enum above for the stats that are supported

## stat Values:
| Value | Name |
| --- | --- |
| 76 | None |
| 77 | Longest Wheelie Dist |
| 78 | Longest Stoppie Dist |
| 79 | Longest Drive Nocrash |
| 80 | Top Speed Car |
| 81 | Most Flips In One Jump |
| 82 | Most Spins In One Jump |
| 83 | Highest Jump Reached |
| 84 | Farthest Jump Dist |
| 85 | Number Near Miss Nocrash |
| 86 | Longest Survived Freefall |
| 87 | Lowest Parachute Open |
| 88 | Dist Driving Car Reverse |
| 89 | Longest Survived Skydive |
| 90 | Number Stolen Vehicle |
| 91 | Players Set On Fire |
| 92 | On Foot Altitude |
| 93 | Flight Time Below 20 |
| 94 | Flight Dist Below 20 |
| 95 | Flight Time Below 100 |
| 96 | Flight Dist Below 100 |
| 97 | Plane Barrel Rolls |
| 98 | Melee Killed Players |
| 99 | Sniper Kill Distance |
| 100 | Sniper Kill |
| 101 | Db Non Turret Player Kills |
| 102 | Player Headshots |
| 103 | Dist Bailing From Vehicle |
| 104 | Player Vehicle Damages |
| 105 | Near Miss Precise |
| 106 | Dist Beaching Boat |
| 107 | Dist Wallride |


## policy Values:
| Value | Name |
| --- | --- |
| 1 | Sum |
| 2 | Greatest |
| 3 | Lowest |


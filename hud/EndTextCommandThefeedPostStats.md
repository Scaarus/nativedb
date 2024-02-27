---
ns: HUD
aliases: ["0x2b7e9a4eaaa93c89"]
---
## END_TEXT_COMMAND_THEFEED_POST_STATS

```c
// 0x2B7E9A4EAAA93C89
int END_TEXT_COMMAND_THEFEED_POST_STATS(string sTitleString, int eIcon, int iTotalLevel, int iCurrentLevel, bool IsImportant, string sContactTxD, string sContactTxN);
```

Displays the stats message/icon in the top left of the HUD

## Values for `eIcon`:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Call For Backup |
| 1 | Call A Car |
| 2 | Stamina |
| 3 | Swim Speed |
| 4 | Run Faster |
| 5 | Unburstable Tyres |
| 6 | Jack Faster |
| 7 | Hold Drugs Purse |
| 8 | Kit Ammo |
| 9 | Kit Smoke Grenade |
| 10 | Kit Parachute |
| 11 | Kit Green Smoke |
| 12 | Health Armour Upgrades |
| 13 | Health Health Upgrades |
| 14 | Driving |
| 15 | Driveby |
| 16 | Reliability |
| 17 | Shooting |
| 18 | Hacking |
| 19 | Badcop |
| 20 | Hatecops |
| 21 | Hatevagos |
| 22 | Hatelost |
| 23 | Special Ability Capacity |
| 24 | Lung Capacity |
| 25 | Strength |
| 26 | Bike Skill |
| 27 | Flying Ability |
| 28 | Stealth Ability |
| 29 | Mechanic Ability |


## Parameters
* **sTitleString**: Title of the stats icon.
* **eIcon**: Icon to use ( See ABILITY_ICON enum above )
* **iTotalLevel**: The amount in difference of increasedecrease e.g. -1, 5, -100, 100 Max 100 both ways
* **iCurrentLevel**: Current level value 0-100(%)
* **IsImportant**: T
* **sContactTxD**: Contact, texture dictionary string
* **sContactTxN**: Contact, texture name

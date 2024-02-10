---
ns: HUD
aliases: ["0x2b7e9a4eaaa93c89"]
---
## END_TEXT_COMMAND_THEFEED_POST_STATS

```c
// 0x2B7E9A4EAAA93C89
int END_TEXT_COMMAND_THEFEED_POST_STATS(string sTitleString, int eIcon, int iTotalLevel, int iCurrentLevel, bool IsImportant, string sContactTxD, string sContactTxN);
```

```
Displays the stats message/icon in the top left of the HUD

Possible values for eIcon:
| Index | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Call For Backup |
| 1200 | Call A Car |
| 1201 | Stamina |
| 1202 | Swim Speed |
| 1203 | Run Faster |
| 1204 | Unburstable Tyres |
| 1205 | Jack Faster |
| 1206 | Hold Drugs Purse |
| 1207 | Kit Ammo |
| 1208 | Kit Smoke Grenade |
| 1209 | Kit Parachute |
| 1210 | Kit Green Smoke |
| 1211 | Health Armour Upgrades |
| 1212 | Health Health Upgrades |
| 1213 | Driving |
| 1214 | Driveby |
| 1215 | Reliability |
| 1216 | Shooting |
| 1217 | Hacking |
| 1218 | Badcop |
| 1219 | Hatecops |
| 1220 | Hatevagos |
| 1221 | Hatelost |
| 1222 | Special Ability Capacity |
| 1223 | Lung Capacity |
| 1224 | Strength |
| 1225 | Bike Skill |
| 1226 | Flying Ability |
| 1227 | Stealth Ability |
| 1228 | Mechanic Ability |
```

## Parameters
* **sTitleString**: Title of the stats icon.
* **eIcon**: Icon to use ( See ABILITY_ICON enum above )
* **iTotalLevel**: The amount in difference of increasedecrease e.g. -1, 5, -100, 100 Max 100 both ways
* **iCurrentLevel**: Current level value 0-100(%)
* **IsImportant**: T
* **sContactTxD**: Contact, texture dictionary string
* **sContactTxN**: Contact, texture name

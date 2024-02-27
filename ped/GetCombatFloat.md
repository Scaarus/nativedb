---
ns: PED
aliases: ["0x52dff8a10508090a"]
---
## GET_COMBAT_FLOAT

```c
// 0x52DFF8A10508090A
float GET_COMBAT_FLOAT(Ped ped, int combatAttribute);
```

This function will get the value of any of the enum driven combat float attributes

## Values for `combatAttribute`:
| Value | Name |
| --- | --- |
| 0 | Blind Fire Chance (Chance To Blind Fire From Cover, Range Is 0.0-1.0 (Default Is 0.05 For Civilians, Law Doesn'T Blind Fire)) |
| 1 | Burst Duration In Cover (How Long Each Burst From Cover Should Last (Default Is 2.0)) |
| 3 | Time Between Bursts In Cover (How Long To Wait, In Cover, Between Firing Bursts (< 0.0 Will Disable Firing, Unless Cover Fire Is Requested, Default Is 1.25)) |
| 4 | Time Between Peeks (How Long To Wait Before Attempting To Peek Again (Default Is 10.0)) |
| 5 | Strafe When Moving Chance (A Chance To Strafe To Cover, Range Is 0.0-1.0 (0.0 Will Force Them To Run, 1.0 Will Force Strafe And Shoot, Default Is 1.0)) |
| 6 | Weapon Accuracy (Default Is 0.4) |
| 7 | Fight Proficiency (How Well An Opponent Can Melee Fight, Range Is 0.0-1.0 (Default Is 0.5)) |
| 8 | Walk When Strafing Chance (The Possibility Of A Ped Walking While Strafing Rather Than Jog/Run, Range Is 0.0-1.0 (Default Is 0.0)) |
| 9 | Heli Speed Modifier (The Speed Modifier When Driving A Heli In Combat) |
| 10 | Heli Senses Range (The Range Of The Ped'S Senses (Sight, Identification, Hearing) When In A Heli) |
| 11 | Attack Window Distance For Cover (The Distance We'Ll Use For Cover Based Behaviour In Attack Windows Default Is -1.0 (Disabled), Range Is -1.0 To 150.0) |
| 12 | Time To Invalidate Injured Target (How Long To Stop Combat An Injured Target If There Is No Other Valid Target, If Target Is Player In Singleplayer) |
| 13 | Min Distance To Target (Min Distance The Ped Will Use If Ca Maintain Min Distance To Target Is Set, Default 5.0 (Currently Only For Cover Search + Usage)) |
| 14 | Bullet Impact Detection Range (The Range At Which The Ped Will Detect The Bullet Impact Event) |
| 15 | Aim Turn Threshold (The Threshold At Which The Ped Will Perform An Aim Turn) |
| 16 | Optimal Cover Distance |
| 17 | Automobile Speed Modifier (The Speed Modifier When Driving An Automobile In Combat) |
| 18 | Speed To Flee In Vehicle |
| 19 | Trigger Charge Time Near (How Long To Wait Before Charging A Close Target Hiding In Cover) |
| 20 | Trigger Charge Time Far (How Long To Wait Before Charging A Distant Target Hiding In Cover) |
| 23 | Homing Rocket Break Lock Angle (Angle Between The Rocket And Target Where Lock-On Will Stop, Range Is 0.0-1.0, (Default Is 0.2), The Bigger The Number The Easier To Break Lock) |
| 24 | Homing Rocket Break Lock Angle Close (Angle Between The Rocket And Target Where Lock-On Will Stop, When Rocket Is Within Ccf Homing Rocket Break Lock Close Distance, Range Is 0.0-1.0, (Default Is 0.6), The Bigger The Number The Easier To Break Lock) |
| 25 | Homing Rocket Break Lock Close Distance (Distance At Which We Check Ccf Homing Rocket Break Lock Angle Close Rather Than Ccf Homing Rocket Break Lock Angle) |
| 26 | Homing Rocket Turn Rate Modifier (Alters Homing Characteristics Defined For The Weapon (1.0 Is Default, <1.0 Slow Turn Rates, >1.0 Speed Them Up) |
| 27 | Time Between Aggressive Moves During Vehicle Chase (Sets The Time Delay Between Aggressive Moves During Vehicle Chases. -1.0 Means Use Random Values, 0.0 Means Never) |
| 29 | Weapon Damage Modifier (Multiplies The Weapon Damage Dealt By The Ped, Range Is 0.0-10.0 (Default Is 1.0)) |


See COMBAT_ATTRIBUTE_FLOATS for information on the default values of each combat float


---
ns: OBJECT
aliases: ["0x616093ec6b139dd9"]
---
## SET_PLAYER_PERMITTED_TO_COLLECT_PICKUPS_OF_TYPE

```c
// 0x616093EC6B139DD9
void SET_PLAYER_PERMITTED_TO_COLLECT_PICKUPS_OF_TYPE(int Type, bool Allow);
```

Prohibits/allows a player to collect the specified pickup type

## Values for `Type`:
| Value | Name |
| --- | --- |
| 0 | Health Standard |
| 1 | Armour Standard |
| 2 | Health Snack |
| 3 | Money Variable |
| 4 | Money Case |
| 5 | Money Wallet |
| 6 | Money Purse |
| 7 | Money Dep Bag |
| 8 | Money Med Bag |
| 9 | Money Paper Bag |
| 10 | Money Security Case |
| 11 | Gang Attack Money |
| 12 | Weapon Pistol |
| 13 | Weapon Combatpistol |
| 14 | Weapon Dlc Pistol50 |
| 15 | Weapon Appistol |
| 16 | Weapon Microsmg |
| 17 | Weapon Smg |
| 18 | Weapon Dlc Assaultsmg |
| 19 | Weapon Assaultrifle |
| 20 | Weapon Carbinerifle |
| 21 | Weapon Advancedrifle |
| 22 | Weapon Mg |
| 23 | Weapon Combatmg |
| 24 | Weapon Dlc Assaultmg |
| 25 | Weapon Pumpshotgun |
| 26 | Weapon Sawnoffshotgun |
| 27 | Weapon Dlc Bullpupshotgun |
| 28 | Weapon Assaultshotgun |
| 29 | Weapon Sniperrifle |
| 30 | Weapon Dlc Assaultsniper |
| 31 | Weapon Heavysniper |
| 32 | Weapon Grenadelauncher |
| 33 | Weapon Rpg |
| 34 | Weapon Minigun |
| 35 | Weapon Grenade |
| 36 | Weapon Smokegrenade |
| 37 | Weapon Stickybomb |
| 38 | Weapon Molotov |
| 39 | Weapon Stungun |
| 40 | Weapon Rubbergun |
| 41 | Weapon Dlc Programmablear |
| 42 | Weapon Fireextinguisher |
| 43 | Weapon Petrolcan |
| 44 | Weapon Loudhailer |
| 45 | Weapon Knife |
| 46 | Weapon Nightstick |
| 47 | Weapon Hammer |
| 48 | Weapon Bat |
| 49 | Weapon Crowbar |
| 50 | Weapon Golfclub |
| 51 | Ammo Bullet Mp |
| 52 | Ammo Missile Mp |
| 53 | Ammo Grenadelauncher Mp |
| 54 | Ammo Pistol |
| 55 | Ammo Smg |
| 56 | Ammo Rifle |
| 57 | Ammo Mg |
| 58 | Ammo Shotgun |
| 59 | Ammo Sniper |
| 60 | Ammo Grenadelauncher |
| 61 | Ammo Rpg |
| 62 | Ammo Minigun |
| 63 | Ammo Dlc Rubbergun |
| 64 | Ammo Dlc Harpoon |
| 65 | Ammo Dlc Flaregun |
| 66 | Ammo Dlc Firework |
| 67 | Ammo Dlc Amrifle |
| 68 | Ammo Dlc Crossbow |
| 69 | Ammo Dlc Hominglauncher |
| 70 | Ammo Emplauncher |
| 71 | Vehicle Health Standard |
| 72 | Vehicle Health Standard Low Glow |
| 73 | Vehicle Armour Standard |
| 74 | Vehicle Weapon Pistol |
| 75 | Vehicle Weapon Combatpistol |
| 77 | Vehicle Weapon Appistol |
| 78 | Vehicle Weapon Microsmg |
| 79 | Vehicle Weapon Smg |
| 80 | Vehicle Weapon Sawnoff |
| 81 | Vehicle Weapon Dlc Assaultsmg |
| 82 | Vehicle Weapon Grenade |
| 83 | Vehicle Weapon Smokegrenade |
| 84 | Vehicle Weapon Stickybomb |
| 85 | Vehicle Weapon Molotov |
| 86 | Vehicle Custom Script |
| 87 | Vehicle Custom Script No Rotate |
| 88 | Vehicle Custom Script Low Glow |
| 89 | Vehicle Money Variable |
| 90 | Portable Crate Unfixed |
| 91 | Portable Crate Unfixed Incar |
| 92 | Portable Crate Unfixed Incar Small |
| 93 | Portable Crate Unfixed Incar With Passengers |
| 94 | Portable Crate Unfixed Inairvehicle With Passengers |
| 95 | Portable Crate Unfixed Inairvehicle With Passengers Upright |
| 96 | Portable Crate Fixed Incar With Passengers |
| 97 | Portable Crate Unfixed Low Glow |
| 98 | Portable Crate Fixed Incar |
| 99 | Portable Crate Fixed Incar Small |
| 100 | Portable Package |
| 101 | Portable Dlc Vehicle Package |
| 102 | Portable Package Large Radius |
| 103 | Submarine |
| 104 | Parachute |
| 105 | Custom Script |
| 106 | Handcuff Key |
| 107 | Camera |
| 108 | Weapon Dlc Bottle |
| 109 | Weapon Dlc Specialcarbine |
| 110 | Weapon Dlc Snspistol |
| 111 | Weapon Dlc Bullpuprifle |
| 112 | Weapon Dlc Heavypistol |
| 113 | Weapon Dlc Dagger |
| 114 | Weapon Dlc Vintagepistol |
| 115 | Weapon Dlc Gusenberg |
| 116 | Weapon Dlc Harpoon |
| 117 | Weapon Dlc Flaregun |
| 118 | Weapon Dlc Firework |
| 119 | Weapon Dlc Jetpack |
| 120 | Weapon Dlc Musket |
| 121 | Weapon Dlc Amrifle |
| 122 | Weapon Dlc Crossbow |
| 123 | Type Invalid |
| 124 | Weapon Dlc Heavyshotgun |
| 125 | Weapon Dlc Marksmanrifle |
| 126 | Weapon Dlc Hominglauncher |
| 127 | Weapon Dlc Proxmine |
| 128 | Weapon Dlc Combatpdw |
| 129 | Weapon Dlc Knuckle |
| 130 | Weapon Dlc Marksmanpistol |
| 131 | Weapon Dlc Hatchet |
| 132 | Weapon Dlc Railgun |
| 133 | Weapon Dlc Compactrifle |
| 134 | Weapon Dlc Dbshotgun |
| 135 | Weapon Dlc Machete |
| 136 | Weapon Dlc Machinepistol |
| 137 | Weapon Dlc Flashlight |
| 138 | Weapon Dlc Revolver |
| 139 | Weapon Dlc Switchblade |
| 140 | Weapon Dlc Autoshotgun |
| 141 | Weapon Dlc Battleaxe |
| 142 | Weapon Dlc Compactlauncher |
| 143 | Weapon Dlc Minismg |
| 144 | Weapon Dlc Pipebomb |
| 145 | Weapon Dlc Poolcue |
| 146 | Weapon Dlc Wrench |
| 147 | Weapon Dlc Assaultrifle Mk2 |
| 148 | Weapon Dlc Carbinerifle Mk2 |
| 149 | Weapon Dlc Combatmg Mk2 |
| 150 | Weapon Dlc Heavysniper Mk2 |
| 151 | Weapon Dlc Pistol Mk2 |
| 152 | Weapon Dlc Smg Mk2 |
| 153 | Weapon Dlc Bullpuprifle Mk2 |
| 154 | Weapon Dlc Marksmanrifle Mk2 |
| 155 | Weapon Dlc Pumpshotgun Mk2 |
| 156 | Weapon Dlc Revolver Mk2 |
| 157 | Weapon Dlc Snspistol Mk2 |
| 158 | Weapon Dlc Specialcarbine Mk2 |
| 159 | Weapon Dlc Doubleaction |
| 160 | Weapon Dlc Stone Hatchet |
| 161 | Weapon Dlc Raypistol |
| 162 | Weapon Dlc Raycarbine |
| 163 | Weapon Dlc Rayminigun |
| 164 | Weapon Dlc Ceramicpistol |
| 165 | Weapon Dlc Hazardcan |
| 166 | Weapon Dlc Navyrevolver |
| 167 | Weapon Dlc Gadgetpistol |
| 168 | Weapon Dlc Militaryrifle |
| 169 | Weapon Dlc Combatshotgun |
| 170 | Weapon Dlc Compactsmg |
| 171 | Weapon Dlc Riotsmg |
| 172 | Weapon Dlc Baton |
| 173 | Weapon Dlc Bzgas Mk2 |
| 174 | Weapon Dlc Riotshotgun |
| 175 | Weapon Dlc Flashgrenade |
| 176 | Weapon Dlc Stunguncnc |
| 177 | Weapon Dlc Policerifle |
| 178 | Weapon Dlc Stungrenade |
| 179 | Weapon Dlc Heavyrifle |
| 180 | Weapon Dlc Emplauncher |
| 181 | Weapon Dlc Fertilizercan |
| 182 | Weapon Dlc Stungun Mp |
| 183 | Weapon Dlc Metaldetector |
| 184 | Weapon Dlc Tacticalrifle |
| 185 | Weapon Dlc Precisionrifle |


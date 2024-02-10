---
ns: HUD
aliases: ["0x186e5d252fa50e7d"]
---
## GET_WAYPOINT_BLIP_ENUM_ID

```c
// 0x186E5D252FA50E7D
int GET_WAYPOINT_BLIP_ENUM_ID();
```

## Return Type Values:
| Value | Name |
| --- | --- |
| -1 | RADAR_TRACE_INVALID |
| 0 | RADAR_TRACE_POLICE_PLANE_MOVE |
| 1 | RADAR_TRACE_NUMBERED_1 |
| 2 | RADAR_TRACE_NUMBERED_2 |
| 3 | RADAR_TRACE_NUMBERED_3 |
| 4 | RADAR_TRACE_NUMBERED_4 |
| 5 | RADAR_TRACE_NUMBERED_5 |
| 6 | RADAR_TRACE_NUMBERED_6 |
| 7 | RADAR_TRACE_NUMBERED_7 |
| 8 | RADAR_TRACE_NUMBERED_8 |
| 9 | RADAR_TRACE_NUMBERED_9 |
| 10 | RADAR_TRACE_NUMBERED_10 |
| 11 | RADAR_TRACE_PLACEHOLDER_1 |
| 12 | RADAR_TRACE_PLACEHOLDER_2 |
| 13 | RADAR_TRACE_PLACEHOLDER_3 |
| 14 | RADAR_TRACE_PLACEHOLDER_4 |
| 15 | RADAR_TRACE_POLICE_HELI_SPIN |
| 16 | RADAR_TRACE_PLACEHOLDER_5 |
| 17 | RADAR_TRACE_OBJECTIVE |
| 18 | RADAR_TRACE_JIMMY |
| 19 | RADAR_TRACE_SKI_LIFT |
| 20 | RADAR_TRACE_STATION |
| 21 | RADAR_TRACE_CABLE_CAR |
| 22 | RADAR_TRACE_ACTIVITIES |
| 23 | RADAR_TRACE_RACEFLAG |
| 24 | RADAR_TRACE_FIRE |
| 25 | RADAR_TRACE_SAFEHOUSE |
| 26 | RADAR_TRACE_POLICE |
| 27 | RADAR_TRACE_POLICE_CHASE |
| 28 | RADAR_TRACE_POLICE_HELI |
| 29 | RADAR_TRACE_BOMB_A |
| 30 | RADAR_TRACE_BOMB_B |
| 31 | RADAR_TRACE_BOMB_C |
| 32 | RADAR_TRACE_SNITCH |
| 33 | RADAR_TRACE_PLANNING_LOCATIONS |
| 34 | RADAR_TRACE_CRIM_ARREST |
| 35 | RADAR_TRACE_CRIM_CARSTEAL |
| 36 | RADAR_TRACE_CRIM_DRUGS |
| 37 | RADAR_TRACE_CRIM_HOLDUPS |
| 38 | RADAR_TRACE_CRIM_PIMPING |
| 39 | RADAR_TRACE_CRIM_PLAYER |
| 40 | RADAR_TRACE_FENCE |
| 41 | RADAR_TRACE_COP_PATROL |
| 42 | RADAR_TRACE_COP_PLAYER |
| 43 | RADAR_TRACE_CRIM_WANTED |
| 44 | RADAR_TRACE_HEIST |
| 45 | RADAR_TRACE_POLICE_STATION |
| 46 | RADAR_TRACE_HOSPITAL |
| 47 | RADAR_TRACE_ASSASSINS_MARK |
| 48 | RADAR_TRACE_ELEVATOR |
| 49 | RADAR_TRACE_HELICOPTER |
| 50 | RADAR_TRACE_JOYRIDERS |
| 51 | RADAR_TRACE_RANDOM_CHARACTER |
| 52 | RADAR_TRACE_SECURITY_VAN |
| 53 | RADAR_TRACE_TOW_TRUCK |
| 54 | RADAR_TRACE_DRIVE_THRU |
| 55 | RADAR_TRACE_ILLEGAL_PARKING |
| 56 | RADAR_TRACE_BARBER |
| 57 | RADAR_TRACE_CAR_MOD_SHOP |
| 58 | RADAR_TRACE_CLOTHES_STORE |
| 59 | RADAR_TRACE_GYM |
| 60 | RADAR_TRACE_TATTOO |
| 61 | RADAR_TRACE_ARMENIAN_FAMILY |
| 62 | RADAR_TRACE_LESTER_FAMILY |
| 63 | RADAR_TRACE_MICHAEL_FAMILY |
| 64 | RADAR_TRACE_TREVOR_FAMILY |
| 65 | RADAR_TRACE_JEWELRY_HEIST |
| 66 | RADAR_TRACE_DRAG_RACE |
| 67 | RADAR_TRACE_DRAG_RACE_FINISH |
| 68 | RADAR_TRACE_CAR_CARRIER |
| 69 | RADAR_TRACE_RAMPAGE |
| 70 | RADAR_TRACE_VINEWOOD_TOURS |
| 71 | RADAR_TRACE_LAMAR_FAMILY |
| 72 | RADAR_TRACE_TACO_VAN |
| 73 | RADAR_TRACE_FRANKLIN_FAMILY |
| 74 | RADAR_TRACE_CHINESE_STRAND |
| 75 | RADAR_TRACE_FLIGHT_SCHOOL |
| 76 | RADAR_TRACE_EYE_SKY |
| 77 | RADAR_TRACE_AIR_HOCKEY |
| 78 | RADAR_TRACE_BAR |
| 79 | RADAR_TRACE_BASE_JUMP |
| 80 | RADAR_TRACE_BASKETBALL |
| 81 | RADAR_TRACE_BIOLAB_HEIST |
| 82 | RADAR_TRACE_BOWLING |
| 83 | RADAR_TRACE_BURGER_SHOT |
| 84 | RADAR_TRACE_CABERET_CLUB |
| 85 | RADAR_TRACE_CAR_WASH |
| 86 | RADAR_TRACE_CLUCKIN_BELL |
| 87 | RADAR_TRACE_COMEDY_CLUB |
| 88 | RADAR_TRACE_DARTS |
| 89 | RADAR_TRACE_DOCKS_HEIST |
| 90 | RADAR_TRACE_FBI_HEIST |
| 91 | RADAR_TRACE_FBI_OFFICERS_STRAND |
| 92 | RADAR_TRACE_FINALE_BANK_HEIST |
| 93 | RADAR_TRACE_FINANCIER_STRAND |
| 94 | RADAR_TRACE_GOLF |
| 95 | RADAR_TRACE_GUN_SHOP |
| 96 | RADAR_TRACE_INTERNET_CAFE |
| 97 | RADAR_TRACE_MICHAEL_FAMILY_EXILE |
| 98 | RADAR_TRACE_NICE_HOUSE_HEIST |
| 99 | RADAR_TRACE_RANDOM_FEMALE |
| 100 | RADAR_TRACE_RANDOM_MALE |
| 101 | RADAR_TRACE_REPO |
| 102 | RADAR_TRACE_RESTAURANT |
| 103 | RADAR_TRACE_RURAL_BANK_HEIST |
| 104 | RADAR_TRACE_SHOOTING_RANGE |
| 105 | RADAR_TRACE_SOLOMON_STRAND |
| 106 | RADAR_TRACE_STRIP_CLUB |
| 107 | RADAR_TRACE_TENNIS |
| 108 | RADAR_TRACE_TREVOR_FAMILY_EXILE |
| 109 | RADAR_TRACE_MICHAEL_TREVOR_FAMILY |
| 110 | RADAR_TRACE_VEHICLE_SPAWN |
| 111 | RADAR_TRACE_TRIATHLON |
| 112 | RADAR_TRACE_OFF_ROAD_RACING |
| 113 | RADAR_TRACE_GANG_COPS |
| 114 | RADAR_TRACE_GANG_MEXICANS |
| 115 | RADAR_TRACE_GANG_BIKERS |
| 116 | RADAR_TRACE_GANG_FAMILIES |
| 117 | RADAR_TRACE_GANG_PROFESSIONALS |
| 118 | RADAR_TRACE_SNITCH_RED |
| 119 | RADAR_TRACE_CRIM_CUFF_KEYS |
| 120 | RADAR_TRACE_CINEMA |
| 121 | RADAR_TRACE_MUSIC_VENUE |
| 122 | RADAR_TRACE_POLICE_STATION_BLUE |
| 123 | RADAR_TRACE_AIRPORT |
| 124 | RADAR_TRACE_CRIM_SAVED_VEHICLE |
| 125 | RADAR_TRACE_WEED_STASH |
| 126 | RADAR_TRACE_HUNTING |
| 127 | RADAR_TRACE_POOL |
| 128 | RADAR_TRACE_OBJECTIVE_BLUE |
| 129 | RADAR_TRACE_OBJECTIVE_GREEN |
| 130 | RADAR_TRACE_OBJECTIVE_RED |
| 131 | RADAR_TRACE_OBJECTIVE_YELLOW |
| 132 | RADAR_TRACE_ARMS_DEALING |
| 133 | RADAR_TRACE_MP_FRIEND |
| 134 | RADAR_TRACE_CELEBRITY_THEFT |
| 135 | RADAR_TRACE_WEAPON_ASSAULT_RIFLE |
| 136 | RADAR_TRACE_WEAPON_BAT |
| 137 | RADAR_TRACE_WEAPON_GRENADE |
| 138 | RADAR_TRACE_WEAPON_HEALTH |
| 139 | RADAR_TRACE_WEAPON_KNIFE |
| 140 | RADAR_TRACE_WEAPON_MOLOTOV |
| 141 | RADAR_TRACE_WEAPON_PISTOL |
| 142 | RADAR_TRACE_WEAPON_ROCKET |
| 143 | RADAR_TRACE_WEAPON_SHOTGUN |
| 144 | RADAR_TRACE_WEAPON_SMG |
| 145 | RADAR_TRACE_WEAPON_SNIPER |
| 146 | RADAR_TRACE_MP_NOISE |
| 147 | RADAR_TRACE_POI |
| 148 | RADAR_TRACE_PASSIVE |
| 149 | RADAR_TRACE_USINGMENU |
| 150 | RADAR_TRACE_FRIEND_FRANKLIN_P |
| 151 | RADAR_TRACE_FRIEND_FRANKLIN_X |
| 152 | RADAR_TRACE_FRIEND_MICHAEL_P |
| 153 | RADAR_TRACE_FRIEND_MICHAEL_X |
| 154 | RADAR_TRACE_FRIEND_TREVOR_P |
| 155 | RADAR_TRACE_FRIEND_TREVOR_X |
| 156 | RADAR_TRACE_GANG_COPS_PARTNER |
| 157 | RADAR_TRACE_FRIEND_LAMAR |
| 158 | RADAR_TRACE_WEAPON_MINIGUN |
| 159 | RADAR_TRACE_WEAPON_GRENADELAUNCHER |
| 160 | RADAR_TRACE_WEAPON_ARMOUR |
| 161 | RADAR_TRACE_PROPERTY_TAKEOVER |
| 162 | RADAR_TRACE_GANG_MEXICANS_HIGHLIGHT |
| 163 | RADAR_TRACE_GANG_BIKERS_HIGHLIGHT |
| 164 | RADAR_TRACE_TRIATHLON_CYCLING |
| 165 | RADAR_TRACE_TRIATHLON_SWIMMING |
| 166 | RADAR_TRACE_PROPERTY_TAKEOVER_BIKERS |
| 167 | RADAR_TRACE_PROPERTY_TAKEOVER_COPS |
| 168 | RADAR_TRACE_PROPERTY_TAKEOVER_VAGOS |
| 169 | RADAR_TRACE_CAMERA |
| 170 | RADAR_TRACE_CENTRE_RED |
| 171 | RADAR_TRACE_HANDCUFF_KEYS_BIKERS |
| 172 | RADAR_TRACE_HANDCUFF_KEYS_VAGOS |
| 173 | RADAR_TRACE_HANDCUFFS_CLOSED_BIKERS |
| 174 | RADAR_TRACE_HANDCUFFS_CLOSED_VAGOS |
| 175 | RADAR_TRACE_HANDCUFFS_OPEN_BIKERS |
| 176 | RADAR_TRACE_HANDCUFFS_OPEN_VAGOS |
| 177 | RADAR_TRACE_CAMERA_BADGER |
| 178 | RADAR_TRACE_CAMERA_FACADE |
| 179 | RADAR_TRACE_CAMERA_IFRUIT |
| 180 | RADAR_CRIM_ARREST_BIKERS |
| 181 | RADAR_CRIM_ARREST_VAGOS |
| 182 | RADAR_TRACE_YOGA |
| 183 | RADAR_TRACE_TAXI |
| 184 | RADAR_TRACE_NUMBERED_11 |
| 185 | RADAR_TRACE_NUMBERED_12 |
| 186 | RADAR_TRACE_NUMBERED_13 |
| 187 | RADAR_TRACE_NUMBERED_14 |
| 188 | RADAR_TRACE_NUMBERED_15 |
| 189 | RADAR_TRACE_NUMBERED_16 |
| 190 | RADAR_TRACE_SHRINK |
| 191 | RADAR_TRACE_EPSILON |
| 192 | RADAR_TRACE_FINANCIER_STRAND_GREY |
| 193 | RADAR_TRACE_TREVOR_FAMILY_GREY |
| 194 | RADAR_TRACE_TREVOR_FAMILY_RED |
| 195 | RADAR_TRACE_FRANKLIN_FAMILY_GREY |
| 196 | RADAR_TRACE_FRANKLIN_FAMILY_BLUE |
| 197 | RADAR_TRACE_FRANKLIN_A |
| 198 | RADAR_TRACE_FRANKLIN_B |
| 199 | RADAR_TRACE_FRANKLIN_C |
| 200 | RADAR_TRACE_NUMBERED_RED_1 |
| 201 | RADAR_TRACE_NUMBERED_RED_2 |
| 202 | RADAR_TRACE_NUMBERED_RED_3 |
| 203 | RADAR_TRACE_NUMBERED_RED_4 |
| 204 | RADAR_TRACE_NUMBERED_RED_5 |
| 205 | RADAR_TRACE_NUMBERED_RED_6 |
| 206 | RADAR_TRACE_NUMBERED_RED_7 |
| 207 | RADAR_TRACE_NUMBERED_RED_8 |
| 208 | RADAR_TRACE_NUMBERED_RED_9 |
| 209 | RADAR_TRACE_NUMBERED_RED_10 |
| 210 | RADAR_TRACE_GANG_VEHICLE |
| 211 | RADAR_TRACE_GANG_VEHICLE_BIKERS |
| 212 | RADAR_TRACE_GANG_VEHICLE_COPS |
| 213 | RADAR_TRACE_GANG_VEHICLE_VAGOS |
| 214 | RADAR_TRACE_RADAR_GUNCAR |
| 215 | RADAR_TRACE_DRIVING_BIKERS |
| 216 | RADAR_TRACE_DRIVING_COPS |
| 217 | RADAR_TRACE_DRIVING_VAGOS |
| 218 | RADAR_TRACE_GANG_COPS_HIGHLIGHT |
| 219 | RADAR_TRACE_SHIELD_BIKERS |
| 220 | RADAR_TRACE_SHIELD_COPS |
| 221 | RADAR_TRACE_SHIELD_VAGOS |
| 222 | RADAR_TRACE_CUSTODY_BIKERS |
| 223 | RADAR_TRACE_CUSTODY_VAGOS |
| 224 | RADAR_TRACE_GANG_WANTED_BIKERS |
| 225 | RADAR_TRACE_GANG_WANTED_BIKERS_1 |
| 226 | RADAR_TRACE_GANG_WANTED_BIKERS_2 |
| 227 | RADAR_TRACE_GANG_WANTED_BIKERS_3 |
| 228 | RADAR_TRACE_GANG_WANTED_BIKERS_4 |
| 229 | RADAR_TRACE_GANG_WANTED_BIKERS_5 |
| 230 | RADAR_TRACE_GANG_WANTED_VAGOS |
| 231 | RADAR_TRACE_GANG_WANTED_VAGOS_1 |
| 232 | RADAR_TRACE_GANG_WANTED_VAGOS_2 |
| 233 | RADAR_TRACE_GANG_WANTED_VAGOS_3 |
| 234 | RADAR_TRACE_GANG_WANTED_VAGOS_4 |
| 235 | RADAR_TRACE_GANG_WANTED_VAGOS_5 |
| 236 | RADAR_TRACE_ARMS_DEALING_AIR |
| 237 | RADAR_TRACE_PLAYERSTATE_ARRESTED |
| 238 | RADAR_TRACE_PLAYERSTATE_CUSTODY |
| 239 | RADAR_TRACE_PLAYERSTATE_DRIVING |
| 240 | RADAR_TRACE_PLAYERSTATE_KEYHOLDER |
| 241 | RADAR_TRACE_PLAYERSTATE_PARTNER |
| 242 | RADAR_TRACE_GANG_WANTED_1 |
| 243 | RADAR_TRACE_GANG_WANTED_2 |
| 244 | RADAR_TRACE_GANG_WANTED_3 |
| 245 | RADAR_TRACE_GANG_WANTED_4 |
| 246 | RADAR_TRACE_GANG_WANTED_5 |
| 247 | RADAR_TRACE_ZTYPE |
| 248 | RADAR_TRACE_STINGER |
| 249 | RADAR_TRACE_PACKER |
| 250 | RADAR_TRACE_MONROE |
| 251 | RADAR_TRACE_FAIRGROUND |
| 252 | RADAR_TRACE_PROPERTY |
| 253 | RADAR_TRACE_GANG_HIGHLIGHT |
| 254 | RADAR_TRACE_ALTRUIST |
| 255 | RADAR_TRACE_AI |
| 256 | RADAR_TRACE_ON_MISSION |
| 257 | RADAR_TRACE_CASH_PICKUP |
| 258 | RADAR_TRACE_CHOP |
| 259 | RADAR_TRACE_DEAD |
| 260 | RADAR_TRACE_TERRITORY_LOCKED |
| 261 | RADAR_TRACE_CASH_LOST |
| 262 | RADAR_TRACE_CASH_VAGOS |
| 263 | RADAR_TRACE_CASH_COPS |
| 264 | RADAR_TRACE_HOOKER |
| 265 | RADAR_TRACE_FRIEND |
| 266 | RADAR_TRACE_MISSION_2TO4 |
| 267 | RADAR_TRACE_MISSION_2TO8 |
| 268 | RADAR_TRACE_MISSION_2TO12 |
| 269 | RADAR_TRACE_MISSION_2TO16 |
| 270 | RADAR_TRACE_CUSTODY_DROPOFF |
| 271 | RADAR_TRACE_ONMISSION_COPS |
| 272 | RADAR_TRACE_ONMISSION_LOST |
| 273 | RADAR_TRACE_ONMISSION_VAGOS |
| 274 | RADAR_TRACE_CRIM_CARSTEAL_COPS |
| 275 | RADAR_TRACE_CRIM_CARSTEAL_BIKERS |
| 276 | RADAR_TRACE_CRIM_CARSTEAL_VAGOS |
| 277 | RADAR_TRACE_BAND_STRAND |
| 278 | RADAR_TRACE_SIMEON_FAMILY |
| 279 | RADAR_TRACE_MISSION_1 |
| 280 | RADAR_TRACE_MISSION_2 |
| 281 | RADAR_TRACE_FRIEND_DARTS |
| 282 | RADAR_TRACE_FRIEND_COMEDYCLUB |
| 283 | RADAR_TRACE_FRIEND_CINEMA |
| 284 | RADAR_TRACE_FRIEND_TENNIS |
| 285 | RADAR_TRACE_FRIEND_STRIPCLUB |
| 286 | RADAR_TRACE_FRIEND_LIVEMUSIC |
| 287 | RADAR_TRACE_FRIEND_GOLF |
| 288 | RADAR_TRACE_BOUNTY_HIT |
| 289 | RADAR_TRACE_UGC_MISSION |
| 290 | RADAR_TRACE_HORDE |
| 291 | RADAR_TRACE_CRATEDROP |
| 292 | RADAR_TRACE_PLANE_DROP |
| 293 | RADAR_TRACE_SUB |
| 294 | RADAR_TRACE_RACE |
| 295 | RADAR_TRACE_DEATHMATCH |
| 296 | RADAR_TRACE_ARM_WRESTLING |
| 297 | RADAR_TRACE_MISSION_1TO2 |
| 298 | RADAR_TRACE_SHOOTINGRANGE_GUNSHOP |
| 299 | RADAR_TRACE_RACE_AIR |
| 300 | RADAR_TRACE_RACE_LAND |
| 301 | RADAR_TRACE_RACE_SEA |
| 302 | RADAR_TRACE_TOW |
| 303 | RADAR_TRACE_GARBAGE |
| 304 | RADAR_TRACE_DRILL |
| 305 | RADAR_TRACE_SPIKES |
| 306 | RADAR_TRACE_FIRETRUCK |
| 307 | RADAR_TRACE_MINIGUN2 |
| 308 | RADAR_TRACE_BUGSTAR |
| 309 | RADAR_TRACE_SUBMARINE |
| 310 | RADAR_TRACE_CHINOOK |
| 311 | RADAR_TRACE_GETAWAY_CAR |
| 312 | RADAR_TRACE_MISSION_BIKERS_1 |
| 313 | RADAR_TRACE_MISSION_BIKERS_1TO2 |
| 314 | RADAR_TRACE_MISSION_BIKERS_2 |
| 315 | RADAR_TRACE_MISSION_BIKERS_2TO4 |
| 316 | RADAR_TRACE_MISSION_BIKERS_2TO8 |
| 317 | RADAR_TRACE_MISSION_BIKERS_2TO12 |
| 318 | RADAR_TRACE_MISSION_BIKERS_2TO16 |
| 319 | RADAR_TRACE_MISSION_COPS_1 |
| 320 | RADAR_TRACE_MISSION_COPS_1TO2 |
| 321 | RADAR_TRACE_MISSION_COPS_2 |
| 322 | RADAR_TRACE_MISSION_COPS_2TO4 |
| 323 | RADAR_TRACE_MISSION_COPS_2TO8 |
| 324 | RADAR_TRACE_MISSION_COPS_2TO12 |
| 325 | RADAR_TRACE_MISSION_COPS_2TO16 |
| 326 | RADAR_TRACE_MISSION_VAGOS_1 |
| 327 | RADAR_TRACE_MISSION_VAGOS_1TO2 |
| 328 | RADAR_TRACE_MISSION_VAGOS_2 |
| 329 | RADAR_TRACE_MISSION_VAGOS_2TO4 |
| 330 | RADAR_TRACE_MISSION_VAGOS_2TO8 |
| 331 | RADAR_TRACE_MISSION_VAGOS_2TO12 |
| 332 | RADAR_TRACE_MISSION_VAGOS_2TO16 |
| 333 | RADAR_TRACE_GANG_BIKE |
| 334 | RADAR_TRACE_GAS_GRENADE |
| 335 | RADAR_TRACE_PROPERTY_FOR_SALE |
| 336 | RADAR_TRACE_GANG_ATTACK_PACKAGE |
| 337 | RADAR_TRACE_MARTIN_MADRAZZO |
| 338 | RADAR_TRACE_ENEMY_HELI_SPIN |
| 339 | RADAR_TRACE_BOOST |
| 340 | RADAR_TRACE_DEVIN |
| 341 | RADAR_TRACE_DOCK |
| 342 | RADAR_TRACE_GARAGE |
| 343 | RADAR_TRACE_GOLF_FLAG |
| 344 | RADAR_TRACE_HANGAR |
| 345 | RADAR_TRACE_HELIPAD |
| 346 | RADAR_TRACE_JERRY_CAN |
| 347 | RADAR_TRACE_MASK |
| 348 | RADAR_TRACE_HEIST_PREP |
| 349 | RADAR_TRACE_INCAPACITATED |
| 350 | RADAR_TRACE_SPAWN_POINT_PICKUP |
| 351 | RADAR_TRACE_BOILERSUIT |
| 352 | RADAR_TRACE_COMPLETED |
| 353 | RADAR_TRACE_ROCKETS |
| 354 | RADAR_TRACE_GARAGE_FOR_SALE |
| 355 | RADAR_TRACE_HELIPAD_FOR_SALE |
| 356 | RADAR_TRACE_DOCK_FOR_SALE |
| 357 | RADAR_TRACE_HANGAR_FOR_SALE |
| 358 | RADAR_TRACE_PLACEHOLDER_6 |
| 359 | RADAR_TRACE_BUSINESS |
| 360 | RADAR_TRACE_BUSINESS_FOR_SALE |
| 361 | RADAR_TRACE_RACE_BIKE |
| 362 | RADAR_TRACE_PARACHUTE |
| 363 | RADAR_TRACE_TEAM_DEATHMATCH |
| 364 | RADAR_TRACE_RACE_FOOT |
| 365 | RADAR_TRACE_VEHICLE_DEATHMATCH |
| 366 | RADAR_TRACE_BARRY |
| 367 | RADAR_TRACE_DOM |
| 368 | RADAR_TRACE_MARYANN |
| 369 | RADAR_TRACE_CLETUS |
| 370 | RADAR_TRACE_JOSH |
| 371 | RADAR_TRACE_MINUTE |
| 372 | RADAR_TRACE_OMEGA |
| 373 | RADAR_TRACE_TONYA |
| 374 | RADAR_TRACE_PAPARAZZO |
| 375 | RADAR_TRACE_AIM |
| 376 | RADAR_TRACE_CRATEDROP_BACKGROUND |
| 377 | RADAR_TRACE_GREEN_AND_NET_PLAYER1 |
| 378 | RADAR_TRACE_GREEN_AND_NET_PLAYER2 |
| 379 | RADAR_TRACE_GREEN_AND_NET_PLAYER3 |
| 380 | RADAR_TRACE_GREEN_AND_FRIENDLY |
| 381 | RADAR_TRACE_NET_PLAYER1_AND_NET_PLAYER2 |
| 382 | RADAR_TRACE_NET_PLAYER1_AND_NET_PLAYER3 |
| 383 | RADAR_TRACE_CREATOR |
| 384 | RADAR_TRACE_CREATOR_DIRECTION |
| 385 | RADAR_TRACE_ABIGAIL |
| 386 | RADAR_TRACE_BLIMP |
| 387 | RADAR_TRACE_REPAIR |
| 388 | RADAR_TRACE_TESTOSTERONE |
| 389 | RADAR_TRACE_DINGHY |
| 390 | RADAR_TRACE_FANATIC |
| 391 | RADAR_TRACE_INVISIBLE |
| 392 | RADAR_TRACE_INFO_ICON |
| 393 | RADAR_TRACE_CAPTURE_THE_FLAG |
| 394 | RADAR_TRACE_LAST_TEAM_STANDING |
| 395 | RADAR_TRACE_BOAT |
| 396 | RADAR_TRACE_CAPTURE_THE_FLAG_BASE |
| 397 | RADAR_TRACE_MP_CREW script must not use this! it's for code only! |
| 398 | RADAR_TRACE_CAPTURE_THE_FLAG_OUTLINE script must not use this! it's for code only! |
| 399 | RADAR_TRACE_CAPTURE_THE_FLAG_BASE_NOBAG |
| 400 | RADAR_TRACE_WEAPON_JERRYCAN |
| 401 | RADAR_TRACE_RP |
| 402 | RADAR_TRACE_LEVEL_INSIDE |
| 403 | RADAR_TRACE_BOUNTY_HIT_INSIDE |
| 404 | RADAR_TRACE_CAPTURE_THE_USAFLAG |
| 405 | RADAR_TRACE_CAPTURE_THE_USAFLAG_OUTLINE script must not use this! it's for code only! |
| 406 | RADAR_TRACE_TANK |
| 407 | RADAR_TRACE_PLAYER_HELI |
| 408 | RADAR_TRACE_PLAYER_PLANE |
| 409 | RADAR_TRACE_PLAYER_JET |
| 410 | RADAR_TRACE_CENTRE_STROKE |
| 411 | RADAR_TRACE_PLAYER_GUNCAR |
| 412 | RADAR_TRACE_PLAYER_BOAT |
| 413 | RADAR_TRACE_MP_HEIST |
| 414 | RADAR_TRACE_TEMP_1 |
| 415 | RADAR_TRACE_TEMP_2 |
| 416 | RADAR_TRACE_TEMP_3 |
| 417 | RADAR_TRACE_TEMP_4 |
| 418 | RADAR_TRACE_TEMP_5 |
| 419 | RADAR_TRACE_TEMP_6 |
| 420 | RADAR_TRACE_RACE_STUNT |
| 421 | RADAR_TRACE_HOT_PROPERTY |
| 422 | RADAR_TRACE_URBANWARFARE_VERSUS |
| 423 | RADAR_TRACE_KING_OF_THE_CASTLE |
| 424 | RADAR_TRACE_PLAYER_KING |
| 425 | RADAR_TRACE_DEAD_DROP |
| 426 | RADAR_TRACE_PENNED_IN |
| 427 | RADAR_TRACE_BEAST |
| 428 | RADAR_TRACE_EDGE_POINTER |
| 429 | RADAR_TRACE_EDGE_CROSSTHELINE |
| 430 | RADAR_TRACE_MP_LAMAR |
| 431 | RADAR_TRACE_BENNYS |
| 432 | RADAR_TRACE_CORNER_NUMBER_1 |
| 433 | RADAR_TRACE_CORNER_NUMBER_2 |
| 434 | RADAR_TRACE_CORNER_NUMBER_3 |
| 435 | RADAR_TRACE_CORNER_NUMBER_4 |
| 436 | RADAR_TRACE_CORNER_NUMBER_5 |
| 437 | RADAR_TRACE_CORNER_NUMBER_6 |
| 438 | RADAR_TRACE_CORNER_NUMBER_7 |
| 439 | RADAR_TRACE_CORNER_NUMBER_8 |
| 440 | RADAR_TRACE_YACHT |
| 441 | RADAR_TRACE_FINDERS_KEEPERS |
| 442 | RADAR_TRACE_ASSAULT_PACKAGE |
| 443 | RADAR_TRACE_HUNT_THE_BOSS |
| 444 | RADAR_TRACE_SIGHTSEER |
| 445 | RADAR_TRACE_TURRETED_LIMO |
| 446 | RADAR_TRACE_BELLY_OF_THE_BEAST |
| 447 | RADAR_TRACE_YACHT_LOCATION |
| 448 | RADAR_TRACE_PICKUP_BEAST |
| 449 | RADAR_TRACE_PICKUP_ZONED |
| 450 | RADAR_TRACE_PICKUP_RANDOM |
| 451 | RADAR_TRACE_PICKUP_SLOW_TIME |
| 452 | RADAR_TRACE_PICKUP_SWAP |
| 453 | RADAR_TRACE_PICKUP_THERMAL |
| 454 | RADAR_TRACE_PICKUP_WEED |
| 455 | RADAR_TRACE_WEAPON_RAILGUN |
| 456 | RADAR_TRACE_SEASHARK |
| 457 | RADAR_TRACE_PICKUP_HIDDEN |
| 458 | RADAR_TRACE_WAREHOUSE |
| 459 | RADAR_TRACE_WAREHOUSE_FOR_SALE |
| 460 | RADAR_TRACE_OFFICE |
| 461 | RADAR_TRACE_OFFICE_FOR_SALE |
| 462 | RADAR_TRACE_TRUCK |
| 463 | RADAR_TRACE_CONTRABAND |
| 464 | RADAR_TRACE_TRAILER |
| 465 | RADAR_TRACE_VIP |
| 466 | RADAR_TRACE_CARGOBOB |
| 467 | RADAR_TRACE_AREA_OUTLINE_BLIP |
| 468 | RADAR_TRACE_PICKUP_ACCELERATOR |
| 469 | RADAR_TRACE_PICKUP_GHOST |
| 470 | RADAR_TRACE_PICKUP_DETONATOR |
| 471 | RADAR_TRACE_PICKUP_BOMB |
| 472 | RADAR_TRACE_PICKUP_ARMOURED |
| 473 | RADAR_TRACE_STUNT |
| 474 | RADAR_TRACE_WEAPON_LIVES |
| 475 | RADAR_TRACE_STUNT_PREMIUM |
| 476 | RADAR_TRACE_ADVERSARY |
| 477 | RADAR_TRACE_BIKER_CLUBHOUSE |
| 478 | RADAR_TRACE_BIKER_CAGED_IN |
| 479 | RADAR_TRACE_BIKER_TURF_WAR |
| 480 | RADAR_TRACE_BIKER_JOUST |
| 481 | RADAR_TRACE_PRODUCTION_WEED |
| 482 | RADAR_TRACE_PRODUCTION_CRACK |
| 483 | RADAR_TRACE_PRODUCTION_FAKE_ID |
| 484 | RADAR_TRACE_PRODUCTION_METH |
| 485 | RADAR_TRACE_PRODUCTION_MONEY |
| 486 | RADAR_TRACE_PACKAGE |
| 487 | RADAR_TRACE_CAPTURE_1 |
| 488 | RADAR_TRACE_CAPTURE_2 |
| 489 | RADAR_TRACE_CAPTURE_3 |
| 490 | RADAR_TRACE_CAPTURE_4 |
| 491 | RADAR_TRACE_CAPTURE_5 |
| 492 | RADAR_TRACE_CAPTURE_6 |
| 493 | RADAR_TRACE_CAPTURE_7 |
| 494 | RADAR_TRACE_CAPTURE_8 |
| 495 | RADAR_TRACE_CAPTURE_9 |
| 496 | RADAR_TRACE_CAPTURE_10 |
| 497 | RADAR_TRACE_QUAD |
| 498 | RADAR_TRACE_BUS |
| 499 | RADAR_TRACE_DRUGS_PACKAGE |
| 500 | RADAR_TRACE_PICKUP_JUMP |
| 501 | RADAR_TRACE_ADVERSARY_4 |
| 502 | RADAR_TRACE_ADVERSARY_8 |
| 503 | RADAR_TRACE_ADVERSARY_10 |
| 504 | RADAR_TRACE_ADVERSARY_12 |
| 505 | RADAR_TRACE_ADVERSARY_16 |
| 506 | RADAR_TRACE_LAPTOP |
| 507 | RADAR_TRACE_PICKUP_DEADLINE |
| 508 | RADAR_TRACE_SPORTS_CAR |
| 509 | RADAR_TRACE_WAREHOUSE_VEHICLE |
| 510 | RADAR_TRACE_REG_PAPERS |
| 511 | RADAR_TRACE_POLICE_STATION_DROPOFF |
| 512 | RADAR_TRACE_JUNKYARD |
| 513 | RADAR_TRACE_EX_VECH_1 |
| 514 | RADAR_TRACE_EX_VECH_2 |
| 515 | RADAR_TRACE_EX_VECH_3 |
| 516 | RADAR_TRACE_EX_VECH_4 |
| 517 | RADAR_TRACE_EX_VECH_5 |
| 518 | RADAR_TRACE_EX_VECH_6 |
| 519 | RADAR_TRACE_EX_VECH_7 |
| 520 | RADAR_TRACE_TARGET_A |
| 521 | RADAR_TRACE_TARGET_B |
| 522 | RADAR_TRACE_TARGET_C |
| 523 | RADAR_TRACE_TARGET_D |
| 524 | RADAR_TRACE_TARGET_E |
| 525 | RADAR_TRACE_TARGET_F |
| 526 | RADAR_TRACE_TARGET_G |
| 527 | RADAR_TRACE_TARGET_H |
| 528 | RADAR_TRACE_JUGG |
| 529 | RADAR_TRACE_PICKUP_REPAIR |
| 530 | RADAR_TRACE_STEERINGWHEEL |
| 531 | RADAR_TRACE_TROPHY |
| 532 | RADAR_TRACE_PICKUP_ROCKET_BOOST |
| 533 | RADAR_TRACE_PICKUP_HOMING_ROCKET |
| 534 | RADAR_TRACE_PICKUP_MACHINEGUN |
| 535 | RADAR_TRACE_PICKUP_PARACHUTE |
| 536 | RADAR_TRACE_PICKUP_TIME_5 |
| 537 | RADAR_TRACE_PICKUP_TIME_10 |
| 538 | RADAR_TRACE_PICKUP_TIME_15 |
| 539 | RADAR_TRACE_PICKUP_TIME_20 |
| 540 | RADAR_TRACE_PICKUP_TIME_30 |
| 541 | RADAR_TRACE_SUPPLIES |
| 542 | RADAR_TRACE_PROPERTY_BUNKER |
| 543 | RADAR_TRACE_GR_WVM_1 |
| 544 | RADAR_TRACE_GR_WVM_2 |
| 545 | RADAR_TRACE_GR_WVM_3 |
| 546 | RADAR_TRACE_GR_WVM_4 |
| 547 | RADAR_TRACE_GR_WVM_5 |
| 548 | RADAR_TRACE_GR_WVM_6 |
| 549 | RADAR_TRACE_GR_COVERT_OPS |
| 550 | RADAR_TRACE_ADVERSARY_BUNKER |
| 551 | RADAR_TRACE_GR_MOC_UPGRADE |
| 552 | RADAR_TRACE_GR_W_UPGRADE |
| 553 | RADAR_TRACE_SM_CARGO |
| 554 | RADAR_TRACE_SM_HANGAR |
| 555 | RADAR_TRACE_TF_CHECKPOINT |
| 556 | RADAR_TRACE_RACE_TF |
| 557 | RADAR_TRACE_SM_WP1 |
| 558 | RADAR_TRACE_SM_WP2 |
| 559 | RADAR_TRACE_SM_WP3 |
| 560 | RADAR_TRACE_SM_WP4 |
| 561 | RADAR_TRACE_SM_WP5 |
| 562 | RADAR_TRACE_SM_WP6 |
| 563 | RADAR_TRACE_SM_WP7 |
| 564 | RADAR_TRACE_SM_WP8 |
| 565 | RADAR_TRACE_SM_WP9 |
| 566 | RADAR_TRACE_SM_WP10 |
| 567 | RADAR_TRACE_SM_WP11 |
| 568 | RADAR_TRACE_SM_WP12 |
| 569 | RADAR_TRACE_SM_WP13 |
| 570 | RADAR_TRACE_SM_WP14 |
| 571 | RADAR_TRACE_NHP_BAG |
| 572 | RADAR_TRACE_NHP_CHEST |
| 573 | RADAR_TRACE_NHP_ORBIT |
| 574 | RADAR_TRACE_NHP_VEH1 |
| 575 | RADAR_TRACE_NHP_BASE |
| 576 | RADAR_TRACE_NHP_OVERLAY |
| 577 | RADAR_TRACE_NHP_TURRET |
| 578 | RADAR_TRACE_NHP_MG_FIREWALL |
| 579 | RADAR_TRACE_NHP_MG_NODE |
| 580 | RADAR_TRACE_NHP_WP1 |
| 581 | RADAR_TRACE_NHP_WP2 |
| 582 | RADAR_TRACE_NHP_WP3 |
| 583 | RADAR_TRACE_NHP_WP4 |
| 584 | RADAR_TRACE_NHP_WP5 |
| 585 | RADAR_TRACE_NHP_WP6 |
| 586 | RADAR_TRACE_NHP_WP7 |
| 587 | RADAR_TRACE_NHP_WP8 |
| 588 | RADAR_TRACE_NHP_WP9 |
| 589 | RADAR_TRACE_NHP_CCTV |
| 590 | RADAR_TRACE_NHP_STARTERPACK |
| 591 | RADAR_TRACE_NHP_TURRET_CONSOLE |
| 592 | RADAR_TRACE_NHP_MG_MIR_ROTATE |
| 593 | RADAR_TRACE_NHP_MG_MIR_STATIC |
| 594 | RADAR_TRACE_NHP_MG_PROXY |
| 595 | RADAR_TRACE_ACSR_RACE_TARGET |
| 596 | RADAR_TRACE_ACSR_RACE_HOTRING |
| 597 | RADAR_TRACE_ACSR_WP1 |
| 598 | RADAR_TRACE_ACSR_WP2 |
| 599 | RADAR_TRACE_BAT_CLUB_PROPERTY |
| 600 | RADAR_TRACE_BAT_CARGO |
| 601 | RADAR_TRACE_BAT_TRUCK |
| 602 | RADAR_TRACE_BAT_HACK_JEWEL |
| 603 | RADAR_TRACE_BAT_HACK_GOLD |
| 604 | RADAR_TRACE_BAT_KEYPAD |
| 605 | RADAR_TRACE_BAT_HACK_TARGET |
| 606 | RADAR_TRACE_PICKUP_DTB_HEALTH |
| 607 | RADAR_TRACE_PICKUP_DTB_BLAST_INCREASE |
| 608 | RADAR_TRACE_PICKUP_DTB_BLAST_DECREASE |
| 609 | RADAR_TRACE_PICKUP_DTB_BOMB_INCREASE |
| 610 | RADAR_TRACE_PICKUP_DTB_BOMB_DECREASE |
| 611 | RADAR_TRACE_BAT_RIVAL_CLUB |
| 612 | RADAR_TRACE_BAT_DRONE |
| 613 | RADAR_TRACE_BAT_CASH_REG |
| 614 | RADAR_TRACE_CCTV |
| 615 | RADAR_TRACE_BAT_ASSASSINATE |
| 616 | RADAR_TRACE_BAT_PBUS |
| 617 | RADAR_TRACE_BAT_WP1 |
| 618 | RADAR_TRACE_BAT_WP2 |
| 619 | RADAR_TRACE_BAT_WP3 |
| 620 | RADAR_TRACE_BAT_WP4 |
| 621 | RADAR_TRACE_BAT_WP5 |
| 622 | RADAR_TRACE_BAT_WP6 |
| 623 | RADAR_TRACE_BLIMP_2 |
| 624 | RADAR_TRACE_OPPRESSOR_2 |
| 625 | RADAR_TRACE_BAT_WP7 |
| 626 | RADAR_TRACE_ARENA_SERIES |
| 627 | RADAR_TRACE_ARENA_PREMIUM |
| 628 | RADAR_TRACE_ARENA_WORKSHOP |
| 629 | RADAR_TRACE_RACE_WARS |
| 630 | RADAR_TRACE_ARENA_TURRET |
| 631 | RADAR_TRACE_ARENA_RC_CAR |
| 632 | RADAR_TRACE_ARENA_RC_WORKSHOP |
| 633 | RADAR_TRACE_ARENA_TRAP_FIRE |
| 634 | RADAR_TRACE_ARENA_TRAP_FLIP |
| 635 | RADAR_TRACE_ARENA_TRAP_SEA |
| 636 | RADAR_TRACE_ARENA_TRAP_TURN |
| 637 | RADAR_TRACE_ARENA_TRAP_PIT |
| 638 | RADAR_TRACE_ARENA_TRAP_MINE |
| 639 | RADAR_TRACE_ARENA_TRAP_BOMB |
| 640 | RADAR_TRACE_ARENA_TRAP_WALL |
| 641 | RADAR_TRACE_ARENA_TRAP_BRD |
| 642 | RADAR_TRACE_ARENA_TRAP_SBRD |
| 643 | RADAR_TRACE_ARENA_BRUISER |
| 644 | RADAR_TRACE_ARENA_BRUTUS |
| 645 | RADAR_TRACE_ARENA_CERBERUS |
| 646 | RADAR_TRACE_ARENA_DEATHBIKE |
| 647 | RADAR_TRACE_ARENA_DOMINATOR |
| 648 | RADAR_TRACE_ARENA_IMPALER |
| 649 | RADAR_TRACE_ARENA_IMPERATOR |
| 650 | RADAR_TRACE_ARENA_ISSI |
| 651 | RADAR_TRACE_ARENA_SASQUATCH |
| 652 | RADAR_TRACE_ARENA_SCARAB |
| 653 | RADAR_TRACE_ARENA_SLAMVAN |
| 654 | RADAR_TRACE_ARENA_ZR380 |
| 655 | RADAR_TRACE_AP |
| 656 | RADAR_TRACE_COMIC_STORE |
| 657 | RADAR_TRACE_COP_CAR |
| 658 | RADAR_TRACE_RC_TIME_TRIALS |
| 659 | RADAR_TRACE_KING_OF_THE_HILL |
| 660 | RADAR_TRACE_KING_OF_THE_HILL_TEAMS |
| 661 | RADAR_TRACE_RUCKSACK |
| 662 | RADAR_TRACE_SHIPPING_CONTAINER |
| 663 | RADAR_TRACE_AGATHA |
| 664 | RADAR_TRACE_CASINO |
| 665 | RADAR_TRACE_CASINO_TABLE_GAMES |
| 666 | RADAR_TRACE_CASINO_WHEEL |
| 667 | RADAR_TRACE_CASINO_CONCIERGE |
| 668 | RADAR_TRACE_CASINO_CHIPS |
| 669 | RADAR_TRACE_CASINO_HORSE_RACING |
| 670 | RADAR_TRACE_ADVERSARY_FEATURED |
| 671 | RADAR_TRACE_ROULETTE_1 |
| 672 | RADAR_TRACE_ROULETTE_2 |
| 673 | RADAR_TRACE_ROULETTE_3 |
| 674 | RADAR_TRACE_ROULETTE_4 |
| 675 | RADAR_TRACE_ROULETTE_5 |
| 676 | RADAR_TRACE_ROULETTE_6 |
| 677 | RADAR_TRACE_ROULETTE_7 |
| 678 | RADAR_TRACE_ROULETTE_8 |
| 679 | RADAR_TRACE_ROULETTE_9 |
| 680 | RADAR_TRACE_ROULETTE_10 |
| 681 | RADAR_TRACE_ROULETTE_11 |
| 682 | RADAR_TRACE_ROULETTE_12 |
| 683 | RADAR_TRACE_ROULETTE_13 |
| 684 | RADAR_TRACE_ROULETTE_14 |
| 685 | RADAR_TRACE_ROULETTE_15 |
| 686 | RADAR_TRACE_ROULETTE_16 |
| 687 | RADAR_TRACE_ROULETTE_17 |
| 688 | RADAR_TRACE_ROULETTE_18 |
| 689 | RADAR_TRACE_ROULETTE_19 |
| 690 | RADAR_TRACE_ROULETTE_20 |
| 691 | RADAR_TRACE_ROULETTE_21 |
| 692 | RADAR_TRACE_ROULETTE_22 |
| 693 | RADAR_TRACE_ROULETTE_23 |
| 694 | RADAR_TRACE_ROULETTE_24 |
| 695 | RADAR_TRACE_ROULETTE_25 |
| 696 | RADAR_TRACE_ROULETTE_26 |
| 697 | RADAR_TRACE_ROULETTE_27 |
| 698 | RADAR_TRACE_ROULETTE_28 |
| 699 | RADAR_TRACE_ROULETTE_29 |
| 700 | RADAR_TRACE_ROULETTE_30 |
| 701 | RADAR_TRACE_ROULETTE_31 |
| 702 | RADAR_TRACE_ROULETTE_32 |
| 703 | RADAR_TRACE_ROULETTE_33 |
| 704 | RADAR_TRACE_ROULETTE_34 |
| 705 | RADAR_TRACE_ROULETTE_35 |
| 706 | RADAR_TRACE_ROULETTE_36 |
| 707 | RADAR_TRACE_ROULETTE_0 |
| 708 | RADAR_TRACE_ROULETTE_00 |
| 709 | RADAR_TRACE_LIMO |
| 710 | RADAR_TRACE_WEAPON_ALIEN |
| 711 | RADAR_TRACE_RACE_OPEN_WHEEL |
| 712 | RADAR_TRACE_RAPPEL |
| 713 | RADAR_TRACE_SWAP_CAR |
| 714 | RADAR_TRACE_SCUBA_GEAR |
| 715 | RADAR_TRACE_CPANEL_1 |
| 716 | RADAR_TRACE_CPANEL_2 |
| 717 | RADAR_TRACE_CPANEL_3 |
| 718 | RADAR_TRACE_CPANEL_4 |
| 719 | RADAR_TRACE_SNOW_TRUCK |
| 720 | RADAR_TRACE_BUGGY_1 |
| 721 | RADAR_TRACE_BUGGY_2 |
| 722 | RADAR_TRACE_ZHABA |
| 723 | RADAR_TRACE_GERALD |
| 724 | RADAR_TRACE_RON |
| 725 | RADAR_TRACE_ARCADE |
| 726 | RADAR_TRACE_DRONE_CONTROLS |
| 727 | RADAR_TRACE_RC_TANK |
| 728 | RADAR_TRACE_STAIRS |
| 729 | RADAR_TRACE_CAMERA_2 |
| 730 | RADAR_TRACE_WINKY |
| 731 | RADAR_TRACE_MINI_SUB |
| 732 | RADAR_TRACE_KART_RETRO |
| 733 | RADAR_TRACE_KART_MODERN |
| 734 | RADAR_TRACE_MILITARY_QUAD |
| 735 | RADAR_TRACE_MILITARY_TRUCK |
| 736 | RADAR_TRACE_SHIP_WHEEL |
| 737 | RADAR_TRACE_UFO |
| 738 | RADAR_TRACE_SEASPARROW2 |
| 739 | RADAR_TRACE_DINGHY2 |
| 740 | RADAR_TRACE_PATROL_BOAT |
| 741 | RADAR_TRACE_RETRO_SPORTS_CAR |
| 742 | RADAR_TRACE_SQUADEE |
| 743 | RADAR_TRACE_FOLDING_WING_JET |
| 744 | RADAR_TRACE_VALYKRIE2 |
| 745 | RADAR_TRACE_SUB2 |
| 746 | RADAR_TRACE_BOLT_CUTTERS |
| 747 | RADAR_TRACE_RAPPEL_GEAR |
| 748 | RADAR_TRACE_KEYCARD |
| 749 | RADAR_TRACE_PASSWORD |
| 750 | RADAR_TRACE_ISLAND_HEIST_PREP |
| 751 | RADAR_TRACE_ISLAND_PARTY |
| 752 | RADAR_TRACE_CONTROL_TOWER |
| 753 | RADAR_TRACE_UNDERWATER_GATE |
| 754 | RADAR_TRACE_POWER_SWITCH |
| 755 | RADAR_TRACE_COMPOUND_GATE |
| 756 | RADAR_TRACE_RAPPEL_POINT |
| 757 | RADAR_TRACE_KEYPAD |
| 758 | RADAR_TRACE_SUB_CONTROLS |
| 759 | RADAR_TRACE_SUB_PERISCOPE |
| 760 | RADAR_TRACE_SUB_MISSILE |
| 761 | RADAR_TRACE_PAINTING |
| 762 | RADAR_TRACE_CAR_MEET |
| 763 | RADAR_TRACE_CAR_TEST_AREA |
| 764 | RADAR_TRACE_AUTO_SHOP_PROPERTY |
| 765 | RADAR_TRACE_DOCKS_EXPORT |
| 766 | RADAR_TRACE_PRIZE_CAR |
| 767 | RADAR_TRACE_TEST_CAR |
| 768 | RADAR_TRACE_CAR_ROBBERY_BOARD |
| 769 | RADAR_TRACE_CAR_ROBBERY_PREP |
| 770 | RADAR_TRACE_STREET_RACE_SERIES |
| 771 | RADAR_TRACE_PURSUIT_SERIES |
| 772 | RADAR_TRACE_CAR_MEET_ORGANISER |
| 773 | RADAR_TRACE_SECUROSERV |
| 774 | RADAR_TRACE_BOUNTY_COLLECTIBLES |
| 775 | RADAR_TRACE_MOVIE_COLLECTIBLES |
| 776 | RADAR_TRACE_TRAILER_RAMP |
| 777 | RADAR_TRACE_RACE_ORGANISER |
| 778 | RADAR_TRACE_CHALKBOARD_LIST |
| 779 | RADAR_TRACE_EXPORT_VEHICLE |
| 780 | RADAR_TRACE_TRAIN |
| 781 | RADAR_TRACE_HEIST_DIAMOND |
| 782 | RADAR_TRACE_HEIST_DOOMSDAY |
| 783 | RADAR_TRACE_HEIST_ISLAND |
| 784 | RADAR_TRACE_SLAMVAN2 |
| 785 | RADAR_TRACE_CRUSADER |
| 786 | RADAR_TRACE_CONSTRUCTION_OUTFIT |
| 787 | RADAR_TRACE_OVERLAY_JAMMED |
| 788 | RADAR_TRACE_HEIST_ISLAND_UNAVAILABLE |
| 789 | RADAR_TRACE_HEIST_DIAMOND_UNAVAILABLE |
| 790 | RADAR_TRACE_HEIST_DOOMSDAY_UNAVAILABLE |
| 791 | RADAR_TRACE_HSW_RACE_SERIES |
| 792 | RADAR_TRACE_HSW_TIME_TRIAL |
| 793 | RADAR_TRACE_HSW_TEST_VEHICLE |
| 794 | RADAR_TRACE_FEATURED_SERIES |
| 795 | RADAR_TRACE_VEHICLE_FOR_SALE |
| 796 | RADAR_TRACE_VAN_KEYS |
| 797 | RADAR_TRACE_SUV_SERVICE |
| 798 | RADAR_TRACE_SECURITY_CONTRACT |
| 799 | RADAR_TRACE_SAFE |
| 800 | RADAR_TRACE_PED_R |
| 801 | RADAR_TRACE_PED_E |
| 802 | RADAR_TRACE_PAYPHONE |
| 803 | RADAR_TRACE_PATRIOT3 |
| 804 | RADAR_TRACE_MUSIC_STUDIO |
| 805 | RADAR_TRACE_JUBILEE |
| 806 | RADAR_TRACE_GRANGER2 |
| 807 | RADAR_TRACE_EXPLOSIVE_CHARGE |
| 808 | RADAR_TRACE_DEITY |
| 809 | RADAR_TRACE_D_CHAMPION |
| 810 | RADAR_TRACE_BUFFALO_4 |
| 811 | RADAR_TRACE_AGENCY |
| 812 | RADAR_TRACE_BIKER_BAR |
| 813 | RADAR_TRACE_SIMEON_OVERLAY |
| 814 | RADAR_TRACE_JUNK_SKYDIVE |
| 815 | RADAR_TRACE_LUXURY_CAR_SHOWROOM |
| 816 | RADAR_TRACE_CAR_SHOWROOM |
| 817 | RADAR_TRACE_CAR_SHOWROOM_SIMEON |
| 818 | RADAR_TRACE_FLAMING_SKULL |
| 819 | RADAR_TRACE_WEAPON_AMMO |
| 820 | RADAR_TRACE_COMMUNITY_SERIES |
| 821 | RADAR_TRACE_CAYO_SERIES |
| 822 | RADAR_TRACE_CLUBHOUSE_CONTRACT |
| 823 | RADAR_TRACE_AGENT_ULP |
| 824 | RADAR_TRACE_ACID |
| 825 | RADAR_TRACE_ACID_LAB |
| 826 | RADAR_TRACE_DAX_OVERLAY |
| 827 | RADAR_TRACE_DEAD_DROP_PACKAGE |
| 828 | RADAR_TRACE_DOWNTOWN_CAB |
| 829 | RADAR_TRACE_GUN_VAN |
| 830 | RADAR_TRACE_STASH_HOUSE |
| 831 | RADAR_TRACE_TRACTOR |
| 832 | RADAR_TRACE_WAREHOUSE_JUGGALO |
| 833 | RADAR_TRACE_WAREHOUSE_JUGGALO_DAX |
| 834 | MAX_RADAR_TRACES |


returns an id to pass to blip commands of the code "waypoint" blip

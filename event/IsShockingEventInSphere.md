---
ns: EVENT
aliases: ["0x1374abb7c15bab92"]
---
## IS_SHOCKING_EVENT_IN_SPHERE

```c
// 0x1374ABB7C15BAB92
bool IS_SHOCKING_EVENT_IN_SPHERE(int eventType, Vector3 pos, float radius);
```

Checks if a shocking event of the given type is in the given sphere. Returns TRUE if found, FALSE otherwise.

## Values for `eventType`:
| Value | Name |
| --- | --- |
| -1 | Invalid |
| 0 | Acquaintance Ped Dislike |
| 1 | Acquaintance Ped Hate |
| 2 | Acquaintance Ped Like |
| 3 | Acquaintance Ped Respect |
| 4 | Acquaintance Ped Wanted |
| 5 | Acquaintance Ped Dead |
| 6 | Agitated |
| 7 | Agitated Action |
| 8 | Encroaching Ped |
| 9 | Call For Cover |
| 10 | Car Undriveable |
| 11 | Climb Ladder On Route |
| 12 | Climb Navmesh On Route |
| 13 | Combat Taunt |
| 14 | Communicate Event |
| 15 | Cop Car Being Stolen |
| 16 | Crime Reported |
| 17 | Damage |
| 18 | Dead Ped Found |
| 19 | Death |
| 20 | Dragged Out Car |
| 21 | Dummy Conversion |
| 22 | Explosion |
| 23 | Explosion Heard |
| 24 | Fire Nearby |
| 25 | Flush Tasks |
| 26 | Foot Step Heard |
| 27 | Get Out Of Water |
| 28 | Give Ped Task |
| 29 | Gun Aimed At |
| 30 | Help Ambient Friend |
| 31 | Injured Cry For Help |
| 32 | Crime Cry For Help |
| 33 | In Air |
| 34 | In Water |
| 35 | Incapacitated |
| 36 | Leader Entered Car As Driver |
| 37 | Leader Entered Cover |
| 38 | Leader Exited Car As Driver |
| 39 | Leader Holstered Weapon |
| 40 | Leader Left Cover |
| 41 | Leader Unholstered Weapon |
| 42 | Melee Action |
| 43 | Must Leave Boat |
| 44 | New Task |
| 45 | None |
| 46 | Object Collision |
| 47 | On Fire |
| 48 | Open Door |
| 49 | Shove Ped |
| 50 | Ped Collision With Ped |
| 51 | Ped Collision With Player |
| 52 | Ped Entered My Vehicle |
| 53 | Ped Jacking My Vehicle |
| 54 | Ped On Car Roof |
| 55 | Ped To Chase |
| 56 | Ped To Flee |
| 57 | Player Collision With Ped |
| 58 | Player Lock On Target |
| 59 | Potential Be Walked Into |
| 60 | Potential Blast |
| 61 | Potential Get Run Over |
| 62 | Potential Walk Into Fire |
| 63 | Potential Walk Into Object |
| 64 | Potential Walk Into Vehicle |
| 65 | Providing Cover |
| 66 | Radio Target Position |
| 67 | Ran Over Ped |
| 68 | Reaction Combat Victory |
| 69 | Reaction Enemy Ped |
| 70 | Reaction Investigate Dead Ped |
| 71 | Reaction Investigate Threat |
| 72 | Request Help With Confrontation |
| 73 | Responded To Threat |
| 74 | Revived |
| 75 | Script Command |
| 76 | Shocking Broken Glass |
| 77 | Shocking Car Alarm |
| 78 | Shocking Car Chase |
| 79 | Shocking Car Crash |
| 80 | Shocking Bicycle Crash |
| 81 | Shocking Car Pile Up |
| 82 | Shocking Car On Car |
| 83 | Shocking Dangerous Animal |
| 84 | Shocking Dead Body |
| 85 | Shocking Driving On Pavement |
| 86 | Shocking Bicycle On Pavement |
| 87 | Shocking Engine Revved |
| 88 | Shocking Explosion |
| 89 | Shocking Fire |
| 90 | Shocking Gun Fight |
| 91 | Shocking Gunshot Fired |
| 92 | Shocking Helicopter Overhead |
| 93 | Shocking Parachuter Overhead |
| 94 | Shocking Ped Knocked Into By Player |
| 95 | Shocking Horn Sounded |
| 96 | Shocking In Dangerous Vehicle |
| 97 | Shocking Injured Ped |
| 98 | Shocking Mad Driver |
| 99 | Shocking Mad Driver Extreme |
| 100 | Shocking Mad Driver Bicycle |
| 101 | Shocking Mugging |
| 102 | Shocking Non Violent Weapon Aimed At |
| 103 | Shocking Ped Run Over |
| 104 | Shocking Ped Shot |
| 105 | Shocking Plane Fly By |
| 106 | Shocking Potential Blast |
| 107 | Shocking Property Damage |
| 108 | Shocking Running Ped |
| 109 | Shocking Running Stampede |
| 110 | Shocking Seen Car Stolen |
| 111 | Shocking Seen Confrontation |
| 112 | Shocking Seen Gang Fight |
| 113 | Shocking Seen Insult |
| 114 | Shocking Seen Melee Action |
| 115 | Shocking Seen Nice Car |
| 116 | Shocking Seen Ped Killed |
| 117 | Shocking Seen Vehicle Towed |
| 118 | Shocking Seen Weapon Threat |
| 119 | Shocking Seen Weird Ped |
| 120 | Shocking Seen Weird Ped Approaching |
| 121 | Shocking Siren |
| 122 | Shocking Studio Bomb |
| 123 | Shocking Visible Weapon |
| 124 | Shot Fired |
| 125 | Shot Fired Bullet Impact |
| 126 | Shot Fired Whizzed By |
| 127 | Friendly Aimed At |
| 128 | Shot Friendly Near Miss |
| 129 | Shout Blocking Los |
| 130 | Shout Target Position |
| 131 | Static Count Reached Max |
| 132 | Stuck In Air |
| 133 | Suspicious Activity |
| 134 | Switch 2 Nm Task |
| 135 | Unidentified Ped |
| 136 | Vehicle Collision |
| 137 | Vehicle Damage Weapon |
| 138 | Vehicle On Fire |
| 139 | Whistling Heard |
| 140 | Disturbance |
| 141 | Entity Damaged |
| 142 | Entity Destroyed |
| 143 | Writhe |
| 144 | Hurt Transition |
| 145 | Player Unable To Enter Vehicle |
| 146 | Scenario Force Action |
| 147 | Stat Value Changed |
| 148 | Player Death |
| 149 | Ped Seen Dead Ped |
| 151 | Network Player Join Session |
| 152 | Network Player Left Session |
| 153 | Network Player Join Script |
| 154 | Network Player Left Script |
| 155 | Network Store Player Left |
| 156 | Network Session Start |
| 157 | Network Session End |
| 158 | Network Start Match |
| 159 | Network End Match |
| 160 | Network Removed From Session Due To Stall |
| 161 | Network Removed From Session Due To Complaints |
| 162 | Network Connection Timeout |
| 163 | Network Ped Dropped Weapon |
| 164 | Network Player Spawn |
| 165 | Network Player Collected Pickup |
| 166 | Network Player Collected Ambient Pickup |
| 167 | Network Player Collected Portable Pickup |
| 168 | Network Player Dropped Portable Pickup |
| 169 | Network Invite Arrived |
| 170 | Network Invite Accepted |
| 171 | Network Invite Confirmed |
| 172 | Network Invite Rejected |
| 173 | Network Summon |
| 174 | Network Script Event |
| 175 | Network Player Signed Offline |
| 176 | Network Sign In State Changed |
| 177 | Network Sign In Change Actioned |
| 178 | Network Network Ros Changed |
| 179 | Network Network Bail |
| 180 | Network Host Migration |
| 181 | Network Find Session |
| 182 | Network Host Session |
| 183 | Network Join Session |
| 184 | Network Join Session Response |
| 185 | Network Cheat Triggered |
| 186 | Network Damage Entity |
| 187 | Network Player Arrest |
| 188 | Network Timed Explosion |
| 189 | Network Primary Clan Changed |
| 190 | Network Clan Joined |
| 191 | Network Clan Left |
| 192 | Network Clan Invite Received |
| 193 | Voice Session Started |
| 194 | Voice Session Ended |
| 195 | Voice Connection Requested |
| 196 | Voice Connection Response |
| 197 | Voice Connection Terminated |
| 198 | Text Message Received |
| 199 | Cloud File Response |
| 200 | Network Pickup Respawned |
| 201 | Network Presence Stat Update |
| 202 | Network Ped Left Behind |
| 203 | Network Inbox Msgs Rcvd |
| 204 | Network Attempt Host Migration |
| 205 | Network Increment Stat |
| 206 | Network Session Event |
| 207 | Network Transition Started |
| 208 | Network Transition Event |
| 209 | Network Transition Member Joined |
| 210 | Network Transition Member Left |
| 211 | Network Transition Parameter Changed |
| 212 | Network Clan Kicked |
| 213 | Network Transition String Changed |
| 214 | Network Transition Gamer Instruction |
| 215 | Network Presence Invite |
| 216 | Network Presence Invite Removed |
| 217 | Network Presence Invite Reply |
| 218 | Network Cash Transaction Log |
| 219 | Network Clan Rank Change |
| 220 | Network Vehicle Undrivable |
| 221 | Network Presence Trigger |
| 222 | Network Email Received |
| 223 | Network Follow Invite Received |
| 224 | Network Admin Invited |
| 225 | Network Spectate Local |
| 226 | Network Cloud Event |
| 227 | Network Shop Transaction |
| 228 | Network Permission Check Result |
| 229 | Network App Launched |
| 230 | Network Online Permissions Updated |
| 231 | Network System Service Event |
| 232 | Network Request Delay |
| 233 | Network Social Club Account Linked |
| 234 | Network Scadmin Player Updated |
| 235 | Network Scadmin Received Cash |
| 236 | Network Clan Invite Request Received |
| 237 | Network Marketing Email Received |
| 238 | Network Stunt Performed |
| 239 | Network Fired Dummy Projectile |
| 240 | Network Player Entered Vehicle |
| 241 | Network Player Activated Special Ability |
| 242 | Network Player Deactivated Special Ability |
| 243 | Network Player Special Ability Failed Activation |
| 244 | Network Fired Vehicle Projectile |
| 245 | Network Sc Membership Status |
| 246 | Network Sc Benefits Status |
| 248 | Errors Unknown Errors |
| 249 | Errors Array Overflow |
| 250 | Errors Instruction Limit |
| 251 | Errors Stack Overflow |


eventType must be one of the EVENT_SHOCKING_... events.


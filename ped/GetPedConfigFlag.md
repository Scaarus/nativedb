---
ns: PED
aliases: ["0x7ee53118c892b513"]
---
## GET_PED_CONFIG_FLAG

```c
// 0x7EE53118C892B513
bool GET_PED_CONFIG_FLAG(Ped ped, int ConfigFlag, bool DoDeadCheck);
```

Gets the given ped config flag bit

## ConfigFlag Values:
| Value | Name |
| --- | --- |
| 0 | Created By Factory |
| 1 | Can Be Shot In Vehicle |
| 2 | No Critical Hits |
| 3 | Drowns In Water |
| 4 | Drowns In Sinking Vehicle |
| 5 | Dies Instantly When Swimming |
| 6 | Has Bullet Proof Vest |
| 7 | Upper Body Damage Anims Only |
| 8 | Never Fall Off Skis |
| 9 | Never Ever Target This Ped |
| 10 | This Ped Is Atarget Priority |
| 11 | Targettable With No Los |
| 12 | Doesnt Listen To Player Group Commands |
| 13 | Never Leaves Group |
| 14 | Doesnt Drop Weapons When Dead |
| 15 | Set Delayed Weapon As Current |
| 16 | Keep Tasks After Clean Up |
| 17 | Block Non Temporary Events |
| 18 | Has Ascript Brain |
| 19 | Waiting For Script Brain To Load |
| 20 | Allow Medics To Revive Me |
| 21 | Money Has Been Given By Script |
| 22 | Not Allowed To Crouch |
| 23 | Death Pickups Persist |
| 24 | Ignore Seen Melee |
| 25 | Force Die If Injured |
| 26 | Dont Drag Me Out Car |
| 27 | Stay In Car On Jack |
| 28 | Force Die In Car |
| 29 | Get Out Undriveable Vehicle |
| 30 | Will Remain On Boat After Mission Ends |
| 31 | Dont Store As Persistent |
| 32 | Will Fly Through Windscreen |
| 33 | Die When Ragdoll |
| 34 | Has Helmet |
| 35 | Use Helmet |
| 36 | Dont Take Off Helmet |
| 37 | Hide In Cutscene |
| 38 | Ped Is Enemy To Player |
| 39 | Disable Evasive Dives |
| 40 | Ped Generates Dead Body Events |
| 41 | Dont Attack Player Without Wanted Level |
| 42 | Dont Influence Wanted Level |
| 43 | Disable Player Lockon |
| 44 | Disable Lockon To Random Peds |
| 45 | Allow Lockon To Friendly Players |
| 46 | Disable Horn Audio When Dead |
| 47 | Ped Being Deleted |
| 48 | Block Weapon Switching |
| 49 | Block Group Ped Aimed At Response |
| 50 | Will Follow Leader Any Means |
| 51 | Blipped By Script |
| 52 | Draw Radar Visual Field |
| 53 | Stop Weapon Firing On Impact |
| 54 | Dissable Auto Fall Off Tests |
| 55 | Steer Around Dead Bodies |
| 56 | Constrain To Nav Mesh |
| 57 | Syncing Animated Props |
| 58 | Is Firing |
| 59 | Was Firing |
| 60 | Is Standing |
| 61 | Was Standing |
| 62 | In Vehicle |
| 63 | On Mount |
| 64 | Attached To Vehicle |
| 65 | Is Swimming |
| 66 | Was Swimming |
| 67 | Is Skiing |
| 68 | Is Sitting |
| 69 | Killed By Stealth |
| 70 | Killed By Takedown |
| 71 | Knockedout |
| 72 | Clear Radar Blip On Death |
| 73 | Just Got Off Train |
| 74 | Just Got On Train |
| 75 | Using Cover Point |
| 76 | Is In The Air |
| 77 | Knocked Up Into Air |
| 78 | Is Aiming Gun |
| 79 | Has Just Left Car |
| 80 | Target When Injured Allowed |
| 81 | Curr Left Foot Coll Nm |
| 82 | Prev Left Foot Coll Nm |
| 83 | Curr Right Foot Coll Nm |
| 84 | Prev Right Foot Coll Nm |
| 85 | Has Been Bumped In Car |
| 86 | In Water Task Quit To Climb Ladder |
| 87 | Nmtwo Handed Weapon Both Hands Constrained |
| 88 | Created Blood Pool Timer |
| 89 | Dont Activate Ragdoll From Any Ped Impact |
| 90 | Group Ped Failed To Enter Cover |
| 91 | Already Chatted On Phone |
| 92 | Already Reacted To Ped On Roof |
| 93 | Force Ped Load Cover |
| 94 | Block Cowering In Cover |
| 95 | Block Peeking In Cover |
| 96 | Just Left Car Not Checked For Doors |
| 97 | Vault From Cover |
| 98 | Auto Conversation Look Ats |
| 99 | Using Crouched Ped Capsule |
| 100 | Has Dead Ped Been Reported |
| 101 | Forced Aim |
| 102 | Steers Around Peds |
| 103 | Steers Around Objects |
| 104 | Open Door Arm Ik |
| 105 | Force Reload |
| 106 | Dont Activate Ragdoll From Vehicle Impact |
| 107 | Dont Activate Ragdoll From Bullet Impact |
| 108 | Dont Activate Ragdoll From Explosions |
| 109 | Dont Activate Ragdoll From Fire |
| 110 | Dont Activate Ragdoll From Electrocution |
| 111 | Is Being Dragged To Safety |
| 112 | Has Been Dragged To Safety |
| 113 | Keep Weapon Holstered Unless Fired |
| 114 | Force Script Controlled Knockout |
| 115 | Fall Out Of Vehicle When Killed |
| 116 | Get Out Burning Vehicle |
| 117 | Bumped By Player |
| 118 | Run From Fires And Explosions |
| 119 | Treat As Player During Targeting |
| 120 | Is Hand Cuffed |
| 121 | Is Ankle Cuffed |
| 122 | Disable Melee |
| 123 | Disable Unarmed Drivebys |
| 124 | Just Gets Pulled Out When Electrocuted |
| 125 | Unused Replace Me |
| 126 | Will Not Hotwire Law Enforcement Vehicle |
| 127 | Will Commandeer Rather Than Jack |
| 128 | Can Be Agitated |
| 129 | Force Ped To Face Left In Cover |
| 130 | Force Ped To Face Right In Cover |
| 131 | Block Ped From Turning In Cover |
| 132 | Keep Relationship Group After Clean Up |
| 133 | Force Ped To Be Dragged |
| 134 | Prevent Ped From Reacting To Being Jacked |
| 135 | Is Scuba |
| 136 | Will Arrest Rather Than Jack |
| 137 | Remove Dead Extra Far Away |
| 138 | Riding Train |
| 139 | Arrest Result |
| 140 | Can Attack Friendly |
| 141 | Will Jack Any Player |
| 142 | Bumped By Player Vehicle |
| 143 | Dodged Player Vehicle |
| 144 | Will Jack Wanted Players Rather Than Steal Car |
| 145 | No Cop Wanted Aggro |
| 146 | Disable Ladder Climbing |
| 147 | Stairs Detected |
| 148 | Slope Detected |
| 149 | Helmet Has Been Shot |
| 150 | Cower Instead Of Flee |
| 151 | Can Activate Ragdoll When Vehicle Upside Down |
| 152 | Always Respond To Cries For Help |
| 153 | Disable Blood Pool Creation |
| 154 | Should Fix If No Collision |
| 155 | Can Perform Arrest |
| 156 | Can Perform Uncuff |
| 157 | Can Be Arrested |
| 158 | Mover Constricted By Opposing Collisions |
| 159 | Player Prefer Front Seat Mp |
| 160 | Dont Activate Ragdoll From Impact Object |
| 161 | Dont Activate Ragdoll From Melee |
| 162 | Dont Activate Ragdoll From Water Jet |
| 163 | Dont Activate Ragdoll From Drowning |
| 164 | Dont Activate Ragdoll From Falling |
| 165 | Dont Activate Ragdoll From Rubber Bullet |
| 166 | Is Injured |
| 167 | Dont Enter Vehicles In Players Group |
| 168 | Swimming Tasks Running |
| 169 | Prevent All Melee Taunts |
| 170 | Force Direct Entry |
| 171 | Always See Approaching Vehicles |
| 172 | Can Dive Away From Approaching Vehicles |
| 173 | Allow Player To Interrupt Vehicle Entry Exit |
| 174 | Only Attack Law If Player Is Wanted |
| 175 | Player In Contact With Kinematic Ped |
| 176 | Player In Contact With Something Other Than Kinematic Ped |
| 177 | Peds Jacking Me Dont Get In |
| 178 | Additional Rappelling Ped |
| 179 | Ped Ignores Anim Interrupt Events |
| 180 | Is In Custody |
| 181 | Force Standard Bump Reaction Thresholds |
| 182 | Law Will Only Attack If Player Is Wanted |
| 183 | Is Agitated |
| 184 | Prevent Auto Shuffle To Drivers Seat |
| 185 | Use Kinematic Mode When Stationary |
| 186 | Enable Weapon Blocking |
| 187 | Has Hurt Started |
| 188 | Disable Hurt |
| 189 | Player Is Weird |
| 190 | Ped Had Phone Conversation |
| 191 | Began Crossing Road |
| 192 | Warp Into Leaders Vehicle |
| 193 | Do Nothing When On Foot By Default |
| 194 | Using Scenario |
| 195 | Visible On Screen |
| 196 | Dont Collide With Kinematic |
| 197 | Activate On Switch From Low Physics Lod |
| 198 | Dont Activate Ragdoll On Ped Collision When Dead |
| 199 | Dont Activate Ragdoll On Vehicle Collision When Dead |
| 200 | Has Been In Armed Combat |
| 201 | Use Diminishing Ammo Rate |
| 202 | Avoidance Ignore All |
| 203 | Avoidance Ignored By All |
| 204 | Avoidance Ignore Group1 |
| 205 | Avoidance Member Of Group1 |
| 206 | Forced To Use Specific Group Seat Index |
| 207 | Low Physics Lod May Place On Nav Mesh |
| 208 | Disable Explosion Reactions |
| 209 | Dodged Player |
| 210 | Waiting For Player Control Interrupt |
| 211 | Forced To Stay In Cover |
| 212 | Generates Sound Events |
| 213 | Listens To Sound Events |
| 214 | Allow To Be Targeted In Avehicle |
| 215 | Wait For Direct Entry Point To Be Free When Exiting |
| 216 | Only Require One Press To Exit Vehicle |
| 217 | Force Exit To Sky Dive |
| 218 | Steers Around Vehicles |
| 219 | Allow Ped In Vehicles Override Task Flags |
| 220 | Dont Enter Leaders Vehicle |
| 221 | Disable Exit To Sky Dive |
| 222 | Script Has Disabled Collision |
| 223 | Use Ambient Model Scaling |
| 224 | Dont Watch First On Next Hurry Away |
| 225 | Disable Potential To Be Walked Into Response |
| 226 | Disable Ped Avoidance |
| 227 | Force Ragdoll Upon Death |
| 228 | Can Lose Props On Damage |
| 229 | Disable Panic In Vehicle |
| 230 | Allowed To Detach Trailer |
| 231 | Has Shot Been Reacted To From Front |
| 232 | Has Shot Been Reacted To From Back |
| 233 | Has Shot Been Reacted To From Left |
| 234 | Has Shot Been Reacted To From Right |
| 235 | Allow Block Dead Ped Ragdoll Activation |
| 236 | Is Holding Prop |
| 237 | Blocks Pathing When Dead |
| 238 | Force Play Normal Scenario Exit On Next Script Command |
| 239 | Force Play Immediate Scenario Exit On Next Script Command |
| 240 | Force Skin Character Cloth |
| 241 | Leave Engine On When Exiting Vehicles |
| 242 | Phone Disable Texting Animations |
| 243 | Phone Disable Talking Animations |
| 244 | Phone Disable Camera Animations |
| 245 | Disable Blind Firing In Shot Reactions |
| 246 | Allow Nearby Cover Usage |
| 247 | In Strafe Transition |
| 248 | Can Play In Car Idles |
| 249 | Can Attack Non Wanted Player As Law |
| 250 | Will Take Damage When Vehicle Crashes |
| 251 | Aican Drive Player As Rear Passenger |
| 252 | Player Can Jack Friendly Players |
| 253 | On Stairs |
| 254 | Simulating Aiming |
| 255 | Aidriver Allow Friendly Passenger Seat Entry |
| 256 | Parent Car Is Being Removed |
| 257 | Allow Mission Ped To Use Injured Movement |
| 258 | Can Lose Helmet On Damage |
| 259 | Never Do Scenario Exit Probe Checks |
| 260 | Suppress Low Lodragdoll Switch When Corpse Settles |
| 261 | Prevent Using Lower Priority Seats |
| 262 | Just Left Vehicle Needs Reset |
| 263 | Teleport If Cant Reach Player |
| 264 | Peds In Vehicle Position Needs Reset |
| 265 | Peds Fully In Seat |
| 266 | Allow Player Lock On If Friendly |
| 267 | Use Camera Heading For Desired Direction Lock On Test |
| 268 | Teleport To Leader Vehicle |
| 269 | Avoidance Ignore Weird Ped Buffer |
| 270 | On Stair Slope |
| 271 | Has Played Nmgetup |
| 272 | Dont Blip Cop |
| 273 | Spawned At Extended Range Scenario |
| 274 | Walk Alongside Leader When Close |
| 275 | Kill When Trapped |
| 276 | Edge Detected |
| 277 | Always Wake Up Physics Of Intersected Peds |
| 278 | Equipped Ambient Load Out Weapon |
| 279 | Avoid Tear Gas |
| 280 | Stopped Speech Upon Freezing |
| 281 | Disable Go To Writhe When Injured |
| 282 | Only Use Forced Seat When Entering Heli In Group |
| 283 | Thrown From Vehicle Due To Exhaustion |
| 284 | Update Enclosed Search Region |
| 285 | Disable Weird Ped Events |
| 286 | Should Charge Now |
| 287 | Ragdolling On Boat |
| 288 | Has Brandished Weapon |
| 289 | Allow Minor Reactions As Mission Ped |
| 290 | Block Dead Body Shocking Events When Dead |
| 291 | Ped Has Been Seen |
| 292 | Ped Is In Reuse Pool |
| 293 | Ped Was Reused |
| 294 | Disable Shocking Events |
| 295 | Moved Using Low Lod Physics Since Last Active |
| 296 | Never React To Ped On Roof |
| 297 | Force Play Flee Scenario Exit On Next Script Command |
| 298 | Just Bumped Into Vehicle |
| 299 | Disable Shocking Driving On Pavement Events |
| 300 | Should Throw Smoke Now |
| 301 | Disable Ped Constraints |
| 302 | Force Initial Peek In Cover |
| 303 | Created By Dispatch |
| 304 | Point Gun Left Hand Supporting |
| 305 | Disable Jumping From Vehicles After Leader |
| 306 | Dont Activate Ragdoll From Player Ped Impact |
| 307 | Dont Activate Ragdoll From Ai Ragdoll Impact |
| 308 | Dont Activate Ragdoll From Player Ragdoll Impact |
| 309 | Disable Quadruped Spring |
| 310 | Is In Cluster |
| 311 | Shout To Group On Player Melee |
| 312 | Ignored By Auto Open Doors |
| 313 | Prefer Injured Getup |
| 314 | Force Ignore Melee Active Combatant |
| 315 | Check Lo Sfor Sound Events |
| 316 | Jacked Abandoned Car |
| 317 | Can Say Followed By Player Audio |
| 318 | Activate Ragdoll From Minor Player Contact |
| 319 | Has Portable Pickup Attached |
| 320 | Force Pose Character Cloth |
| 321 | Has Cloth Collision Bounds |
| 322 | Has High Heels |
| 323 | Treat As Ambient Ped For Driver Lock On |
| 324 | Dont Behave Like Law |
| 325 | Spawned At Scenario |
| 326 | Disable Police Investigating Body |
| 327 | Disable Writhe Shoot From Ground |
| 328 | Lower Priority Of Warp Seats |
| 329 | Disable Talk To |
| 330 | Dont Blip |
| 331 | Is Switching Weapon |
| 332 | Ignore Leg Ik Restrictions |
| 333 | Script Force No Timeslice Intelligence Update |
| 334 | Jacked Out Of My Vehicle |
| 335 | Went Into Combat After Being Jacked |
| 336 | Dont Activate Ragdoll For Vehicle Grab |
| 337 | Force Package Character Cloth |
| 338 | Dont Remove With Valid Order |
| 339 | Allow Task Do Nothing Timeslicing |
| 340 | Forced To Stay In Cover Due To Player Switch |
| 341 | Force Prone Character Cloth |
| 342 | Not Allowed To Jack Any Players |
| 343 | In To Strafe Transition |
| 344 | Killed By Standard Melee |
| 345 | Always Leave Train Upon Arrival |
| 346 | Force Play Directed Normal Scenario Exit On Next Script Command |
| 347 | Only Writhe From Weapon Damage |
| 348 | Use Slo Mo Blood Vfx |
| 349 | Equip Jetpack |
| 350 | Prevent Dragged Out Of Car Threat Response |
| 351 | Script Has Completely Disabled Collision |
| 352 | Never Do Scenario Nav Checks |
| 353 | Force Synchronous Scenario Exit Checking |
| 354 | Throwing Grenade While Aiming |
| 355 | Headbob To Radio Enabled |
| 356 | Force Deep Surface Check |
| 357 | Disable Deep Surface Anims |
| 358 | Dont Blip Not Synced |
| 359 | Is Ducking In Vehicle |
| 360 | Prevent Auto Shuffle To Turret Seat |
| 361 | Disable Event Interior Status Check |
| 362 | Has Reserve Parachute |
| 363 | Use Reserve Parachute |
| 364 | Treat Dislike As Hate When In Combat |
| 365 | Only Update Target Wanted If Seen |
| 366 | Allow Auto Shuffle To Drivers Seat |
| 367 | Dont Activate Ragdoll From Smoke Grenade |
| 368 | Link Mbrto Owner On Chain |
| 369 | Ambient Friend Bumped By Player |
| 370 | Ambient Friend Bumped By Player Vehicle |
| 371 | In Fpsunholster Transition |
| 372 | Prevent Reacting To Silenced Clone Bullets |
| 373 | Disable Injured Cry For Help Events |
| 374 | Never Leave Train |
| 375 | Dont Drop Jetpack On Death |
| 376 | Use Fpsunholster Transition During Combat Roll |
| 377 | Exiting Fpscombat Roll |
| 378 | Script Has Control Of Player |
| 379 | Play Fpsidle Fidgets For Projectile |
| 380 | Disable Auto Equip Helmets In Bikes |
| 381 | Disable Auto Equip Helmets In Aircraft |
| 382 | Was Playing Fpsgetup |
| 383 | Was Playing Fpsmelee Action Result |
| 384 | Prefer No Priority Removal |
| 385 | Fpsfidgets Aborted On Fire |
| 386 | Force Fpsikwith Upper Body Anim |
| 387 | Switching Characters In First Person |
| 388 | Is Climbing Ladder |
| 389 | Has Bare Feet |
| 390 | Unused Replace Me 2 |
| 391 | Go On Without Vehicle If It Is Unable To Get Back To Road |
| 392 | Block Dropping Health Snacks On Death |
| 393 | Reset Last Vehicle On Vehicle Exit |
| 394 | Force Threat Response To Non Friend To Friend Melee Actions |
| 395 | Dont Respond To Random Peds Damage |
| 396 | Allow Continuous Threat Response Wanted Level Updates |
| 397 | Keep Target Loss Response On Cleanup |
| 398 | Players Dont Drag Me Out Of Car |
| 399 | Broadcast Reponded To Threat When Going To Point Shooting |
| 400 | Ignore Ped Type For Is Friendly With |
| 401 | Treat Non Friendly As Hate When In Combat |
| 402 | Dont Leave Vehicle If Leader Not In Vehicle |
| 403 | Change From Permanent To Ambient Pop Type On Migration |
| 404 | Allow Melee Reaction If Melee Proof Is On |
| 405 | Using Lowrider Leans |
| 406 | Using Alternate Lowrider Leans |
| 407 | Use Normal Explosion Damage When Blown Up In Vehicle |
| 408 | Disable Homing Missile Lock For Vehicle Ped Inside |
| 409 | Disable Take Off Scuba Gear |
| 410 | Ignore Melee Fist Weapon Damage Mult |
| 411 | Law Peds Can Flee From Non Wanted Player |
| 412 | Force Blip Security Peds If Player Is Wanted |
| 413 | Is Holstering Weapon |
| 414 | Use Go To Point For Scenario Navigation |
| 415 | Dont Clear Local Passengers Wanted Level |
| 416 | Block Auto Swap On Weapon Pickups |
| 417 | This Ped Is Atarget Priority For Ai |
| 418 | Is Switching Helmet Visor |
| 419 | Force Helmet Visor Switch |
| 420 | Is Performing Vehicle Melee |
| 421 | Use Override Footstep Pt Fx |
| 422 | Disable Vehicle Combat |
| 423 | Treat As Friendly For Targeting And Damage |
| 424 | Allow Bike Alternate Animations |
| 425 | Treat As Friendly For Targeting And Damage Non Synced |
| 426 | Use Lockpick Vehicle Entry Animations |
| 427 | Ignore Interior Check For Sprinting |
| 428 | Swat Heli Spawn Within Last Spotted Location |
| 429 | Disable Start Engine |
| 430 | Ignore Being On Fire |
| 431 | Disable Turret Or Rear Seat Preference |
| 432 | Disable Wanted Helicopter Spawning |
| 433 | Use Target Perception For Creating Aimed At Events |
| 434 | Disable Homing Missile Lockon |
| 435 | Force Ignore Max Melee Active Support Combatants |
| 436 | Stay In Defensive Area When In Vehicle |
| 437 | Dont Shout Target Position |
| 438 | Disable Helmet Armor |
| 439 | Created By Concealed Player |
| 440 | Permanently Disable Potential To Be Walked Into Response |
| 441 | Prevent Veh Exit Due To Invalid Weapon |
| 442 | Ignore Net Session Friendly Fire Check For Allow Damage |
| 443 | Dont Leave Combat If Target Player Is Attacked By Police |
| 444 | Check Locked Before Warp |
| 445 | Dont Shuffle In Vehicle To Make Room |
| 446 | Give Weapon On Getup |
| 447 | Dont Hit Vehicle With Projectiles |
| 448 | Disable Forced Entry For Open Vehicles From Try Locked Door |
| 449 | Fires Dummy Rockets |
| 450 | Ped Is Arresting |
| 451 | Is Decoy Ped |
| 452 | Has Established Decoy |
| 453 | Block Dispatched Helicopters From Landing |
| 454 | Dont Cry For Help On Stun |
| 455 | Hit By Tranq Weapon |
| 456 | Can Be Incapacitated |
| 457 | Forced Aim From Arrest |
| 458 | Dont Change Target From Melee |
| 459 | Disable Health Regeneration When Stunned |
| 460 | Ragdoll Floats Indefinitely |
| 461 | Block Electric Weapon Damage |


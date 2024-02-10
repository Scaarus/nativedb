---
ns: PED
aliases: ["0x418ef2a1bce56685"]
---
## CREATE_NM_MESSAGE

```c
// 0x418EF2A1BCE56685
void CREATE_NM_MESSAGE(int StartParam, int MessageType);
```

Create a Natural motion message.

## StartParam Values:
| Value | Name |
| --- | --- |
| -1 | Update |
| 0 | Stop |
| 1 | Start |


## MessageType Values:
| Value | Name |
| --- | --- |
| 0 | Stop All Msg |
| 1 | Stop All Fb Feedback Message, Must Be Next One After The Original Message, Must Have One Per Message |
| 2 | Start |
| 3 | Active Pose Msg |
| 4 | Active Pose Fb |
| 5 | Active Pose Mask |
| 6 | Active Pose Use Grav Compensation |
| 7 | Active Pose Anim Source |
| 8 | Applyimpulse Msg |
| 9 | Applyimpulse Fb |
| 10 | Applyimpulse Equalize Amount |
| 11 | Applyimpulse Part Index |
| 12 | Applyimpulse Impulse |
| 13 | Applyimpulse Hit Point |
| 14 | Applyimpulse Local Hit Point Info |
| 15 | Applyimpulse Local Impulse Info |
| 16 | Applyimpulse Angular Impulse |
| 17 | Applybulletimp Msg |
| 18 | Applybulletimp Fb |
| 19 | Applybulletimp Equalize Amount |
| 20 | Applybulletimp Part Index |
| 21 | Applybulletimp Impulse |
| 22 | Applybulletimp Hit Point |
| 23 | Applybulletimp Local Hit Point Info |
| 24 | Buoyancy Msg |
| 25 | Buoyancy Fb |
| 26 | Buoyancy Surfacepoint |
| 27 | Buoyancy Surfacenormal |
| 28 | Buoyancy Buoyancy |
| 29 | Buoyancy Chestbuoyancy |
| 30 | Buoyancy Damping |
| 31 | Buoyancy Righting |
| 32 | Buoyancy Rightingstrength |
| 33 | Buoyancy Rightingtime |
| 34 | Relax Msg |
| 35 | Relax Fb |
| 36 | Relax Relaxation |
| 37 | Relax Damping |
| 38 | Relax Mask |
| 39 | Relax Hold Pose |
| 40 | Carried Msg |
| 41 | Carried Fb |
| 42 | Configure Balance Msg |
| 43 | Configure Balance Fb |
| 44 | Configure Balance Step Height |
| 45 | Configure Balance Step Int 4 Step |
| 46 | Configure Balance Legs Apart Restep |
| 47 | Configure Balance Legs Together Restep |
| 48 | Configure Balance Legs Apart Max |
| 49 | Configure Balance Taper Knee Strength |
| 50 | Configure Balance Leg Stiffness |
| 51 | Configure Balance Left Leg Swing Damping |
| 52 | Configure Balance Right Leg Swing Damping |
| 53 | Configure Balance Oppose Gravity Legs |
| 54 | Configure Balance Oppose Gravity Ankles |
| 55 | Configure Balance Lean Acc |
| 56 | Configure Balance Hip Lean Acc |
| 57 | Configure Balance Lean Acc Max |
| 58 | Configure Balance Resist Acc |
| 59 | Configure Balance Resist Acc Max |
| 60 | Configure Balance Foot Slip Comp On Mov Floor |
| 61 | Configure Balance Ankle Equilibrium |
| 62 | Configure Balance Extra Feet Apart |
| 63 | Configure Balance Dont Step Time |
| 64 | Configure Balance Abort Threshold |
| 65 | Configure Balance Give Up Height |
| 66 | Configure Balance Step Clamp Scale |
| 67 | Configure Balance Step Clamp Scale Variance |
| 68 | Configure Balance Prediction Time Hip |
| 69 | Configure Balance Prediction Time |
| 70 | Configure Balance Prediction Time Variance |
| 72 | Configure Balance Fall Type |
| 73 | Configure Balance Fall Mult |
| 74 | Configure Balance Fall Reduce Gravity Comp |
| 76 | Configure Balance Stable Lin Speed Thresh |
| 77 | Configure Balance Stable Rot Speed Thresh |
| 78 | Configure Balance Fail Must Collide |
| 79 | Configure Balance Ignore Failure |
| 80 | Configure Balance Stable Change Step Time |
| 81 | Configure Balance Balance Indefinitely |
| 82 | Configure Balance Ramp Hip Pitch On Fail |
| 83 | Configure Balance Moving Floor |
| 84 | Configure Balance Airborne Step |
| 85 | Configure Balance Use Com Dir Turn Vel Thresh |
| 86 | Configure Balance Min Knee Angle |
| 87 | Configure Balance Flatter Swing Feet |
| 88 | Configure Balance Flatter Static Feet |
| 89 | Configure Balance Lean Against Velocity |
| 90 | Configure Balance Step Decision Threshold |
| 91 | Configure Balance Step If In Support |
| 92 | Configure Balance Always Step With Farthest |
| 93 | Configure Balance Stand Up |
| 94 | Configure Balance Depth Fudge |
| 95 | Configure Balance Depth Fudge Stagger |
| 96 | Configure Balance Foot Friction |
| 97 | Configure Balance Foot Friction Stagger |
| 98 | Configure Balance Give Up Height End |
| 99 | Configure Balance Abort Thresh |
| 100 | Configure Balance Give Up Ramp Dur |
| 101 | Configure Balance Lean To Abort |
| 102 | Configure Balance Reset Msg |
| 103 | Configure Balance Reset Fb |
| 104 | Configurebullets Msg |
| 105 | Configurebullets Fb |
| 106 | Configurebullets Imp Spread Over Parts |
| 107 | Configurebullets Imp Leak Strength Scaled |
| 108 | Configurebullets Imp Period |
| 109 | Configurebullets Imp Torque Scale |
| 110 | Configurebullets Looseness Fix |
| 111 | Configurebullets Imp Delay |
| 112 | Configurebullets Imp Reduct Per Shot |
| 113 | Configurebullets Imp Recovery |
| 114 | Configurebullets Imp Min Leakage |
| 115 | Configurebullets Torque Mode |
| 116 | Configurebullets Torque Spin Mode |
| 117 | Configurebullets Torque Filter Mode |
| 118 | Configurebullets Torque Always Spine3 |
| 119 | Configurebullets Torque Del |
| 120 | Configurebullets Torque Period |
| 121 | Configurebullets Torque Gain |
| 122 | Configurebullets Torque Cutoff |
| 123 | Configurebullets Torque Reduct Per Tick |
| 124 | Configurebullets Lift Gain |
| 125 | Configurebullets Counter Imp Del |
| 126 | Configurebullets Counter Imp Mag |
| 127 | Configurebullets Counter After Mag Reached |
| 128 | Configurebullets Do Counter Imp |
| 129 | Configurebullets Counter Imp2Hips |
| 130 | Configurebullets Imp Air Mult |
| 131 | Configurebullets Imp Air Mult Start |
| 132 | Configurebullets Imp Air Max |
| 133 | Configurebullets Imp Air Apply Above |
| 134 | Configurebullets Imp Air On |
| 135 | Configurebullets Imp One Leg Mult |
| 136 | Configurebullets Imp One Leg Mult Start |
| 137 | Configurebullets Imp One Leg Max |
| 138 | Configurebullets Imp One Leg Apply Above |
| 139 | Configurebullets Imp One Leg On |
| 140 | Configurebullets Rb Ratio |
| 141 | Configurebullets Rb Lower Share |
| 142 | Configurebullets Rb Moment |
| 145 | Configurebullets Rb Ratio Airborne |
| 146 | Configurebullets Rb Moment Airborne |
| 149 | Configurebullets Rb Ratio One Leg |
| 150 | Configurebullets Rb Moment One Leg |
| 153 | Configurebullets Rb Twist Axis |
| 154 | Configurebullets Rb Pivot |
| 155 | Configshotinjuredarm Msg |
| 156 | Configshotinjuredarm Fb |
| 157 | Configshotinjuredarm Injured Arm Time |
| 158 | Configshotinjuredarm Hipyaw |
| 159 | Configshotinjuredarm Hiproll |
| 160 | Configshotinjuredarm Force Step Extra Height |
| 161 | Configshotinjuredarm Shrug Time |
| 162 | Configshotinjuredarm Force Step |
| 163 | Configshotinjuredarm Step Turn |
| 164 | Configshotinjuredarm Vel Mult Start |
| 165 | Configshotinjuredarm Vel Mult End |
| 166 | Configshotinjuredarm Vel Force Step |
| 167 | Configshotinjuredarm Vel Step Turn |
| 168 | Configshotinjuredarm Vel Scales |
| 169 | Configshotinjuredleg Msg |
| 170 | Configshotinjuredleg Fb |
| 171 | Configshotinjuredleg Time Before Collapse Wound Leg |
| 172 | Configshotinjuredleg Leg Injury Time |
| 173 | Configshotinjuredleg Leg Force Step |
| 174 | Configshotinjuredleg Leg Limp Bend |
| 175 | Configshotinjuredleg Leg Lift Time |
| 176 | Configshotinjuredleg Leg Injury |
| 177 | Configshotinjuredleg Leg Injury Hip Pitch |
| 178 | Configshotinjuredleg Leg Injury Lift Hip Pitch |
| 179 | Configshotinjuredleg Leg Injury Spine Bend |
| 180 | Configshotinjuredleg Leg Injury Lift Spine Bend |
| 181 | Dangle Msg |
| 182 | Dangle Fb |
| 183 | Dangle Do Grab |
| 184 | Dangle Grab Frequency |
| 185 | Define Attached Obj Msg |
| 186 | Define Attached Obj Fb |
| 187 | Define Attached Obj Part Index |
| 188 | Define Attached Obj Mass |
| 189 | Define Attached Obj Pos Vec3 |
| 190 | Forcetobodypart Msg |
| 191 | Forcetobodypart Fb |
| 192 | Forcetobodypart Part Index |
| 193 | Forcetobodypart Force |
| 194 | Forcetobodypart Force In Part Space |
| 195 | Balance Lean Dir Msg |
| 196 | Balance Lean Dir Fb |
| 197 | Balance Lean Dir Amount |
| 198 | Balance Lean Dir Vec3 |
| 199 | Balance Lean Random Msg |
| 200 | Balance Lean Random Fb |
| 201 | Balance Lean Amount Min |
| 202 | Balance Lean Amount Max |
| 203 | Balance Lean Change Time Min |
| 204 | Balance Lean Change Time Max |
| 205 | Balance Lean Pos Msg |
| 206 | Balance Lean Pos Fb |
| 207 | Balance Lean Pos Amount |
| 208 | Balance Lean Pos Vec3 |
| 209 | Balance Lean To Obj Msg |
| 210 | Balance Lean To Obj Fb |
| 211 | Balance Lean To Obj Amount |
| 212 | Balance Lean To Obj Offset Vec3 |
| 213 | Balance Lean To Obj Instance Index |
| 214 | Balance Lean To Obj Bound Index |
| 215 | Hipsleandir Msg |
| 216 | Hipsleandir Fb |
| 217 | Hipsleandir Lean Amount |
| 218 | Hipsleandir Dir |
| 219 | Hipsleanrandom Msg |
| 220 | Hipsleanrandom Fb |
| 221 | Hipsleanrandom Lean Amount Min |
| 222 | Hipsleanrandom Lean Amount Max |
| 223 | Hipsleanrandom Change Time Min |
| 224 | Hipsleanrandom Change Time Max |
| 225 | Hipsleanpos Msg |
| 226 | Hipsleanpos Fb |
| 227 | Hipsleanpos Lean Amount |
| 228 | Hipsleanpos Pos |
| 229 | Hipsleanobj Msg |
| 230 | Hipsleanobj Fb |
| 231 | Hipsleanobj Lean Amount |
| 232 | Hipsleanobj Offset |
| 233 | Hipsleanobj Instance Index |
| 234 | Hipsleanobj Bound Index |
| 235 | Forceleandir Msg |
| 236 | Forceleandir Fb |
| 237 | Forceleandir Lean Amount |
| 238 | Forceleandir Dir |
| 239 | Forceleandir Body Part |
| 240 | Forceleanrandom Msg |
| 241 | Forceleanrandom Fb |
| 242 | Forceleanrandom Lean Amount Min |
| 243 | Forceleanrandom Lean Amount Max |
| 244 | Forceleanrandom Change Time Min |
| 245 | Forceleanrandom Change Time Max |
| 246 | Forceleanrandom Part |
| 247 | Forceleanpos Msg |
| 248 | Forceleanpos Fb |
| 249 | Forceleanpos Lean Amount |
| 250 | Forceleanpos Pos |
| 251 | Forceleanpos Part |
| 252 | Forceleanobj Msg |
| 253 | Forceleanobj Fb |
| 254 | Forceleanobj Lean Amount |
| 255 | Forceleanobj Offset |
| 256 | Forceleanobj Instance Index |
| 257 | Forceleanobj Bound Index |
| 258 | Forceleanobj Part |
| 259 | Set Stiffness Msg |
| 260 | Set Stiffness Fb |
| 261 | Set Stiffness Stiffness |
| 262 | Set Stiffness Damping |
| 263 | Set Stiffness Mask |
| 264 | Setmusclestiffness Msg |
| 265 | Setmusclestiffness Fb |
| 266 | Setmusclestiffness Stiffness |
| 267 | Setmusclestiffness Mask |
| 268 | Setweaponmode Msg |
| 269 | Setweaponmode Fb |
| 270 | Setweaponmode Mode |
| 271 | Shot Relax Msg |
| 272 | Shot Relax Fb |
| 273 | Shot Relax Period Upper |
| 274 | Shot Relax Period Lower |
| 275 | Fireweapon Msg |
| 276 | Fireweapon Fb |
| 277 | Fireweapon Weapon Strength |
| 278 | Fireweapon Gun Hand Enum |
| 279 | Fireweapon Apply Force At Clav |
| 280 | Fireweapon Inhibit Time |
| 281 | Fireweapon Dir |
| 282 | Fireweapon Split |
| 283 | Configure Constraints Msg |
| 284 | Configure Constraints Fb |
| 285 | Configure Constraints Hand Cuffs |
| 286 | Configure Constraints Hand Cuffs Behind Back |
| 287 | Configure Constraints Leg Cuffs |
| 288 | Configure Constraints Right Dominant |
| 289 | Configure Constraints Passive Mode |
| 290 | Configure Constraints Bespoke Behavior |
| 291 | Configure Constraints Blend 2 Zero Pose |
| 292 | Stayupright Msg |
| 293 | Stayupright Fb |
| 294 | Stayupright Use Forces |
| 295 | Stayupright Use Torques |
| 296 | Stayupright Last Stand Mode |
| 297 | Stayupright Last Stand Sink Rate |
| 298 | Stayupright Last Stand Horiz Damping |
| 300 | Stayupright Turn Toward Bullets |
| 301 | Stayupright Vel Based |
| 302 | Stayupright Torque Only In Air |
| 303 | Stayupright Force Strength |
| 304 | Stayupright Force Damping |
| 305 | Stayupright Force Feet Mult |
| 306 | Stayupright Spine3 Share |
| 307 | Stayupright Force Lean Reduct |
| 308 | Stayupright Force In Air Share |
| 309 | Stayupright Force Min |
| 310 | Stayupright Force Max |
| 311 | Stayupright Force Sat Vel |
| 312 | Stayupright Force Thresh Vel |
| 313 | Stayupright Torque Strength |
| 314 | Stayupright Torque Damping |
| 315 | Stayupright Torque Sat Vel |
| 316 | Stayupright Torque Thresh Vel |
| 317 | Stayupright Support Pos |
| 318 | Stayupright No Support Force Mult |
| 319 | Stayupright Step Up Help |
| 320 | Stayupright Stay Up Acc |
| 321 | Stayupright Stay Up Acc Max |
| 322 | Setcharacterstrength Msg |
| 323 | Setcharacterstrength Fb |
| 324 | Setcharacterstrength Strength |
| 325 | Set Falling Reaction Msg |
| 326 | Set Falling Reaction Fb |
| 327 | Set Falling Reaction Hands And Knees |
| 328 | Set Falling Reaction Call Rds |
| 329 | Set Falling Reaction Com Vel Rds Thresh |
| 330 | Set Falling Reaction Resist Rolling |
| 331 | Set Falling Reaction Arm Reduce Speed |
| 332 | Set Falling Reaction Reach Length Multiplier |
| 333 | Set Falling Reaction Inhibit Rolling Time |
| 334 | Set Falling Reaction Change Fritcion Time |
| 335 | Set Falling Reaction Ground Friction |
| 336 | Anim Pose Msg |
| 337 | Anim Pose Fb |
| 338 | Anim Pose Muscle Stiffness |
| 339 | Anim Pose Stiffness |
| 340 | Anim Pose Damping |
| 341 | Anim Pose Effector Mask |
| 342 | Anim Pose Overide Head Look |
| 343 | Anim Pose Overide Point Arm |
| 344 | Anim Pose Overide Point Gun |
| 345 | Anim Pose Use Zmp Gravity Compensation |
| 346 | Anim Pose Gravity Compensation Factor |
| 347 | Anim Pose Muscle Stiffness Left Arm |
| 348 | Anim Pose Muscle Stiffness Right Arm |
| 349 | Anim Pose Muscle Stiffness Spine |
| 350 | Anim Pose Muscle Stiffness Left Leg |
| 351 | Anim Pose Muscle Stiffness Right Leg |
| 352 | Anim Pose Stiffness Left Arm |
| 353 | Anim Pose Stiffness Right Arm |
| 354 | Anim Pose Stiffness Spine |
| 355 | Anim Pose Stiffness Left Leg |
| 356 | Anim Pose Stiffness Right Leg |
| 357 | Anim Pose Damping Left Arm |
| 358 | Anim Pose Damping Right Arm |
| 359 | Anim Pose Damping Spine |
| 360 | Anim Pose Damping Left Leg |
| 361 | Anim Pose Damping Right Leg |
| 362 | Anim Pose Grav Comp Left Arm |
| 363 | Anim Pose Grav Comp Right Arm |
| 364 | Anim Pose Grav Comp Spine |
| 365 | Anim Pose Grav Comp Left Leg |
| 366 | Anim Pose Grav Comp Right Leg |
| 367 | Anim Pose Connected Left Hand |
| 368 | Anim Pose Connected Right Hand |
| 369 | Anim Pose Connected Left Foot |
| 370 | Anim Pose Connected Right Foot |
| 371 | Anim Pose Anim Source |
| 372 | Windmill Msg |
| 373 | Windmill Fb |
| 374 | Windmill Left Part Id |
| 375 | Windmill Left Radius1 |
| 376 | Windmill Left Radius2 |
| 377 | Windmill Left Speed |
| 378 | Windmill Left Normal |
| 379 | Windmill Left Centre |
| 380 | Windmill Right Part Id |
| 381 | Windmill Right Radius1 |
| 382 | Windmill Right Radius2 |
| 383 | Windmill Right Speed |
| 384 | Windmill Right Normal |
| 385 | Windmill Right Centre |
| 386 | Windmill Shoulder Stiffness |
| 387 | Windmill Shoulder Damping |
| 388 | Windmill Elbow Stiffness |
| 389 | Windmill Elbow Damping |
| 390 | Windmill Left Elbow Min |
| 391 | Windmill Right Elbow Min |
| 392 | Windmill Phase Offset |
| 393 | Windmill Drag Reduction |
| 394 | Windmill Ik Twist |
| 395 | Windmill Ang Vel Thresh |
| 396 | Windmill Ang Vel Gain |
| 397 | Windmill Mirror Mode |
| 398 | Windmill Adaptive Mode |
| 399 | Windmill Force Sync |
| 400 | Windmill Use Left |
| 401 | Windmill Use Right |
| 402 | Windmill Disable On Impact |
| 403 | Windmilladapt Msg |
| 404 | Windmilladapt Fb |
| 405 | Windmilladapt Ang Speed |
| 406 | Windmilladapt Body Stiffness |
| 407 | Windmilladapt Amplitude |
| 408 | Windmilladapt Phase |
| 409 | Windmilladapt Arm Stiffness |
| 410 | Windmilladapt Left Elbow Angle |
| 411 | Windmilladapt Right Elbow Angle |
| 412 | Windmilladapt Lean 1 Mult |
| 413 | Windmilladapt Lean 1 Offset |
| 414 | Windmilladapt Elbow Rate |
| 415 | Windmilladapt Arm Dir |
| 416 | Windmilladapt Disable On Impact |
| 417 | Windmilladapt Set Back Angles |
| 418 | Windmilladapt Use Ang Mom |
| 419 | Windmilladapt Bend Left Elbow |
| 420 | Windmilladapt Bend Right Elbow |
| 421 | Windmilladapt Mask |
| 422 | Balancercollisionsreaction Msg |
| 423 | Balancercollisionsreaction Fb |
| 424 | Balancercollisionsreaction Num Steps Till Slump |
| 425 | Balancercollisionsreaction Stable To Slump Time |
| 426 | Balancercollisionsreaction Exclusion Zone |
| 427 | Balancercollisionsreaction Foot Friction Mult Start |
| 428 | Balancercollisionsreaction Foot Fritcion Mult Rate |
| 429 | Balancercollisionsreaction Back Friction Mult Start |
| 430 | Balancercollisionsreaction Back Friction Mult Rate |
| 431 | Balancercollisionsreaction Impact Leg Stiff Reduct |
| 432 | Balancercollisionsreaction Slump Leg Stiff Reduct |
| 433 | Balancercollisionsreaction Slump Leg Stiff Rate |
| 434 | Balancercollisionsreaction React Time |
| 435 | Balancercollisionsreaction Impact Exag Time |
| 436 | Balancercollisionsreaction Glance Spin Time |
| 437 | Balancercollisionsreaction Glance Spin Mag |
| 438 | Balancercollisionsreaction Glance Spin Decay Mult |
| 439 | Balancercollisionsreaction Ignore Col Index |
| 440 | Balancercollisionsreaction Slump Mode |
| 441 | Balancercollisionsreaction Rebound Mode |
| 442 | Balancercollisionsreaction Ignore Col Mass Below |
| 443 | Balancercollisionsreaction Ignore Col Vol Below |
| 444 | Balancercollisionsreaction Falloverwall Drape |
| 445 | Balancercollisionsreaction Fall Over High Walls |
| 446 | Balancercollisionsreaction Snap |
| 447 | Balancercollisionsreaction Snapmag |
| 448 | Balancercollisionsreaction Snap Direction Randomness |
| 449 | Balancercollisionsreaction Snap Left Arm |
| 450 | Balancercollisionsreaction Snap Right Arm |
| 451 | Balancercollisionsreaction Snap Left Leg |
| 452 | Balancercollisionsreaction Snap Right Leg |
| 453 | Balancercollisionsreaction Snap Spine |
| 454 | Balancercollisionsreaction Snap Neck |
| 455 | Balancercollisionsreaction Snap Phased Legs |
| 456 | Balancercollisionsreaction Snap Hip Type |
| 457 | Balancercollisionsreaction Unsnap Interval |
| 458 | Balancercollisionsreaction Unsnap Ratio |
| 459 | Balancercollisionsreaction Snap Use Torques |
| 460 | Balancercollisionsreaction Impact Weakness Zero Duration |
| 461 | Balancercollisionsreaction Impact Weakness Ramp Duration |
| 462 | Balancercollisionsreaction Impact Looseness Amount |
| 463 | Balancercollisionsreaction Obj Behind Victim |
| 464 | Balancercollisionsreaction Obj Behind Victim Pos |
| 465 | Balancercollisionsreaction Obj Behind Victim Normal |
| 466 | Balance Msg |
| 467 | Balance Fb |
| 468 | Balance Arm Stiffness |
| 469 | Balance Elbow |
| 470 | Balance Shoulder |
| 471 | Balance Arm Damping |
| 472 | Balance Lookat B |
| 473 | Balance Lookat Pos Vec3 |
| 474 | Balance Lookat Instanceidx |
| 475 | Balance Spine Stiffness |
| 476 | Balance Somersault Angle |
| 477 | Balance Somersault Angle Threshold |
| 478 | Balance Side Somersault Angle |
| 479 | Balance Side Somersault Angle Threshold |
| 480 | Balance Arms Out On Push |
| 481 | Balance Backwards Auto Turn |
| 482 | Balance Backwards Arms |
| 483 | Balance Blend To Zero Pose |
| 484 | Balance Arms Out On Push Multiplier |
| 485 | Balance Arms Out On Push Timeout |
| 486 | Balance Return To Balance Arms Out |
| 487 | Balance Arms Out Straighten Elbows |
| 488 | Balance Arms Out Min Lean2 |
| 489 | Balance Spine Damping |
| 490 | Balance Use Body Turn |
| 491 | Balance Elbow Angle On Contact |
| 492 | Balance Bend Elbows Time |
| 493 | Balance Bend Elbows Gait |
| 494 | Balance Hip L2 Arm L2 |
| 495 | Balance Shoulder L2 |
| 496 | Balance Shoulder L1 |
| 497 | Balance Shoulder Twist |
| 498 | Balance Head Look At Vel Prob |
| 499 | Balance Turn Off Prob |
| 500 | Balance Turn To Vel Prob |
| 501 | Balance Turn Away Prob |
| 502 | Balance Turn Left Prob |
| 503 | Balance Turn Right Prob |
| 504 | Balance Turn To Target Prob |
| 505 | Balance Ang Vel Multipler |
| 506 | Balance Ang Vel Threshold |
| 507 | Bodyfoetal Msg |
| 508 | Bodyfoetal Fb |
| 509 | Bodyfoetal Stiffness |
| 510 | Bodyfoetal Damping Factor |
| 511 | Bodyfoetal Asymmetry |
| 512 | Bodyfoetal Random Seed |
| 513 | Bodyfoetal Back Twist |
| 514 | Bodyfoetal Mask |
| 515 | Rollup Msg |
| 516 | Rollup Fb |
| 517 | Rollup Stiffness |
| 518 | Rollup Use Arm To Slow Down |
| 519 | Rollup Arm Reach Amount |
| 520 | Rollup Mask |
| 521 | Rollup Leg Push |
| 522 | Rollup Asymmetrical Legs |
| 523 | Rollup No Roll Time Before Success |
| 524 | Rollup Roll Success Vel |
| 525 | Rollup Roll Vel Lin Contribution |
| 526 | Writhe Msg |
| 527 | Writhe Fb |
| 528 | Writhe Arm Stiffness |
| 529 | Writhe Back Stiffness |
| 530 | Writhe Leg Stiffness |
| 531 | Writhe Arm Damping |
| 532 | Writhe Back Damping |
| 533 | Writhe Leg Damping |
| 534 | Writhe Arm Period |
| 535 | Writhe Back Period |
| 536 | Writhe Leg Period |
| 537 | Writhe Mask |
| 538 | Writhe Arm Amplitude |
| 539 | Writhe Back Amplitude |
| 540 | Writhe Leg Amplitude |
| 541 | Writhe Elbow Amplitude |
| 542 | Writhe Knee Amplitude |
| 543 | Writhe Roll Over |
| 544 | Writhe Blend Arms |
| 545 | Writhe Blend Back |
| 546 | Writhe Blend Legs |
| 547 | Writhe Apply Stiffness |
| 548 | Brace Msg |
| 549 | Brace Fb |
| 550 | Brace Distance |
| 551 | Brace Target Prediction Time |
| 552 | Brace Reach Absorbtion Time |
| 553 | Brace Instance Level Index |
| 554 | Brace Body Stiffness |
| 555 | Brace Grab Dont Let Go |
| 556 | Brace Grab Strength |
| 557 | Brace Grab Distance |
| 558 | Brace Grab Reach Angle |
| 559 | Brace Grab Hold Timer |
| 561 | Brace Leg Stiffness |
| 562 | Brace Time To Backwards Brace |
| 563 | Brace Lookat Vec3 |
| 564 | Brace Pos Vec3 |
| 565 | Brace Min Brace Time |
| 566 | Brace Hand Delay Min |
| 567 | Brace Hand Delay Max |
| 568 | Brace Move Away |
| 569 | Brace Move Away Amount |
| 570 | Brace Move Away Lean |
| 571 | Brace Move Sideways |
| 572 | Brace Bbarms |
| 573 | Brace New Brace |
| 574 | Brace Roll To Velocity |
| 575 | Brace Roll Type |
| 576 | Catchfall Msg |
| 577 | Catchfall Fb |
| 578 | Catchfall Torso Stiffness |
| 579 | Catchfall Legs Stiffness |
| 580 | Catchfall Arms Stiffness |
| 581 | Catchfall Backwards Min Arms Offset |
| 583 | Catchfall Zaxis Spin Reduction |
| 584 | Catchfall Use Headlook |
| 585 | Catchfall Mask |
| 586 | Debugrig Msg |
| 587 | Debugrig Fb |
| 588 | Debugrig Stiffness |
| 589 | Debugrig Damping |
| 590 | Debugrig Speed |
| 591 | Debugrig Joint |
| 592 | Debugskel Msg |
| 593 | Debugskel Fb |
| 594 | Debugskel Mode |
| 595 | Debugskel Root |
| 596 | Debugskel Mask |
| 597 | Dragged Msg |
| 598 | Dragged Fb |
| 599 | Dragged Arm Stiffness |
| 600 | Dragged Arm Damping |
| 601 | Dragged Arm Muscle Stiffness |
| 602 | Dragged Radius Tol |
| 603 | Dragged Rope Attach Inst |
| 604 | Dragged Rope Pos |
| 605 | Dragged Roped Body Part |
| 606 | Dragged Rope Taut |
| 607 | Dragged Player Control |
| 608 | Dragged Grab Left |
| 609 | Dragged Grab Right |
| 610 | Dragged Length Tol |
| 611 | Dragged Arm Twist |
| 612 | Dragged Reach |
| 613 | Electrocute Msg |
| 614 | Electrocute Fb |
| 615 | Electrocute Taze Time |
| 616 | Electrocute Relax Time |
| 617 | Electrocute Normal Time |
| 618 | Electrocute Taze Mag |
| 619 | Electrocute Taze Interval |
| 620 | Electrocute Direction Randomness |
| 621 | Electrocute Left Arm |
| 622 | Electrocute Right Arm |
| 623 | Electrocute Left Leg |
| 624 | Electrocute Right Leg |
| 625 | Electrocute Spine |
| 626 | Electrocute Neck |
| 627 | Electrocute Phased Legs |
| 628 | Electrocute Apply Stiffness |
| 629 | Electrocute Use Torques |
| 630 | Electrocute Hip Type |
| 631 | Fallover Wall Msg |
| 632 | Fallover Wall Fb |
| 633 | Fallover Wall State Fb |
| 634 | Fallover Wall Bodystiffness |
| 635 | Fallover Wall Damping |
| 636 | Fallover Wall Force Mag |
| 639 | Fallover Wall Step Exclusion Zone |
| 640 | Fallover Wall Min Leg Height |
| 641 | Fallover Wall Body Twist |
| 643 | Fallover Wall Fall Over Wall End A |
| 644 | Fallover Wall Fall Over Wall End B |
| 645 | Fallover Wall Force Angle Abort |
| 646 | Fallover Wall Force Time Out |
| 647 | Fallover Wall Move Arms |
| 648 | Fallover Wall Move Legs |
| 649 | Fallover Wall Bend Spine |
| 650 | Fallover Wall Angle Dir With Wall Normal |
| 651 | Fallover Wall Leaning Angle Threshold |
| 653 | Fallover Wall Adapt Forces To Low Wall |
| 655 | Fallover Wall Dist To Send Success Msg |
| 656 | Fallover Wall Use Arm Ik |
| 657 | Fallover Wall Reach Dist From Hit Point |
| 658 | Fallover Wall Min Reach Dist From Hit Point |
| 659 | Fallover Wall Angle Totally Back |
| 660 | Grab Msg |
| 661 | Grab R Fb |
| 662 | Grab Use Left |
| 663 | Grab Use Right |
| 664 | Grab Drop Weap If Necessary |
| 665 | Grab Drop Weapon Dist |
| 666 | Grab Strength |
| 667 | Grab Stickey Hands |
| 668 | Grab Turn To Target |
| 670 | Grab Pullup Timer |
| 671 | Grab Pullup Strength Right |
| 672 | Grab Pullup Strength Left |
| 673 | Grab Pos1 Vec3 |
| 674 | Grab Pos2 Vec3 |
| 675 | Grab Pos3 Vec3 |
| 676 | Grab Pos4 Vec3 |
| 677 | Grab Norm1 Vec3 |
| 678 | Grab Norm2 Vec3 |
| 679 | Grab Norm3 Vec3 |
| 680 | Grab Norm4 Vec3 |
| 681 | Grab Hands Collide |
| 682 | Grab Brace Only |
| 683 | Grab A Line |
| 684 | Grab Four Points |
| 685 | Grab Surface |
| 686 | Grab Instance Index |
| 687 | Grab Instance Part Index |
| 688 | Grab Dont Let Go |
| 689 | Grab Body Stiffness |
| 690 | Grab Reach Angle |
| 691 | Grab One Side Reach Angle |
| 692 | Grab Distance |
| 693 | Grab Move 2 Radius |
| 694 | Grab Arm Stiffness |
| 695 | Grab Reach Dist |
| 696 | Grab Orientation Constraint Scale |
| 698 | Grab Use Head Look To Target |
| 699 | Grab Look At Grab |
| 700 | Grab Head Look Target |
| 701 | Grab L Msg Extra Grab Message Just So We Can Check The 2Nd Feedback Message For Grab |
| 702 | Grab L Fb |
| 703 | Headlook Msg |
| 704 | Headlook Fb |
| 705 | Headlook Damping |
| 706 | Headlook Stiffness |
| 707 | Headlook Instance Index |
| 708 | Headlook Vel |
| 709 | Headlook Pos |
| 710 | Headlook Always Look |
| 711 | Headlook Always Eyes Horizontal |
| 712 | Headlook Keep Head Away From Ground |
| 713 | Headlook Extra Tilt |
| 714 | Headlook Twist Spine |
| 715 | Highfall Msg |
| 716 | Highfall Fb |
| 717 | Highfall Stiffness |
| 718 | Highfall Damping |
| 719 | Highfall Catch Fall Time |
| 720 | Highfall Cutoff Upright |
| 721 | Highfall Pd Strength |
| 722 | Highfall Pd Damping |
| 723 | Highfall Arm Ang Speed |
| 724 | Highfall Arm Amplitude |
| 725 | Highfall Arm Phase |
| 726 | Highfall Arm Bend Elbows |
| 727 | Highfall Leg Radius |
| 728 | Highfall Leg Angular Speed |
| 729 | Highfall Leg Asymmetry |
| 730 | Highfallarms To Legs Phase |
| 731 | Highfallarms To Legs Sync |
| 732 | Highfall Arms Up |
| 733 | Highfall Orientate Fall |
| 734 | Highfall Orientate Twist |
| 735 | Highfall Orientate Max |
| 736 | Highfall Alan Rickman |
| 737 | Highfall Forward Roll |
| 738 | Highfall Use Zero Pose With Forward Roll |
| 739 | Highfall Aim Angle |
| 740 | Highfall Fowardvel Mult |
| 741 | Highfall Foot Vel Comp Scale |
| 742 | Highfall Side Distance |
| 743 | Highfall Foward Offset |
| 744 | Highfall Leg L |
| 745 | Highfall Catch Fall Cutoff |
| 746 | Highfall Leg Strength |
| 747 | Highfall Balance |
| 748 | Highfall Ignore World Collisions |
| 749 | Highfall Adaptive Circling |
| 750 | Highfall Hula |
| 751 | Landing Msg |
| 752 | Landing Fb |
| 753 | Landing Body Stiffness |
| 754 | Landing Body Damping |
| 755 | Landing Catchfall Time |
| 756 | Landing Crash Or Land Cutoff |
| 757 | Landing Angle To Catchfall Cutoff |
| 758 | Landing Pd Strength |
| 759 | Landing Legradius |
| 760 | Landing Leg Ang Speed |
| 761 | Landing Arms Up |
| 762 | Landing Arms Frontward |
| 763 | Landing Orient Body To Fall Dir |
| 764 | Landing Pred Time To Orient Fall Dir |
| 765 | Landing Init Ang Vel Reduction Factor |
| 766 | Landing Limit Normal Fall |
| 767 | Landing Aim Angle Base |
| 768 | Landing Forward Vel Rot |
| 769 | Landing Side D |
| 770 | Landing Leg L |
| 771 | Landing Leg Strength |
| 772 | Landing Ignore World Col |
| 773 | Landing Forward Roll |
| 774 | Landing Feet Behind Com |
| 775 | Landing Feet Behind Com Vel |
| 776 | Landing Cheating Torque To Forward Roll |
| 778 | Landing Stop Fw Com Rot |
| 779 | Landing Stop End Fw Com Rot |
| 780 | Landing Stand Up Com Behind Feet |
| 781 | Landing Stand Up Rot Vel |
| 782 | Landing Strength Knee To Stand Up |
| 783 | Landing Side Roll |
| 785 | Incoming Transforms Msg |
| 786 | Incoming Transforms Fb |
| 787 | Injured On Ground Msg |
| 788 | Injured On Ground Fb |
| 789 | Injured On Ground Num Injuries |
| 790 | Injured On Ground Injury 1 Component |
| 791 | Injured On Ground Injury 2 Component |
| 792 | Injured On Ground Injury 1 Local Pos |
| 793 | Injured On Ground Injury 2 Local Pos |
| 794 | Injured On Ground Injury 1 Local Norm |
| 795 | Injured On Ground Injury 2 Local Norm |
| 796 | Injured On Ground Attacker Pos |
| 797 | Injured On Ground Dont Reach With Left |
| 798 | Injured On Ground Dont Reach With Right |
| 799 | Injured On Ground Strong Roll Force |
| 800 | Learnedcrawl Msg |
| 801 | Learnedcrawl Fb |
| 802 | Learnedcrawl Stiffness |
| 803 | Learnedcrawl Damping |
| 804 | Learnedcrawl Learn |
| 805 | Learnedcrawl Num Learning Frames |
| 806 | Learnedcrawl Input Seq |
| 807 | Learnedcrawl Input Seq Size |
| 808 | Learnedcrawl Yaw Offset |
| 809 | Learnedcrawl Target Pos |
| 810 | Learnedcrawl Speed |
| 811 | Learnedcrawl Anim Index |
| 812 | Learnedcrawl Learn From Anim Playback |
| 813 | Learnedcrawl Use Spine3 Thing |
| 814 | Learnedcrawl Use Roll Bone Comp |
| 815 | Learnedcrawl Use Twister |
| 816 | Pedal Msg |
| 817 | Pedal Fb |
| 818 | Pedal L Leg |
| 819 | Pedal R Leg |
| 820 | Pedal Backpedal |
| 821 | Pedal Radius |
| 822 | Pedal Speed |
| 823 | Pedal Leg Stiffness |
| 824 | Pedal Offset |
| 825 | Pedal Random Seed |
| 826 | Pedal Asymmetry |
| 827 | Pedal Adaptive Pedal 4 Dragging |
| 828 | Pedal Ang Speed Multiplier 4 Dragging |
| 829 | Pedal Radius Var |
| 830 | Pedal Leg Angle Var |
| 831 | Pedal Centre Sideways |
| 832 | Pedal Centre Forward |
| 833 | Pedal Centre Up |
| 834 | Pedal Spread |
| 835 | Pedal Ellipse |
| 836 | Pedal Drag Reduct |
| 837 | Pedal Hula |
| 838 | Point Arm Msg |
| 839 | Point Arm Fb |
| 840 | Point Arm Target Left Vec3 |
| 841 | Point Arm Twist Left |
| 842 | Point Arm Arm Straightness Left |
| 843 | Point Arm Use Left Arm |
| 844 | Point Arm Arm Stiffness Left |
| 845 | Point Arm Arm Damping Left |
| 846 | Point Arm Instance Index Left |
| 847 | Point Arm Point Swing Limit Left |
| 848 | Point Arm Use Zero Pose When Not Pointing Left |
| 849 | Point Arm Target Right Vec3 |
| 850 | Point Arm Twist Right |
| 851 | Point Arm Arm Straightness Right |
| 852 | Point Arm Use Right Arm |
| 853 | Point Arm Arm Stiffness Right |
| 854 | Point Arm Arm Damping Right |
| 855 | Point Arm Instance Index Right |
| 856 | Point Arm Point Swing Limit Right |
| 857 | Point Arm Use Zero Pose When Not Pointing Right |
| 858 | Pointgun Msg |
| 859 | Pointgun Fb |
| 860 | Pointgun Enable Right |
| 861 | Pointgun Enable Left |
| 862 | Pointgun Left Hand Target |
| 863 | Pointgun Left Hand Target Index |
| 864 | Pointgun Right Hand Target |
| 865 | Pointgun Right Hand Target Index |
| 866 | Pointgun Lead Target |
| 867 | Pointgun Arm Stiffness |
| 868 | Pointgun Arm Stiffness Det Support |
| 869 | Pointgun Arm Damping |
| 870 | Pointgun Gravity Opposition |
| 871 | Pointgun Grav Opp Det Support |
| 872 | Pointgun Mass Mult Det Support |
| 873 | Pointgun Allow Shot Looseness |
| 874 | Pointgun Clavicle Blend |
| 875 | Pointgun Elbow Attitude |
| 876 | Pointgun Support Constraint |
| 877 | Pointgun Constraint Min Dist |
| 878 | Pointgun Make Constraint Dist |
| 879 | Pointgun Reduce Constraint Leng Vel |
| 880 | Pointgun Break Str |
| 881 | Pointgun Constraint Str |
| 882 | Pointgun Constraint Thresh |
| 883 | Pointgun Broken Support Time |
| 884 | Pointgun Broken To Side Prob |
| 885 | Pointgun Connect After |
| 886 | Pointgun Connect For |
| 887 | Pointgun One Hand Pointing |
| 888 | Pointgun Always Support |
| 889 | Pointgun Pose Unused Gun Arm |
| 890 | Pointgun Pose Unused Support Arm |
| 891 | Pointgun Pose Unused Other Arm |
| 894 | Pointgun Pistol Neutral Type |
| 895 | Pointgun Neutral Point For Pistols |
| 896 | Pointgunneutral Point For Rifles |
| 897 | Pointgun Check Neutral Point |
| 898 | Pointgun Point To Side |
| 899 | Pointgun Add To Weapon Dist Side |
| 900 | Pointgun Point To Connect |
| 901 | Pointgun Add To Weapon Dist Connect |
| 902 | Pointgun Use Pistol Ik |
| 903 | Pointgun Use Spine Twist |
| 904 | Pointgun Use Turn To Target |
| 905 | Pointgun Use Head Look |
| 906 | Pointgun Error Threshold |
| 907 | Pointgun Fire Weapon Relax Time |
| 908 | Pointgun Fire Weapon Relax Amount |
| 909 | Pointgun Fire Weapon Relax Distance |
| 910 | Pointgun Extra Tilt |
| 911 | Pointgun Use Incoming Transforms |
| 912 | Pointgun Measure Parent Offset |
| 913 | Pointgun Left Hand Parent Offset |
| 914 | Pointgun Left Hand Parent Effector |
| 915 | Pointgun Right Hand Parent Offset |
| 916 | Pointgun Right Hand Parent Effector |
| 917 | Pointgun Primary Hand Weapon Dist |
| 918 | Pointgun Weapon Mask |
| 919 | Pointgun Constrain Rifle |
| 920 | Pointgun Rifle Constraint Min Dist |
| 921 | Pointgun Stabilize Rifle Stock |
| 922 | Pointgun Time Warp Active |
| 923 | Pointgun Time Warp Strength Scale |
| 924 | Pointgun Ori Stiff |
| 925 | Pointgun Ori Damp |
| 926 | Pointgun Pos Stiff |
| 927 | Pointgun Pos Damp |
| 928 | Pointgun Disable Arm Collisions |
| 929 | Pointgun Disable Rifle Collisions |
| 930 | Register Weapon Msg |
| 931 | Register Weapon Fb |
| 932 | Register Weapon Hand |
| 933 | Register Weapon Level Index |
| 934 | Register Weapon Constraint Handle |
| 935 | Register Weapon Gun To Hand A |
| 936 | Register Weapon Gun To Hand B |
| 937 | Register Weapon Gun To Hand C |
| 938 | Register Weapon Gun To Hand D |
| 939 | Register Weapon Gun To Muzzle |
| 940 | Register Weapon Gun To Butt |
| 941 | Rolldown Stairs Msg |
| 942 | Rolldown Stairs Fb |
| 943 | Rolldown Stairs Stiffness |
| 944 | Rolldown Stairs Damping |
| 945 | Rolldown Stairs Force Mag |
| 946 | Rolldown Stairs Asymmetry |
| 947 | Rolldown Stairs Use Arm To Slow |
| 948 | Rolldown Stairs Use Zero Pose |
| 949 | Rolldown Stairs Spin When In Air |
| 950 | Rolldown Stairs Arm Reach Amount |
| 951 | Rolldown Stairs Leg Push |
| 952 | Rolldown Stairs Try To Avoid Headbutt |
| 953 | Rolldown Stairs Arm Reach Length |
| 954 | Rolldown Stairs Custom Rolldir Vec3 |
| 955 | Rolldown Stairs Use Custom Rolldir |
| 956 | Rolldown Stairs Stiffness Decay Target |
| 957 | Rolldown Stairs Stiffness Decay Time |
| 958 | Rolldown Stairs Asymmetrical Legs |
| 959 | Rolldown Stairs Zaxis Spin Reduction |
| 960 | Rolldown Stairs Target Lin Vel Decay Time |
| 961 | Rolldown Stairs Target Lin Vel |
| 962 | Rolldown Stairs Helper Forces Only |
| 963 | Rolldown Stairs Use Object Below Vel |
| 964 | Rolldown Stairs Use Rel Vel |
| 965 | Rolldown Stairs Apply Foetal Legs |
| 966 | Rolldown Stairs Move Legs Foetal |
| 968 | Rolldown Stairs Min Ang Vel |
| 969 | Rolldown Stairs Apply New Roll Torque |
| 971 | Rolldown Stairs Roll Torque Mag |
| 972 | Rolldown Stairs Apply Helper Torque |
| 973 | Rolldown Stairs Align Delay |
| 974 | Rolldown Stairs Align Torque Mag |
| 975 | Rolldown Stairs Airborne Reduction |
| 976 | Set Character Underwater Msg |
| 977 | Set Character Underwater Fb |
| 978 | Set Character Underwater Is Underwater |
| 979 | Set Character Underwater Viscosity |
| 980 | Set Character Underwater Gravity Factor |
| 981 | Set Character Underwater Stroke |
| 982 | Set Character Underwater Linear Stroke |
| 983 | Shot Msg |
| 984 | Shot Fb |
| 985 | Shot Body Stiffness |
| 986 | Shot Spine Damping |
| 987 | Shot Arm Stiffness |
| 988 | Shot Initial Neck Stiffness |
| 989 | Shot Initial Neck Damping |
| 990 | Shot Neck Stiffness |
| 991 | Shot Neck Damping |
| 992 | Shot Kmult On Loose |
| 993 | Shot Kmult 4 Legs |
| 994 | Shot Looseness Amount |
| 995 | Shot Looseness For Fall |
| 996 | Shot Looseness For Stagger |
| 997 | Shot Min Arms Looseness |
| 998 | Shot Min Legs Looseness |
| 999 | Shot Grab Hold Time |
| 1000 | Shot Spine Blend Exag Cpain |
| 1001 | Shot Spine Blend Zero |
| 1002 | Shot Bullet Proof Vest |
| 1003 | Shot Always Reset Looseness |
| 1004 | Shot Always Reset Neck Looseness |
| 1005 | Shot Ang Vel Scale |
| 1006 | Shot Ang Vel Scale Mask |
| 1007 | Shot Fling Width |
| 1008 | Shot Time Before Reach For Wound |
| 1009 | Shot Exag Duration |
| 1010 | Shot Exag Mag |
| 1011 | Shot Exag Twist Mag |
| 1012 | Shot Exag Smooth2Zero |
| 1013 | Shot Exag Zero Time |
| 1014 | Shot Cpain Smooth2Time |
| 1015 | Shot Cpain Duration |
| 1016 | Shot Cpain Mag |
| 1017 | Shot Cpain Twist Mag |
| 1018 | Shot Cpain Smooth To Zero |
| 1019 | Shot Crouching |
| 1020 | Shot Chicken Arms |
| 1021 | Shot Reach For Wound |
| 1022 | Shot Reach For Wound Fb |
| 1023 | Shot Fling |
| 1024 | Shot Allow Inj Arm |
| 1025 | Shot Allow Injured Leg |
| 1026 | Shot Allow Injured Lower Leg Reach |
| 1027 | Shot Allow Injured Thigh Reach |
| 1028 | Shot Stable Hands Neck |
| 1029 | Shot Melee |
| 1030 | Shot Use Catchfall On Fall |
| 1031 | Shot Use Extended Catchfall |
| 1032 | Shot Init Weakness Zero Dur |
| 1033 | Shot Init Weakness Ramp Dur |
| 1034 | Shot Init Neck Dur |
| 1035 | Shot Init Neck Ramp Dur |
| 1036 | Shot Use Cstr Modulation |
| 1037 | Shot Cstr Upper Min |
| 1038 | Shot Cstr Upper Max |
| 1039 | Shot Cstr Lower Min |
| 1040 | Shot Cstr Lower Max |
| 1041 | Shot Death Time |
| 1042 | Shot Snap Msg |
| 1043 | Shot Snap Fb |
| 1044 | Shot Snap |
| 1045 | Shot Snap Mag |
| 1046 | Shot Snap Direction Randomness |
| 1047 | Shot Snap Left Arm |
| 1048 | Shot Snap Right Arm |
| 1049 | Shot Snap Left Leg |
| 1050 | Shot Snap Right Leg |
| 1051 | Shot Snap Spine |
| 1052 | Shot Snap Neck |
| 1053 | Shot Snap Phased Legs |
| 1054 | Shot Snap Hip Type |
| 1055 | Shot Snap Use Bullet Dir |
| 1056 | Shot Snap Hit Part |
| 1057 | Shot Unsnap Interval |
| 1058 | Shot Unsnap Ratio |
| 1059 | Shot Snap Use Torques |
| 1060 | Shotnewbullet Msg |
| 1061 | Shotnewbullet Fb |
| 1062 | Shotnewbullet Bodypart |
| 1063 | Shotnewbullet Local Hit Point Info |
| 1064 | Shotnewbullet Bullet Normal Vec3 |
| 1065 | Shotnewbullet Bullet Pos Vec3 |
| 1066 | Shotnewbullet Bullet Vel Vec3 |
| 1067 | Shotshockspin Msg |
| 1068 | Shotshockspin Fb |
| 1069 | Shotshockspin Add Shock Spin |
| 1070 | Shotshockspin Randomize Shock Spin Direction |
| 1071 | Shotshockspin Always Add Shock Spin |
| 1072 | Shotshockspin Shock Spin Min |
| 1073 | Shotshockspin Shock Spin Max |
| 1074 | Shotshockspin Shock Spin Lift Force Mult |
| 1075 | Shotshockspin Shock Spin Decay Mult |
| 1076 | Shotshockspin Shock Spin Scale Per Component |
| 1078 | Shotshockspin Lever Arm Scale |
| 1079 | Shotshockspin Air Mult |
| 1080 | Shotshockspin 1Foot Mult |
| 1081 | Shotshockspin Foot Grip Mult |
| 1082 | Shotshockspin Braced Side Spin Mult |
| 1083 | Shotfalltoknees Msg |
| 1084 | Shotfalltoknees Fb |
| 1085 | Shotfalltoknees Fall To Knees |
| 1086 | Shotfalltoknees Ftk Always Change Fall |
| 1087 | Shotfalltoknees Ftk Balance Time |
| 1088 | Shotfalltoknees Ftk Helper Force |
| 1089 | Shotfalltoknees Ftk Helper Force On Spine |
| 1090 | Shotfalltoknees Ftk Lean Help |
| 1091 | Shotfalltoknees Ftk Spine Bend |
| 1092 | Shotfalltoknees Ftk Stiff Spine |
| 1093 | Shotfalltoknees Ftk Impact Looseness |
| 1094 | Shotfalltoknees Ftk Impact Looseness Time |
| 1095 | Shotfalltoknees Ftk Bend Rate |
| 1096 | Shotfalltoknees Ftk Hip Blend |
| 1097 | Shotfalltoknees Ftk Fric Mult |
| 1098 | Shotfalltoknees Ftk Hip Angle Fall |
| 1099 | Shotfalltoknees Ftk Pitch Forwards |
| 1100 | Shotfalltoknees Ftk Pitch Backwards |
| 1101 | Shotfalltoknees Ftk Fall Below Stab |
| 1102 | Shotfalltoknees Ftk Balance Abort Threshold |
| 1103 | Shotfalltoknees Ftk On Knees Arm Type |
| 1104 | Shotfalltoknees Ftk Release Reach For Wound |
| 1105 | Shotfalltoknees Ftk Release Point Gun |
| 1106 | Shotfalltoknees Ftk Fail Must Collide |
| 1107 | Shotfrombehind Msg |
| 1108 | Shotfrombehind Fb |
| 1109 | Shotfrombehind Shot From Behind |
| 1110 | Shotfrombehind Spine Amount |
| 1111 | Shotfrombehind Neck Amount |
| 1112 | Shotfrombehind Hip Amount |
| 1113 | Shotfrombehind Knee Amount |
| 1114 | Shotfrombehind Period |
| 1115 | Shotfrombehind Force Balance Period |
| 1116 | Shotfrombehind Arms Onset |
| 1117 | Shotfrombehind Knees Onset |
| 1118 | Shotfrombehind Noise Gain |
| 1119 | Shotinguts Msg |
| 1120 | Shotinguts Fb |
| 1121 | Shotinguts Shot In Guts |
| 1122 | Shotinguts Spine Amount |
| 1123 | Shotinguts Neck Amount |
| 1124 | Shotinguts Hip Amount |
| 1125 | Shotinguts Knee Amount |
| 1126 | Shotinguts Period |
| 1127 | Shotinguts Force Balance Period |
| 1128 | Shotinguts Knees Onset |
| 1129 | Shotheadlook Msg |
| 1130 | Shotheadlook Fb |
| 1131 | Shotheadlook Lookat |
| 1132 | Shotheadlook Lookat Vec3 |
| 1133 | Shotheadlook Look At Wound Min Timer |
| 1136 | Shotheadlook Look At Shooter Min Timer |
| 1137 | Shotconfigurearms Msg |
| 1138 | Shotconfigurearms Fb |
| 1139 | Shotconfigurearms Brace |
| 1140 | Shotconfigurearms Pointgun |
| 1141 | Shotconfigurearms Use Arms Windmill |
| 1142 | Shotconfigurearms Release Wound |
| 1143 | Shotconfigurearms Always Reach Time |
| 1144 | Shotconfigurearms Speed Mult |
| 1145 | Shotconfigurearms Radius Mult |
| 1146 | Shotconfigurearms Stiffness Add |
| 1147 | Shotconfigurearms Reach With One Hand |
| 1148 | Shotconfigurearms Allow Left Pistol Rfw |
| 1149 | Shotconfigurearms Allow Right Pistol Rfw |
| 1150 | Shotconfigurearms Rfw With Pistol |
| 1151 | Staggerfall Msg |
| 1152 | Staggerfall Fb |
| 1153 | Staggerfall Arm Stiffness |
| 1154 | Staggerfall Arm Damping |
| 1155 | Staggerfall Spine Damping |
| 1156 | Staggerfall Spine Stiffness |
| 1157 | Staggerfall Arm Stiffness Start |
| 1158 | Staggerfall Arm Damping Start |
| 1159 | Staggerfall Spine Damping Start |
| 1160 | Staggerfall Spine Stiffness Start |
| 1161 | Staggerfall Time At Start Vals |
| 1162 | Staggerfall Ramp Time From Start Vals |
| 1163 | Staggerfall Stagger Step Prob |
| 1164 | Staggerfall Steps Till Start End |
| 1165 | Staggerfall Time Start End |
| 1166 | Staggerfall Ramp Time To End Vals |
| 1167 | Staggerfall Lower Body Stiffness |
| 1168 | Staggerfall Lower Body Stiffness End |
| 1169 | Staggerfall Prediction Time |
| 1170 | Staggerfall Per Step Reduction1 |
| 1171 | Staggerfall Lean In Dir Rate |
| 1176 | Staggerfall Lean To Mult F |
| 1177 | Staggerfall Lean To Mult B |
| 1178 | Staggerfall Push Off Dist |
| 1180 | Staggerfall Hip Bend Mult |
| 1181 | Staggerfall Always Bend Forwards |
| 1182 | Staggerfall Spine Bend Mult |
| 1183 | Staggerfall Use Head Look |
| 1184 | Staggerfall Head Look Pos |
| 1185 | Staggerfall Head Look Inst Index |
| 1186 | Staggerfall Head Look At Vel Prob |
| 1187 | Staggerfall Turn Off Prob |
| 1188 | Staggerfall Turn To Target Prob |
| 1189 | Staggerfall Turn To Vel Prob |
| 1190 | Staggerfall Turn Away Prob |
| 1191 | Staggerfall Turn Left Prob |
| 1192 | Staggerfall Turn Right Prob |
| 1193 | Staggerfall Use Body Turn |
| 1194 | Staggerfall Upper Body Reaction |
| 1195 | Stumble Msg |
| 1196 | Stumble Fb |
| 1197 | Stumble Torso Stiffness |
| 1198 | Stumble Legs Stiffness |
| 1199 | Stumble Arms Stiffness |
| 1200 | Stumble Arm Reduced Speed |
| 1201 | Stumble Arm Twist |
| 1202 | Stumble Stagger Time |
| 1203 | Stumble Drop Val |
| 1204 | Stumble Injury Rate |
| 1205 | Stumble Backwards Min Arm Offset |
| 1207 | Stumble Zaxis Spin Reduction |
| 1208 | Stumble Twist Spine |
| 1209 | Stumble Damp Pelvis |
| 1210 | Stumble Pitch In Contact |
| 1211 | Stumble Different |
| 1212 | Stumble Use Head Look |
| 1213 | Stumble Lean Rate |
| 1216 | Stumble Grab Radius 2 |
| 1217 | Stumble Lean Towards |
| 1218 | Stumble Wrist Ms |
| 1219 | Stumble Feet Ms |
| 1220 | Stumble Fall Mask |
| 1221 | Teeter Msg |
| 1222 | Teeter Fb |
| 1223 | Teeter Edge Left |
| 1224 | Teeter Edge Right |
| 1225 | Teeter Use Exclusion Zone |
| 1226 | Teeter Call Highfall |
| 1227 | Teeter Lean Away |
| 1228 | Flinch Msg |
| 1229 | Flinch Fb |
| 1230 | Flinch Right Handed |
| 1231 | Flinch Left Handed |
| 1232 | Flinch Hand Dist Leftright |
| 1233 | Flinch Hand Dist Frontback |
| 1234 | Flinch Hand Dist Vertical |
| 1235 | Flinch Body Stiffness |
| 1236 | Flinch Body Damping |
| 1237 | Flinch Back Bend |
| 1238 | Flinch Use Right Arm |
| 1239 | Flinch Use Left Arm |
| 1240 | Flinch Noise Scale |
| 1241 | Flinch New Hit |
| 1242 | Flinch Protect Head Toggle |
| 1243 | Flinch Dont Brace Head |
| 1244 | Flinch Apply Stiffness |
| 1245 | Flinch Head Look Away From Target |
| 1246 | Flinch Use Head Look |
| 1247 | Flinch Turn Towards |
| 1248 | Flinch Pos Vec3 |
| 1249 | Yanked Msg |
| 1250 | Yanked Fb |
| 1251 | Yanked Arm Stiffness |
| 1252 | Yanked Arm Damping |
| 1253 | Yanked Spine Damping |
| 1254 | Yanked Spine Stiffness |
| 1255 | Yanked Arm Stiffness Start |
| 1256 | Yanked Arm Damping Start |
| 1257 | Yanked Spine Damping Start |
| 1258 | Yanked Spine Stiffness Start |
| 1259 | Yanked Time At Start Vals |
| 1260 | Yanked Ramp Time From Start Vals |
| 1261 | Yanked Steps Till Start End |
| 1262 | Yanked Time Start End |
| 1263 | Yanked Ramp Time To End Values |
| 1264 | Yanked Lower Body Stiffness |
| 1265 | Yanked Lower Body Stiffness End |
| 1266 | Yanked Per Step Reduction |
| 1267 | Yanked Hip Pitch Forward |
| 1268 | Yanked Hip Pitch Back |
| 1269 | Yanked Spine Bend |
| 1270 | Yanked Foot Friction |
| 1271 | Yanked Turn Threshold Min |
| 1272 | Yanked Turn Threshold Max |
| 1273 | Yanked Use Head Look |
| 1274 | Yanked Head Look Pos |
| 1275 | Yanked Head Look Inst Index |
| 1276 | Yanked Head Look At Vel Prob |
| 1277 | Yanked Com Vel Rds Thresh |
| 1278 | Yanked Hula Period |
| 1279 | Yanked Hip Amplitude |
| 1280 | Yanked Spine Amplitude |
| 1281 | Yanked Min Relax Period |
| 1283 | Yanked Roll Help |
| 1284 | Yanked Ground Leg Stiffness |
| 1285 | Yanked Ground Arm Stiffness |
| 1286 | Yanked Ground Spine Stiffness |
| 1287 | Yanked Ground Leg Damping |
| 1288 | Yanked Ground Arm Damping |
| 1289 | Yanked Ground Spine Damping |
| 1290 | Yanked Ground Friction |
| 1291 | Configurelimits Msg |
| 1292 | Configurelimits Fb |
| 1293 | Configurelimits Mask |
| 1294 | Configurelimits Enable |
| 1295 | Configurelimits To Desired |
| 1296 | Configurelimits To Curr Animation |
| 1297 | Configurelimits Restore |
| 1298 | Configurelimits Index |
| 1299 | Configurelimits Lean1 |
| 1300 | Configurelimits Lean2 |
| 1301 | Configurelimits Twist |
| 1302 | Configurelimits Margin |
| 1303 | Quaddeath Msg |
| 1304 | Quaddeath Fb |
| 1305 | Quaddeath Start Stiffness |
| 1306 | Quaddeath End Stiffness |
| 1307 | Quaddeath Leg Start Stiffness |
| 1308 | Quaddeath Leg End Stiffness |
| 1309 | Quaddeath Body Ramp Duration |
| 1310 | Quaddeath Neck Ramp Duration |
| 1311 | Quaddeath Legs Ramp Duration |
| 1312 | Quaddeath Damping Scale |
| 1313 | Quaddeath Muscle Stiffness |
| 1314 | Quaddeath Head Lift |
| 1315 | Quaddeath Legs Flex Amount |
| 1316 | Quaddeath Legs Flex Duration |
| 1317 | Quaddeath Tendon Offset |
| 1318 | Quaddeath Helper Impulse |
| 1319 | Quaddeath Ang Vel Scale |
| 1320 | Quaddeath Ang Vel Scale Mask |
| 1321 | Hand Animation Fb |
| 1322 | Num Strings |


NM_START_PARAM and NM_STR in nm_strings.sch The messages type are the ones in the enum list that end in _MSG. These are the message names, as opposed to the params, and are all multiples of 20 so we can identify them.


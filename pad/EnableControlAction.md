---
ns: PAD
aliases: ["0x351220255d64c155"]
---
## ENABLE_CONTROL_ACTION

```c
// 0x351220255D64C155
void ENABLE_CONTROL_ACTION(int control, int action, bool enableRelatedActions);
```

## control Values:
| Value | Name |
| --- | --- |
| 0 | PLAYER_CONTROL |
| 1 | CAMERA_CONTROL |
| 2 | FRONTEND_CONTROL |


## action Values:
| Value | Name |
| --- | --- |
| 0 | Next Camera |
| 1 | Look Lr |
| 2 | Look Ud |
| 3 | Look Up Only |
| 4 | Look Down Only |
| 5 | Look Left Only |
| 6 | Look Right Only |
| 7 | Cinematic Slowmo |
| 8 | Scripted Fly Ud |
| 9 | Scripted Fly Lr |
| 10 | Scripted Fly Zup |
| 11 | Scripted Fly Zdown |
| 12 | Weapon Wheel Ud |
| 13 | Weapon Wheel Lr |
| 14 | Weapon Wheel Next |
| 15 | Weapon Wheel Prev |
| 16 | Select Next Weapon |
| 17 | Select Prev Weapon |
| 18 | Skip Cutscene |
| 19 | Character Wheel |
| 20 | Multiplayer Info |
| 21 | Sprint |
| 22 | Jump |
| 23 | Enter |
| 24 | Attack |
| 25 | Aim |
| 26 | Look Behind |
| 27 | Phone |
| 28 | Special Ability |
| 29 | Special Ability Secondary |
| 30 | Move Lr |
| 31 | Move Ud |
| 32 | Move Up Only |
| 33 | Move Down Only |
| 34 | Move Left Only |
| 35 | Move Right Only |
| 36 | Duck |
| 37 | Select Weapon |
| 38 | Pickup |
| 39 | Sniper Zoom |
| 40 | Sniper Zoom In Only |
| 41 | Sniper Zoom Out Only |
| 42 | Sniper Zoom In Secondary |
| 43 | Sniper Zoom Out Secondary |
| 44 | Cover |
| 45 | Reload |
| 46 | Talk |
| 47 | Detonate |
| 48 | Hud Special |
| 49 | Arrest |
| 50 | Accurate Aim |
| 51 | Context |
| 52 | Context Secondary |
| 53 | Weapon Special |
| 54 | Weapon Special Two |
| 55 | Dive |
| 56 | Drop Weapon |
| 57 | Drop Ammo |
| 58 | Throw Grenade |
| 59 | Veh Move Lr |
| 60 | Veh Move Ud |
| 61 | Veh Move Up Only |
| 62 | Veh Move Down Only |
| 63 | Veh Move Left Only |
| 64 | Veh Move Right Only |
| 65 | Veh Special |
| 66 | Veh Gun Lr |
| 67 | Veh Gun Ud |
| 68 | Veh Aim |
| 69 | Veh Attack |
| 70 | Veh Attack2 |
| 71 | Veh Accelerate |
| 72 | Veh Brake |
| 73 | Veh Duck |
| 74 | Veh Headlight |
| 75 | Veh Exit |
| 76 | Veh Handbrake |
| 77 | Veh Hotwire Left |
| 78 | Veh Hotwire Right |
| 79 | Veh Look Behind |
| 80 | Veh Cin Cam |
| 81 | Veh Next Radio |
| 82 | Veh Prev Radio |
| 83 | Veh Next Radio Track |
| 84 | Veh Prev Radio Track |
| 85 | Veh Radio Wheel |
| 86 | Veh Horn |
| 87 | Veh Fly Throttle Up |
| 88 | Veh Fly Throttle Down |
| 89 | Veh Fly Yaw Left |
| 90 | Veh Fly Yaw Right |
| 91 | Veh Passenger Aim |
| 92 | Veh Passenger Attack |
| 93 | Veh Special Ability Franklin |
| 94 | Veh Stunt Ud |
| 95 | Veh Cinematic Ud |
| 96 | Veh Cinematic Up Only |
| 97 | Veh Cinematic Down Only |
| 98 | Veh Cinematic Lr |
| 99 | Veh Select Next Weapon |
| 100 | Veh Select Prev Weapon |
| 101 | Veh Roof |
| 102 | Veh Jump (This Is For Bikes, Try Input Veh Car Jump) |
| 103 | Veh Grappling Hook |
| 104 | Veh Shuffle |
| 105 | Veh Drop Projectile |
| 106 | Veh Mouse Control Override |
| 107 | Veh Fly Roll Lr |
| 108 | Veh Fly Roll Left Only |
| 109 | Veh Fly Roll Right Only |
| 110 | Veh Fly Pitch Ud |
| 111 | Veh Fly Pitch Up Only |
| 112 | Veh Fly Pitch Down Only |
| 113 | Veh Fly Undercarriage |
| 114 | Veh Fly Attack |
| 115 | Veh Fly Select Next Weapon |
| 116 | Veh Fly Select Prev Weapon |
| 117 | Veh Fly Select Target Left |
| 118 | Veh Fly Select Target Right |
| 119 | Veh Fly Vertical Flight Mode |
| 120 | Veh Fly Duck |
| 121 | Veh Fly Attack Camera |
| 122 | Veh Fly Mouse Control Override |
| 123 | Veh Sub Turn Lr |
| 124 | Veh Sub Turn Left Only |
| 125 | Veh Sub Turn Right Only |
| 126 | Veh Sub Pitch Ud |
| 127 | Veh Sub Pitch Up Only |
| 128 | Veh Sub Pitch Down Only |
| 129 | Veh Sub Throttle Up |
| 130 | Veh Sub Throttle Down |
| 131 | Veh Sub Ascend |
| 132 | Veh Sub Descend |
| 133 | Veh Sub Turn Hard Left |
| 134 | Veh Sub Turn Hard Right |
| 135 | Veh Sub Mouse Control Override |
| 136 | Veh Pushbike Pedal |
| 137 | Veh Pushbike Sprint |
| 138 | Veh Pushbike Front Brake |
| 139 | Veh Pushbike Rear Brake |
| 140 | Melee Attack Light |
| 141 | Melee Attack Heavy |
| 142 | Melee Attack Alternate |
| 143 | Melee Block |
| 144 | Parachute Deploy |
| 145 | Parachute Detach |
| 146 | Parachute Turn Lr |
| 147 | Parachute Turn Left Only |
| 148 | Parachute Turn Right Only |
| 149 | Parachute Pitch Ud |
| 150 | Parachute Pitch Up Only |
| 151 | Parachute Pitch Down Only |
| 152 | Parachute Brake Left |
| 153 | Parachute Brake Right |
| 154 | Parachute Smoke |
| 155 | Parachute Precision Landing |
| 156 | Map |
| 157 | Select Weapon Unarmed |
| 158 | Select Weapon Melee |
| 159 | Select Weapon Handgun |
| 160 | Select Weapon Shotgun |
| 161 | Select Weapon Smg |
| 162 | Select Weapon Auto Rifle |
| 163 | Select Weapon Sniper |
| 164 | Select Weapon Heavy |
| 165 | Select Weapon Special |
| 166 | Select Character Michael |
| 167 | Select Character Franklin |
| 168 | Select Character Trevor |
| 169 | Select Character Multiplayer |
| 170 | Save Replay Clip |
| 171 | Special Ability Pc (This Is So You Can Have The Same Input For Both On Foot And In-Car Special Abilities On Pc) |
| 172 | Cellphone Up |
| 173 | Cellphone Down |
| 174 | Cellphone Left |
| 175 | Cellphone Right |
| 176 | Cellphone Select |
| 177 | Cellphone Cancel |
| 178 | Cellphone Option |
| 179 | Cellphone Extra Option |
| 180 | Cellphone Scroll Forward |
| 181 | Cellphone Scroll Backward |
| 182 | Cellphone Camera Focus Lock |
| 183 | Cellphone Camera Grid |
| 184 | Cellphone Camera Selfie |
| 185 | Cellphone Camera Dof |
| 186 | Cellphone Camera Expression |
| 187 | Frontend Down |
| 188 | Frontend Up |
| 189 | Frontend Left |
| 190 | Frontend Right |
| 191 | Frontend Rdown |
| 192 | Frontend Rup |
| 193 | Frontend Rleft |
| 194 | Frontend Rright |
| 195 | Frontend Axis X |
| 196 | Frontend Axis Y |
| 197 | Frontend Right Axis X |
| 198 | Frontend Right Axis Y |
| 199 | Frontend Pause |
| 200 | Frontend Pause Alternate (Alternate Pause To Get Around Conflict Issues With Esc Going Back On Pc.) |
| 201 | Frontend Accept |
| 202 | Frontend Cancel |
| 203 | Frontend X |
| 204 | Frontend Y |
| 205 | Frontend Lb |
| 206 | Frontend Rb |
| 207 | Frontend Lt |
| 208 | Frontend Rt |
| 209 | Frontend Ls |
| 210 | Frontend Rs |
| 211 | Frontend Leaderboard |
| 212 | Frontend Social Club |
| 213 | Frontend Social Club Secondary |
| 214 | Frontend Delete |
| 215 | Frontend Endscreen Accept |
| 216 | Frontend Endscreen Expand |
| 217 | Frontend Select (Dp: Ensure You Update Input Frontend Control End If You Add Any More Frontend Input!) |
| 218 | Script Left Axis X (Left Stick X Analogue Input. Values May Be > 1 When Using A Mouse. Usually Maps To Movement) |
| 219 | Script Left Axis Y (Left Stick Y Analogue Input. Values May Be > 1 When Using A Mouse. Usually Maps To Movement) |
| 220 | Script Right Axis X (Right Stick X Analogue Input. Values May Be > 1 When Using A Mouse. Usually Maps To Look.) |
| 221 | Script Right Axis Y (Right Stick Y Analogue Input. Values May Be > 1 When Using A Mouse. Usually Maps To Look.) |
| 222 | Script Rup (Ps3 = Triangle, 360 = Y) |
| 223 | Script Rdown (Ps3 = X, 360 = A) |
| 224 | Script Rleft (Ps3 = Square, 360 = X) |
| 225 | Script Rright (Ps3 = Circle, 360 = B) |
| 226 | Script Lb (Left Shoulder Button) |
| 227 | Script Rb (Right Shoulder Button) |
| 228 | Script Lt (Left Shoulder Trigger - Digital Only) |
| 229 | Script Rt (Right Shoulder Trigger - Digital Only) |
| 230 | Script Ls (Left Stick L3 Button,) |
| 231 | Script Rs (Right Stick R3 Button) |
| 232 | Script Pad Up (D-Pad / Directional Buttons Up) |
| 233 | Script Pad Down (D-Pad / Directional Buttons Down) |
| 234 | Script Pad Left (D-Pad / Directional Buttons Left) |
| 235 | Script Pad Right (D-Pad / Directional Buttons Right) |
| 236 | Script Select (Back Button On 360, Select On Ps3) |
| 237 | Cursor Accept (Touch Pad Click Or Mouse Button 1 Click) |
| 238 | Cursor Cancel (Mouse Button 2 Click) |
| 239 | Cursor X (The Cursor X Position In The Range Of 0...1.) |
| 240 | Cursor Y (The Cursor Y Position In The Range Of 0...1.) |
| 241 | Cursor Scroll Up (Scroll Up, E.G. Mouse Wheel) |
| 242 | Cursor Scroll Down (Scroll Down, E.G. Mouse Wheel) |
| 243 | Enter Cheat Code (Brings Up The Cheat Code Input Box.) |
| 244 | Interaction Menu (Brings Up The Interaction Menu.) |
| 245 | Mp Text Chat All (Brings Up Text Chat Box. Message Sent To All Players On A Server.) |
| 246 | Mp Text Chat Team (Brings Up Text Chat Box. Message Sent To All Players On In The Current Team.) |
| 247 | Mp Text Chat Friends (Brings Up Text Chat Box. Message Sent To All Friends On A Server) |
| 248 | Mp Text Chat Crew (Brings Up Text Chat Box. Message Sent To All Crew On A Server) |
| 249 | Pc Push To Talk (Push To Talk For Voip) |
| 250 | Creator Ls (Creator Left Stick Equivalent For Functions Like Field Of View, Etc.) |
| 251 | Creator Rs (Creator Right Stick Equivalent For Functions Like Field Of View, Etc.) |
| 252 | Creator Lt (Creator Left Trigger Equivalent For Zooming.) |
| 253 | Creator Rt (Creator Right Trigger Equivalent For Zooming.) |
| 254 | Creator Menu Toggle (Creator Menu Toggle On/Off For Pc Keyboard And Mouse.) |
| 255 | Creator Accept (Creator Accept/Place Items Button.) |
| 256 | Creator Delete (Creator Delete Items Button.) |
| 257 | Attack2 (Know One Knows What This Does!) |
| 258 | Rappel Jump |
| 259 | Rappel Long Jump |
| 260 | Rappel Smash Window |
| 261 | Prev Weapon |
| 262 | Next Weapon |
| 263 | Melee Attack1 (This Has Been Renamed To Input Melee Attack Light. If This Should Be Kept As It Is, Let Me Know Thomas.Randall@Rockstarleeds.Com) |
| 264 | Melee Attack2 (This Has Been Renamed To Input Melee Attack Heavy. If This Should Be Kept As It Is, Let Me Know Thomas.Randall@Rockstarleeds.Com) |
| 265 | Whistle (This Is Mapped To Nothing And Is Not Used Anywhere, It Is Added Here So Scripts Work. If This Should Be Kept Let Me Know Thomas.Randall@Rockstarleeds.Com) |
| 266 | Move Left |
| 267 | Move Right |
| 268 | Move Up |
| 269 | Move Down |
| 270 | Look Left |
| 271 | Look Right |
| 272 | Look Up |
| 273 | Look Down |
| 274 | Sniper Zoom In |
| 275 | Sniper Zoom Out |
| 276 | Sniper Zoom In Alternate |
| 277 | Sniper Zoom Out Alternate |
| 278 | Veh Move Left |
| 279 | Veh Move Right |
| 280 | Veh Move Up |
| 281 | Veh Move Down |
| 282 | Veh Gun Left |
| 283 | Veh Gun Right |
| 284 | Veh Gun Up |
| 285 | Veh Gun Down |
| 286 | Veh Look Left |
| 287 | Veh Look Right |
| 288 | Replay Start Stop Recording |
| 289 | Replay Start Stop Recording Secondary |
| 290 | Scaled Look Lr |
| 291 | Scaled Look Ud |
| 292 | Scaled Look Up Only |
| 293 | Scaled Look Down Only |
| 294 | Scaled Look Left Only |
| 295 | Scaled Look Right Only |
| 296 | Replay Marker Delete |
| 297 | Replay Clip Delete |
| 298 | Replay Pause |
| 299 | Replay Rewind |
| 300 | Replay Ffwd |
| 301 | Replay Newmarker |
| 302 | Replay Record |
| 303 | Replay Screenshot |
| 304 | Replay Hidehud |
| 305 | Replay Startpoint |
| 306 | Replay Endpoint |
| 307 | Replay Advance |
| 308 | Replay Back |
| 309 | Replay Tools |
| 310 | Replay Restart |
| 311 | Replay Showhotkey |
| 312 | Replay Cyclemarkerleft |
| 313 | Replay Cyclemarkerright |
| 314 | Replay Fovincrease |
| 315 | Replay Fovdecrease |
| 316 | Replay Cameraup |
| 317 | Replay Cameradown |
| 318 | Replay Save |
| 319 | Replay Toggletime |
| 320 | Replay Toggletips |
| 321 | Replay Preview |
| 322 | Replay Toggle Timeline |
| 323 | Replay Timeline Pickup Clip |
| 324 | Replay Timeline Duplicate Clip |
| 325 | Replay Timeline Place Clip |
| 326 | Replay Ctrl |
| 327 | Replay Timeline Save |
| 328 | Replay Preview Audio |
| 329 | Veh Drive Look |
| 330 | Veh Drive Look2 |
| 331 | Veh Fly Attack2 |
| 332 | Radio Wheel Ud |
| 333 | Radio Wheel Lr |
| 334 | Veh Slowmo Up |
| 335 | Veh Slowmo Up Only |
| 336 | Veh Slowmo Down Only |
| 337 | Veh Hydraulics Control Toggle |
| 338 | Veh Hydraulics Control Left |
| 339 | Veh Hydraulics Control Right |
| 340 | Veh Hydraulics Control Up |
| 341 | Veh Hydraulics Control Down |
| 342 | Veh Hydraulics Control Lr |
| 343 | Veh Hydraulics Control Ud |
| 344 | Switch Visor |
| 345 | Veh Melee Hold |
| 346 | Veh Melee Left |
| 347 | Veh Melee Right |
| 348 | Map Poi |
| 349 | Replay Snapmatic Photo |
| 350 | Veh Car Jump |
| 351 | Veh Rocket Boost |
| 352 | Veh Fly Boost |
| 353 | Veh Parachute |
| 354 | Veh Bike Wings |
| 355 | Veh Fly Bomb Bay |
| 356 | Veh Fly Counter |
| 357 | Veh Transform |
| 358 | Quad Loco Reverse |
| 359 | Respawn Faster |
| 360 | Hudmarker Select |
| 361 | Eat Snack |
| 362 | Use Armor |


If enableRelatedActions is true, related inputs will also be enabled. For example, enabling INPUT_SELECT_WEAPON will also enable INPUT_SELECT_WEAPON_UNARMED (and others) so the weapon can be selected by the other means.


## Parameters
* **control**: 
* **action**: 
* **enableRelatedActions**: (Default value: `True`)

---
ns: HUD
aliases: ["0x1ccc708f0f850613"]
---
## REPLACE_HUD_COLOUR

```c
// 0x1CCC708F0F850613
void REPLACE_HUD_COLOUR(int destHudColour, int srcHudColour);
```

```
replaces destHudColour with srcHudColour

Possible values for destHudColour:
| Index | Name |
| --- | --- |
| 0 | Pure White |
| 1 | White |
| 2 | Black |
| 3 | Grey |
| 4 | Greylight |
| 5 | Greydark |
| 6 | Red |
| 7 | Redlight |
| 8 | Reddark |
| 9 | Blue |
| 10 | Bluelight |
| 11 | Bluedark |
| 12 | Yellow |
| 13 | Yellowlight |
| 14 | Yellowdark |
| 15 | Orange |
| 16 | Orangelight |
| 17 | Orangedark |
| 18 | Green |
| 19 | Greenlight |
| 20 | Greendark |
| 21 | Purple |
| 22 | Purplelight |
| 23 | Purpledark |
| 24 | Pink |
| 25 | Star |
| 26 | Starlight |
| 27 | Stardark |
| 28 | Net Player1 |
| 29 | Net Player2 |
| 30 | Net Player3 |
| 31 | Net Player4 |
| 32 | Net Player5 |
| 33 | Net Player6 |
| 34 | Net Player7 |
| 35 | Net Player8 |
| 36 | Net Player9 |
| 37 | Net Player10 |
| 38 | Net Player11 |
| 39 | Net Player12 |
| 40 | Net Player13 |
| 41 | Net Player14 |
| 42 | Net Player15 |
| 43 | Net Player16 |
| 44 | Net Player17 |
| 45 | Net Player18 |
| 46 | Net Player19 |
| 47 | Net Player20 |
| 48 | Net Player21 |
| 49 | Net Player22 |
| 50 | Net Player23 |
| 51 | Net Player24 |
| 52 | Net Player25 |
| 53 | Net Player26 |
| 54 | Net Player27 |
| 55 | Net Player28 |
| 56 | Net Player29 |
| 57 | Net Player30 |
| 58 | Net Player31 |
| 59 | Net Player32 |
| 60 | Simpleblip Default |
| 61 | Menu Blue |
| 62 | Menu Grey Light |
| 63 | Menu Blue Extra Dark |
| 64 | Menu Yellow |
| 65 | Menu Yellow Dark |
| 66 | Menu Green |
| 67 | Menu Grey |
| 68 | Menu Grey Dark |
| 69 | Menu Highlight |
| 70 | Menu Standard |
| 71 | Menu Dimmed |
| 72 | Menu Extra Dimmed |
| 73 | Brief Title |
| 74 | Mid Grey Mp |
| 75 | Net Player1 Dark |
| 76 | Net Player2 Dark |
| 77 | Net Player3 Dark |
| 78 | Net Player4 Dark |
| 79 | Net Player5 Dark |
| 80 | Net Player6 Dark |
| 81 | Net Player7 Dark |
| 82 | Net Player8 Dark |
| 83 | Net Player9 Dark |
| 84 | Net Player10 Dark |
| 85 | Net Player11 Dark |
| 86 | Net Player12 Dark |
| 87 | Net Player13 Dark |
| 88 | Net Player14 Dark |
| 89 | Net Player15 Dark |
| 90 | Net Player16 Dark |
| 91 | Net Player17 Dark |
| 92 | Net Player18 Dark |
| 93 | Net Player19 Dark |
| 94 | Net Player20 Dark |
| 95 | Net Player21 Dark |
| 96 | Net Player22 Dark |
| 97 | Net Player23 Dark |
| 98 | Net Player24 Dark |
| 99 | Net Player25 Dark |
| 100 | Net Player26 Dark |
| 101 | Net Player27 Dark |
| 102 | Net Player28 Dark |
| 103 | Net Player29 Dark |
| 104 | Net Player30 Dark |
| 105 | Net Player31 Dark |
| 106 | Net Player32 Dark |
| 107 | Bronze |
| 108 | Silver |
| 109 | Gold |
| 110 | Platinum |
| 111 | Gang1 |
| 112 | Gang2 |
| 113 | Gang3 |
| 114 | Gang4 |
| 115 | Same Crew |
| 116 | Freemode |
| 117 | Pause Bg |
| 118 | Friendly |
| 119 | Enemy |
| 120 | Location |
| 121 | Pickup |
| 122 | Pause Singleplayer |
| 123 | Freemode Dark |
| 124 | Inactive Mission |
| 125 | Damage |
| 126 | Pinklight |
| 127 | Pm Mitem Highlight |
| 128 | Script Variable Marked By ~V~. Can Be Altered With The Set Script Variable Hud Colour Script Command |
| 129 | Yoga |
| 130 | Tennis |
| 131 | Golf |
| 132 | Shooting Range |
| 133 | Flight School |
| 134 | North Blue |
| 135 | Social Club |
| 136 | Platform Blue |
| 137 | Platform Green |
| 138 | Platform Grey |
| 139 | Facebook Blue |
| 140 | Ingame Bg |
| 141 | Darts |
| 142 | Waypoint |
| 143 | Michael |
| 144 | Franklin |
| 145 | Trevor |
| 146 | Golf P1 |
| 147 | Golf P2 |
| 148 | Golf P3 |
| 149 | Golf P4 |
| 150 | Waypointlight |
| 151 | Waypointdark |
| 152 | Panel Light |
| 153 | Michael Dark |
| 154 | Franklin Dark |
| 155 | Trevor Dark |
| 156 | Objective Route |
| 157 | Pausemap Tint |
| 158 | Pause Deselect |
| 159 | Pm Weapons Purchasable |
| 160 | Pm Weapons Locked |
| 161 | End Screen Bg |
| 162 | Chop |
| 163 | Pausemap Tint Half |
| 164 | North Blue Official |
| 165 | Script Variable 2 Marked By ~U~. Can Be Altered With The Set Second Script Variable Hud Colour Script Command |
| 166 | H |
| 167 | Hdark |
| 168 | T |
| 169 | Tdark |
| 170 | Hshard |
| 171 | Controller Michael |
| 172 | Controller Franklin |
| 173 | Controller Trevor |
| 174 | Controller Chop |
| 175 | Video Editor Video |
| 176 | Video Editor Audio |
| 177 | Video Editor Text |
| 178 | Hb Blue |
| 179 | Hb Yellow |
| 180 | Video Editor Score |
| 181 | Video Editor Audio Fadeout |
| 182 | Video Editor Text Fadeout |
| 183 | Video Editor Score Fadeout |
| 184 | Heist Background |
| 185 | Video Editor Ambient |
| 186 | Video Editor Ambient Fadeout |
| 187 | Gang Boss |
| 188 | Goon |
| 189 | Boss |
| 190 | Low Flow |
| 191 | Low Flow Dark |
| 192 | G1 |
| 193 | G2 |
| 194 | G3 |
| 195 | G4 |
| 196 | G5 |
| 197 | G6 |
| 198 | G7 |
| 199 | G8 |
| 200 | G9 |
| 201 | G10 |
| 202 | G11 |
| 203 | G12 |
| 204 | G13 |
| 205 | G14 |
| 206 | G15 |
| 207 | Adversary |
| 208 | Degen Red |
| 209 | Degen Yellow |
| 210 | Degen Green |
| 211 | Degen Cyan |
| 212 | Degen Blue |
| 213 | Degen Magenta |
| 214 | Stunt 1 |
| 215 | Stunt 2 |
| 216 | Special Race Series |
| 217 | Special Race Series Dark |
| 218 | Cs |
| 219 | Cs Dark |
| 220 | Tech Green |
| 221 | Tech Green Dark |
| 222 | Tech Red |
| 223 | Tech Green Very Dark |
| 224 | Placeholder 01 |
| 225 | Placeholder 02 |
| 226 | Placeholder 03 |
| 227 | Placeholder 04 |
| 228 | Placeholder 05 |
| 229 | Placeholder 06 |
| 230 | Placeholder 07 |
| 231 | Placeholder 08 |
| 232 | Placeholder 09 |
| 233 | Placeholder 10 |
| 234 | Junk Energy |
```

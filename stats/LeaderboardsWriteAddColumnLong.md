---
ns: STATS
aliases: ["0x2e65248609523599"]
---
## LEADERBOARDS_WRITE_ADD_COLUMN_LONG

```c
// 0x2E65248609523599
void LEADERBOARDS_WRITE_ADD_COLUMN_LONG(int fieldId, int value_a, int value_b);
```

Set a integerfloat value in a column. Must be used after calling [`LEADERBOARDS2_WRITE_DATA`](#_0xAE2206545888AE49).

## Values for `fieldId`:
| Value | Name |
| --- | --- |
| -1 | Servertime |
| 0 | Invalid |
| 1 | Col Accuracy |
| 2 | Col Best Time |
| 3 | Col Bookie Income |
| 4 | Col Bookie Payout |
| 5 | Col Bullets Fired |
| 6 | Col Cabs Wrecked |
| 7 | Col Car Damage |
| 8 | Col Cash |
| 9 | Col Checkpoint 0 |
| 10 | Col Checkpoint 1 |
| 11 | Col Checkpoint 10 |
| 12 | Col Checkpoint 11 |
| 13 | Col Checkpoint 12 |
| 14 | Col Checkpoint 13 |
| 15 | Col Checkpoint 14 |
| 16 | Col Checkpoint 15 |
| 17 | Col Checkpoint 16 |
| 18 | Col Checkpoint 17 |
| 19 | Col Checkpoint 18 |
| 20 | Col Checkpoint 19 |
| 21 | Col Checkpoint 2 |
| 22 | Col Checkpoint 20 |
| 23 | Col Checkpoint 21 |
| 24 | Col Checkpoint 22 |
| 25 | Col Checkpoint 23 |
| 26 | Col Checkpoint 24 |
| 27 | Col Checkpoint 25 |
| 28 | Col Checkpoint 26 |
| 29 | Col Checkpoint 27 |
| 30 | Col Checkpoint 28 |
| 31 | Col Checkpoint 29 |
| 32 | Col Checkpoint 3 |
| 33 | Col Checkpoint 30 |
| 34 | Col Checkpoint 31 |
| 35 | Col Checkpoint 32 |
| 36 | Col Checkpoint 33 |
| 37 | Col Checkpoint 34 |
| 38 | Col Checkpoint 35 |
| 39 | Col Checkpoint 36 |
| 40 | Col Checkpoint 37 |
| 41 | Col Checkpoint 38 |
| 42 | Col Checkpoint 39 |
| 43 | Col Checkpoint 4 |
| 44 | Col Checkpoint 40 |
| 45 | Col Checkpoint 41 |
| 46 | Col Checkpoint 42 |
| 47 | Col Checkpoint 43 |
| 48 | Col Checkpoint 44 |
| 49 | Col Checkpoint 45 |
| 50 | Col Checkpoint 46 |
| 51 | Col Checkpoint 47 |
| 52 | Col Checkpoint 48 |
| 53 | Col Checkpoint 49 |
| 54 | Col Checkpoint 5 |
| 55 | Col Checkpoint 50 |
| 56 | Col Checkpoint 51 |
| 57 | Col Checkpoint 52 |
| 58 | Col Checkpoint 53 |
| 59 | Col Checkpoint 54 |
| 60 | Col Checkpoint 55 |
| 61 | Col Checkpoint 56 |
| 62 | Col Checkpoint 57 |
| 63 | Col Checkpoint 58 |
| 64 | Col Checkpoint 59 |
| 65 | Col Checkpoint 6 |
| 66 | Col Checkpoint 60 |
| 67 | Col Checkpoint 61 |
| 68 | Col Checkpoint 62 |
| 69 | Col Checkpoint 63 |
| 70 | Col Checkpoint 64 |
| 71 | Col Checkpoint 65 |
| 72 | Col Checkpoint 66 |
| 73 | Col Checkpoint 67 |
| 74 | Col Checkpoint 68 |
| 75 | Col Checkpoint 69 |
| 76 | Col Checkpoint 7 |
| 77 | Col Checkpoint 8 |
| 78 | Col Checkpoint 9 |
| 79 | Col Custom Vehicle |
| 80 | Col Deaths |
| 81 | Col Dist Cab |
| 82 | Col Fails |
| 83 | Col Gang Cash 0 |
| 84 | Col Gang Cash 1 |
| 85 | Col Gang Cash 2 |
| 86 | Col Gold Medals |
| 87 | Col Headshots |
| 88 | Col Highest Deuce |
| 89 | Col Highest Tip |
| 90 | Col Innocents Killed |
| 91 | Col Jump Score |
| 92 | Col Kills |
| 93 | Col Distance |
| 94 | Col Longest Fare |
| 96 | Col Medal |
| 97 | Col Number Bets |
| 98 | Col Number Landings |
| 99 | Col Num 180S |
| 100 | Col Num Aced |
| 101 | Col Num Aces |
| 102 | Col Num Booty Calls |
| 103 | Col Num Bull Eyes |
| 104 | Col Num Drives |
| 105 | Col Num Faults |
| 106 | Col Num Games Lost |
| 107 | Col Num Games Won |
| 108 | Col Num Lap Dances |
| 109 | Col Num Matches |
| 110 | Col Num Matches Lost |
| 111 | Col Num Out Of Bounds |
| 112 | Col Num Points |
| 113 | Col Num Putt |
| 114 | Col Num Robberies |
| 115 | Col Num Sets Lost |
| 116 | Col Num Sets Won |
| 117 | Col Num Sex Act1 |
| 118 | Col Num Sex Act2 |
| 125 | Col Num Wins |
| 126 | Col Passes |
| 127 | Col Player Damage |
| 128 | Col Ratio |
| 129 | Col Ratio Score |
| 130 | Col Replays |
| 131 | Col Score |
| 132 | Col Special Ability Time |
| 133 | Col Special Score 1 |
| 134 | Col Special Score 2 |
| 135 | Col Special Score 3 |
| 136 | Col Special Score 4 |
| 137 | Col Special Score 5 |
| 138 | Col Special Time 1 |
| 139 | Col Special Time 2 |
| 140 | Col Special Time 3 |
| 141 | Col Special Time 4 |
| 142 | Col Switches |
| 143 | Col Territory Owner 0 |
| 144 | Col Territory Owner 1 |
| 145 | Col Territory Owner 2 |
| 146 | Col Tips Earned |
| 147 | Col Total Time |
| 148 | Col Vehicle Color |
| 149 | Col Vehicle Id |
| 150 | Col Weapon Used |
| 151 | Col Win Streak |
| 152 | Col Shots Fired |
| 153 | Col Shots Hit |
| 154 | Col Total Shots Fired |
| 155 | Col Total Shots Hit |
| 156 | Col Match Id |
| 157 | Col Bronze Medals |
| 158 | Col Silver Medals |
| 159 | Col Score Double |
| 160 | Col Num Laps |
| 161 | Col Objectives Passed |
| 162 | Col Mission Score |
| 163 | Col Hole 1 Shots |
| 164 | Col Hole 1 Putt |
| 165 | Col Hole 1 Drive |
| 166 | Col Num Shots Golf |
| 167 | Col Hole 2 Shots |
| 168 | Col Hole 2 Putt |
| 169 | Col Hole 2 Drive |
| 170 | Col Hole 3 Shots |
| 171 | Col Hole 3 Putt |
| 172 | Col Hole 3 Drive |
| 173 | Col Hole 4 Shots |
| 174 | Col Hole 4 Putt |
| 175 | Col Hole 4 Drive |
| 176 | Col Hole 5 Shots |
| 177 | Col Hole 5 Putt |
| 178 | Col Hole 5 Drive |
| 179 | Col Hole 6 Shots |
| 180 | Col Hole 6 Putt |
| 181 | Col Hole 6 Drive |
| 182 | Col Hole 7 Shots |
| 183 | Col Hole 7 Putt |
| 184 | Col Hole 7 Drive |
| 185 | Col Hole 8 Shots |
| 186 | Col Hole 8 Putt |
| 187 | Col Hole 8 Drive |
| 188 | Col Hole 9 Shots |
| 189 | Col Hole 9 Putt |
| 190 | Col Hole 9 Drive |
| 191 | Col Num Elk Killed |
| 192 | Col Num Heart Shots |
| 193 | Col Num Photo Text |
| 194 | Col H2H Wins |
| 195 | Col H2H Loses |
| 196 | Col Challenge Wins |
| 197 | Col Challenge Loses |
| 198 | Col Wins |
| 199 | Col Loses |
| 200 | Col Time Creating |
| 201 | Col Time Edit |
| 202 | Col Num Driven |
| 203 | Col Num Stolen |
| 204 | Col Dist Driven |
| 205 | Col Num Spins |
| 206 | Col Num Flips |
| 207 | Col Num Landings |
| 208 | Col Num Wheelies |
| 209 | Col Num Air Launches |
| 210 | Col Num Air Launches O5S |
| 211 | Col Num Air Launches O5M |
| 212 | Col Num Air Launches O40M |
| 213 | Col Num Large Accidents |
| 214 | Col Num Highest Speed |
| 215 | Col Longest Wheelie Time |
| 216 | Col Longest Wheelie Dist |
| 217 | Col Highest Jump Dist |
| 218 | Col Num Peds Rundown |
| 219 | Col Clocal Tests |
| 220 | Col Cnet Tests |
| 221 | Col Number Players |
| 222 | Score Column Game 1 |
| 223 | Score Column Game 2 |
| 224 | Score Column Game 3 |
| 225 | Score Column Game 4 |
| 226 | Score Column Game 5 |
| 227 | Score Column Game 6 |
| 228 | Score Column Game 7 |
| 229 | Score Column Game 8 |
| 231 | Score Column Game 9 |
| 232 | Score Column Game 10 |
| 233 | Score Column Game 11 |
| 234 | Score Column Game 12 |
| 235 | Score Column Game 13 |
| 236 | Score Column Game 14 |
| 237 | Score Column Game 15 |
| 238 | Score Column Game 16 |
| 239 | Total Time Elo Race |
| 240 | Freemode Arena Mode Score |
| 241 | Freemode Arena Mode Points |
| 242 | Count |
| 243 | Freemode Arena Mode Points2 |
| 244 | Freemode Arena Career Score |
| 245 | Freemode Arena Career Num Wins |
| 246 | Freemode Arena Career Num Matches |
| 247 | Freemode Arena Career Rank Id |
| 248 | Freemode Arena Career Vehicle Id |


## Parameters
* **fieldId**: Field ID of the column being set.
* **value_a**: 
* **value_b**: 

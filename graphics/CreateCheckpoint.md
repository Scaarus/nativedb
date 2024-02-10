---
ns: GRAPHICS
aliases: ["0x0134f0835ab6bfcb"]
---
## CREATE_CHECKPOINT

```c
// 0x0134F0835AB6BFCB
Checkpoint CREATE_CHECKPOINT(int CheckpointType, Vector3 scrVecPosition, Vector3 scrVecPointAt, float fSize, int colR, int colG, int colB, int colA, int num);
```

Creates a race checkpoint.

## CheckpointType Values:
| Value | Name |
| --- | --- |
| 0 | Race Ground Chevron 1 Base |
| 1 | Race Ground Chevron 2 Base |
| 2 | Race Ground Chevron 3 Base |
| 3 | Race Ground Lap Base |
| 4 | Race Ground Flag Base |
| 5 | Race Ground Pit Lane Base |
| 6 | Race Ground Chevron 1 |
| 7 | Race Ground Chevron 2 |
| 8 | Race Ground Chevron 3 |
| 9 | Race Ground Lap |
| 10 | Race Ground Flag |
| 11 | Race Ground Pit Lane |
| 12 | Race Air Chevron 1 |
| 13 | Race Air Chevron 2 |
| 14 | Race Air Chevron 3 |
| 15 | Race Air Lap |
| 16 | Race Air Flag |
| 17 | Race Water Chevron 1 |
| 18 | Race Water Chevron 2 |
| 19 | Race Water Chevron 3 |
| 20 | Race Water Lap |
| 21 | Race Water Flag |
| 22 | Race Tri Run Chevron 1 |
| 23 | Race Tri Run Chevron 2 |
| 24 | Race Tri Run Chevron 3 |
| 25 | Race Tri Run Lap |
| 26 | Race Tri Run Flag |
| 27 | Race Tri Swim Chevron 1 |
| 28 | Race Tri Swim Chevron 2 |
| 29 | Race Tri Swim Chevron 3 |
| 30 | Race Tri Swim Lap |
| 31 | Race Tri Swim Flag |
| 32 | Race Tri Cycle Chevron 1 |
| 33 | Race Tri Cycle Chevron 2 |
| 34 | Race Tri Cycle Chevron 3 |
| 35 | Race Tri Cycle Lap |
| 36 | Race Tri Cycle Flag |
| 37 | Plane Flat |
| 38 | Plane Side L |
| 39 | Plane Side R |
| 40 | Plane Inverted |
| 41 | Heli Landing |
| 42 | Parachute Ring |
| 43 | Parachute Landing |
| 44 | Gang Locate Lost |
| 45 | Gang Locate Vagos |
| 46 | Gang Locate Cops |
| 47 | Race Locate Ground |
| 48 | Race Locate Air |
| 49 | Race Locate Water |
| 50 | Mp Locate 1 |
| 51 | Mp Locate 2 |
| 52 | Mp Locate 3 |
| 53 | Mp Creator Trigger |
| 54 | Money |
| 55 | Beast |
| 56 | Transform |
| 57 | Transform Plane |
| 58 | Transform Helicopter |
| 59 | Transform Boat |
| 60 | Transform Car |
| 61 | Transform Bike |
| 62 | Transform Push Bike |
| 63 | Transform Truck |
| 64 | Transform Parachute |
| 65 | Transform Thruster |
| 66 | Warp |


If the checkpoint is a chevron then it will point towards scrVecPointAt. If it's a flag then scrVecPointAt will be ignored.


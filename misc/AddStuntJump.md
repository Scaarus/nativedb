---
ns: MISC
aliases: ["0x1a992da297a4630c"]
---
## ADD_STUNT_JUMP

```c
// 0x1A992DA297A4630C
int ADD_STUNT_JUMP(Vector3 startMax, Vector3 endMin, Vector3 endMax, Vector3 cameraPos, int Reward, int set, bool camOptional);
```

Adds a stunt jump area in the map.

The first two vector parameters define a box which will start the stunt jump. The 3rd and 4th vector parameters define a box which will complete the stunt jump (if the player enters that area within a few seconds) The camera will change to a fixed camera at the given position.


## Parameters
* **startMax**: 
* **endMin**: 
* **endMax**: 
* **cameraPos**: 
* **Reward**: is the amount of points the player receives if he lands in the end box
* **set**: is the set to add the stunt jump to. (eg 0 = singleplayer stuntjumps, 1 = multiplayer stuntjumps) By default only set 0 stunt jumps are enabled. This value can only be in the range 0 to 31
* **camOptional**: 

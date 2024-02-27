---
ns: OBJECT
aliases: ["0xc6033d32241f6fb5"]
---
## SET_OBJECT_IS_SPECIAL_GOLFBALL

```c
// 0xC6033D32241F6FB5
void SET_OBJECT_IS_SPECIAL_GOLFBALL(Object object, bool IsGolfBall);
```

Marks object as 'golf ball' - which causes it to run some alternate or extra physics to deal with the small scale (Particularly for rolling)

Currently pretty hacky and directly targeted at golf balls interacting at putting level velocities Ask code about this before using it (Robert Percival)


## Parameters
* **object**: 
* **IsGolfBall**: (Default value: `True`)

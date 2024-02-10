---
ns: OBJECT
aliases: ["0xf538081986e49e9d"]
---
## SET_FORCE_OBJECT_THIS_FRAME

```c
// 0xF538081986E49E9D
void SET_FORCE_OBJECT_THIS_FRAME(Vector3 pos, float radius);
```

call each frame to (a) prevent intersecting dynamic objects from reverting to dummy state and (b) promote intersecting dummy objects to real dynamic object state even if it is out of range

centre of sphere, radius of sphere

forces any dummy objects in the specified volume to become real dynamic objects


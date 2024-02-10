---
ns: WATER
aliases: ["0xfdbf4cdbc07e1706"]
---
## ADD_EXTRA_CALMING_QUAD

```c
// 0xFDBF4CDBC07E1706
int ADD_EXTRA_CALMING_QUAD(float minX, float minY, float maxX, float maxY, float dampening);
```

```
Add an extra calming quads, there's up to 8 in game, they're in world space, and axis aligned. dampening of 0.0f mean no water movements, 1.0f is full on.

return the index of the quad, usefull if you need to remove just that one. MAX allowed quads is 8. Let code know if that needs increasing
```

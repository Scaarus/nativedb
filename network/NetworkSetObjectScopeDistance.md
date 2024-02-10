---
ns: NETWORK
aliases: ["0xba7f0b77d80a4eb7"]
---
## NETWORK_SET_OBJECT_SCOPE_DISTANCE

```c
// 0xBA7F0B77D80A4EB7
void NETWORK_SET_OBJECT_SCOPE_DISTANCE(Object object, int distance);
```

Sets the scope distance for an object - this is the distance in metres from a remote player at which the object will get created on his machine. Passing in 0 will make the object revert to the default distance.


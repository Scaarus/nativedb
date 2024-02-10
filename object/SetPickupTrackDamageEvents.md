---
ns: OBJECT
aliases: ["0xbffe53ae7e67fcdc"]
---
## SET_PICKUP_TRACK_DAMAGE_EVENTS

```c
// 0xBFFE53AE7E67FCDC
void SET_PICKUP_TRACK_DAMAGE_EVENTS(Object object, bool set);
```

```
Forces the pickup to fully sync up with all players before it gets destroyed so all players will trigger their damage event correctly NOTE: Unset it before trying to delete the pickup via the DELETE_ENTITY function
```

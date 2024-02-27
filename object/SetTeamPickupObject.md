---
ns: OBJECT
aliases: ["0x53e0df1a2a3cf0ca"]
---
## SET_TEAM_PICKUP_OBJECT

```c
// 0x53E0DF1A2A3CF0CA
void SET_TEAM_PICKUP_OBJECT(int Team, bool Set);
```

Sets an ambient or portable pickup object collectable by the given team. Call this multiple times for all teams you want to permit.


## Parameters
* **Team**: 
* **Set**: if true then the given team is permitted to collect the object, if false the team is not allowed. You only need to call this with false if you have previously called it with true. (Default value: `True`)

---
ns: PATH
aliases: ["0x8415d95b194a3aea"]
---
## ARE_ALL_NAVMESH_REGIONS_LOADED

```c
// 0x8415D95B194A3AEA
bool ARE_ALL_NAVMESH_REGIONS_LOADED();
```

returns whether all the requested navmeshes have loaded.
This could be used at the start of a mission after the player ped has been teleported, as it may take a little time before the surrounding navmehes are streamed in. After the player has been teleported in, this command could be called repeatedly until it returns

This applies to the navmeshes which are always loaded in around the player, as well as any additional navmesh load regions which may have been set up.


---
ns: PLAYER
aliases: ["0x9097eb6d4bb9a12a"]
---
## ADD_PLAYER_TARGETABLE_ENTITY

```c
// 0x9097EB6D4BB9A12A
void ADD_PLAYER_TARGETABLE_ENTITY(Player player, Entity entity);
```

Allows script to specify specific targetable entities that wouldn't get picked up by the targeting search normally (ie for CObjects, as we don't iterate over them by default).
Can only register a MAXIMUM of 5 entities! Please contact Blair Trusler, Paulius Bernotas or David Hynd if you need this increased. This does not guarantee target will be locked-on to, normal validation will still be run (for example CObjects will still need to be flagged as targetable via SET_OBJECT_TARGETTABLE)


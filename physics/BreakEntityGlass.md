---
ns: PHYSICS
aliases: ["0x2e648d16f6e308f3"]
---
## BREAK_ENTITY_GLASS

```c
// 0x2E648D16F6E308F3
void BREAK_ENTITY_GLASS(Vector3 impactPosition, float impactRadius, Vector3 impulse, float damage, int crackType, bool silent);
```

```
on an entity with breakable glass, Breaks any glass panes at impactPosition, in a radius of impactRadius with impulse, damage amount, and using the passed crackType.

Use silent to avoid VFX, falling shards and audio
```

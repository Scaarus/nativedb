---
ns: MISC
aliases: ["0x9870acfb89a90995"]
---
## HAS_BULLET_IMPACTED_IN_AREA

```c
// 0x9870ACFB89A90995
bool HAS_BULLET_IMPACTED_IN_AREA(Vector3 Position, float Radius, bool IsPlayer, bool EntryOnly);
```

```
Finds a bullet impact in the defined sphere

bIsPlayer checks if the player fired the bullet. bEntryOnly=TRUE will only find entry impacts. =FALSE will find both entry and exit impacts
```

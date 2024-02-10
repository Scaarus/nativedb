---
ns: MISC
aliases: ["0xdc8c5d7cfeab8394"]
---
## HAS_BULLET_IMPACTED_IN_BOX

```c
// 0xDC8C5D7CFEAB8394
bool HAS_BULLET_IMPACTED_IN_BOX(Vector3 MinPosition, Vector3 MaxPosition, bool IsPlayer, bool EntryOnly);
```

Finds a bullet impact in the box

bIsPlayer checks if the player fired the bullet. bEntryOnly=TRUE will only find entry impacts. =FALSE will find both entry and exit impacts


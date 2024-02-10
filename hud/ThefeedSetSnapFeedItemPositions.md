---
ns: HUD
aliases: ["0xbae4f9b97cd43b30"]
---
## THEFEED_SET_SNAP_FEED_ITEM_POSITIONS

```c
// 0xBAE4F9B97CD43B30
void THEFEED_SET_SNAP_FEED_ITEM_POSITIONS(bool Set);
```

Flags if the feed should snap feed items (TRUE), or if it should animate (FALSE) into position This is currently only used for showing replay items on DPAD down (Because game speed is slowed down during this, animations run at a slower speed and we want these items to appear immediatey)


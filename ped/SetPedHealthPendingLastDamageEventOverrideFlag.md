---
ns: PED
aliases: ["0xb3352e018d6f89df"]
---
## SET_PED_HEALTH_PENDING_LAST_DAMAGE_EVENT_OVERRIDE_FLAG

```c
// 0xB3352E018D6F89DF
void SET_PED_HEALTH_PENDING_LAST_DAMAGE_EVENT_OVERRIDE_FLAG(bool OverrideValue);
```

Override to allow the pending last damage event flag to get reset without health being set to max. Used for game modes where players are respawned with less than full health which interferes with kill tracking. This should be reset back to false when it's no longer needed.


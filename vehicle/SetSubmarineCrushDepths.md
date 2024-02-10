---
ns: VEHICLE
aliases: ["0xc59872a5134879c7"]
---
## SET_SUBMARINE_CRUSH_DEPTHS

```c
// 0xC59872A5134879C7
void SET_SUBMARINE_CRUSH_DEPTHS(Vehicle vehicle, bool EnableCrushDamage, float VisibleDamageDepth, float AirLeakDepth, float CrushDepth);
```

```
All depths should be negative values.

Needs to be called every frame or it will be reset to the current global defaults.
```

## Parameters
* **vehicle**: 
* **EnableCrushDamage**: Whether or not to allow any crush damage effects.
* **VisibleDamageDepth**: below this depth the sub starts to look like it's being crushed but doesn't harm the player.
* **AirLeakDepth**: time spent below this depth will lead to air bubbles coming from the sub and the player starting to drown.
* **CrushDepth**: at this depth the sub will be wrecked and the occupants killed instantly.

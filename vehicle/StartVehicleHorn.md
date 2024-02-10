---
ns: VEHICLE
aliases: ["0x9c8c6504b5b63d2c"]
---
## START_VEHICLE_HORN

```c
// 0x9C8C6504B5B63D2C
void START_VEHICLE_HORN(Vehicle vehicle, int TimeToSoundHorn, int HornTypeHash, bool isMusicalHorn);
```

Sounds a vehicle horn for the given time and type. the type is the hash name, at the moment we only allow "NORMAL" and "HELDDOWN"


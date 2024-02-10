---
ns: NETWORK
aliases: ["0xe6717e652b8c8d8a"]
---
## NETWORK_ENABLE_EXTRA_VEHICLE_ORIENTATION_BLEND_CHECKS

```c
// 0xE6717E652B8C8D8A
void NETWORK_ENABLE_EXTRA_VEHICLE_ORIENTATION_BLEND_CHECKS(Network network, bool EnableExtraChecks);
```

Set a cloned network vehicle to perform extra validation checks when blending it's orientation based on network updates. This is useful for network modes where players are expected to crash into each other a lot (not races, rather specific modes that encourage crashing) to reduce physics popping issues ***** IMPORTANT NOTE - THIS IS AN EXPENSIVE FUNCTION - ONLY USE WHEN NECESSARY AND TURN OFF WHEN NOT REQUIRED ***************


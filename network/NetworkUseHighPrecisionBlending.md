---
ns: NETWORK
aliases: ["0x2b1813aba29016c5"]
---
## NETWORK_USE_HIGH_PRECISION_BLENDING

```c
// 0x2B1813ABA29016C5
void NETWORK_USE_HIGH_PRECISION_BLENDING(Network network, bool UseHighPrecision);
```

```
Sets whether to use high precision network blending for the specified network ID. Currently this can only be called on objects (not vehicles and peds). High precision blending is useful for small objects that need to be kept very tightly in sync for gameplay purposes (e.g. a golf ball in a golf mini-game)
```

## Parameters
* **network**: 
* **UseHighPrecision**: Flag indicating whether to use high precision or standard network blending

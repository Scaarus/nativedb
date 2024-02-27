---
ns: OBJECT
aliases: ["0x0589b5e791ce9b2b"]
---
## CREATE_MONEY_PICKUPS

```c
// 0x0589B5E791CE9B2B
void CREATE_MONEY_PICKUPS(Vector3 NewPosition, int Amount, int MaxNumPickups, Hash modelHash);
```

Creates a bunch of money pickups around the given coordinates, of the given amount


## Parameters
* **NewPosition**: the coordinates the money pickups will be generated round. Must be on or above the ground.
* **Amount**: the total amount of money dropped
* **MaxNumPickups**: the maximum number of money pickups created (no greater than 8)
* **modelHash**: (Default value: `0`)

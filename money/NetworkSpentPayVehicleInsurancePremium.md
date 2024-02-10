---
ns: MONEY
aliases: ["0x9ff28d88c766e3e8"]
---
## NETWORK_SPENT_PAY_VEHICLE_INSURANCE_PREMIUM

```c
// 0x9FF28D88C766E3E8
void NETWORK_SPENT_PAY_VEHICLE_INSURANCE_PREMIUM(int amount, int vehiclehash, gamer_handle handle, bool fromBank, bool fromBankAndWallet);
```

Player spent money in insurance claim. ONLY Set a valid Gamer handle if we are paying insurance for a remote player vehicle, ie, not our vehicle.


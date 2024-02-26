---
ns: MONEY
aliases: ["0xab3caa6b422164da"]
---
## NETWORK_CAN_SPEND_MONEY

```c
// 0xAB3CAA6B422164DA
bool NETWORK_CAN_SPEND_MONEY(int amount, bool fromBank, bool fromBankAndWallet, bool fromWalletAndBank, int character, bool evcOnly);
```

Call this command to make sure that the call to spend cash will succeedd.


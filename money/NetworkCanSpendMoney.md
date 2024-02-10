---
ns: MONEY
aliases: ["0xab3caa6b422164da"]
---
## NETWORK_CAN_SPEND_MONEY

```c
// 0xAB3CAA6B422164DA
bool NETWORK_CAN_SPEND_MONEY(int amount, bool fromBank, bool fromBankAndWallet, bool fromWalletAndBank, int character, bool evcOnly);
```

```
Call this command to make sure that the call to spend cash will succeedd.
```

## Parameters
* **amount**: cash amount must be > 0.
* **fromBank**: If TRUE take the money from the bank.
* **fromBankAndWallet**: If TRUE take the money from both Bank and Wallet, removing first from the Bank.
* **fromWalletAndBank**: If TRUE take the money from both Wallet and Bank, removing first from the Wallet.
* **character**: if the character is -1 it will use the current selected character.
* **evcOnly**: 

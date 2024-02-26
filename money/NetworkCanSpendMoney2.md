---
ns: MONEY
aliases: ["0x7303e27cc6532080"]
---
## NETWORK_CAN_SPEND_MONEY2

```c
// 0x7303E27CC6532080
bool NETWORK_CAN_SPEND_MONEY2(int amount, bool fromBank, bool fromBankAndWallet, bool fromWalletAndBank, int diff, int character, bool evcOnly);
```

Call this command to make sure that the call to spend cash will succeedd.


## Parameters
* **amount**: cash amount must be > 0.
* **fromBank**: If TRUE take the money from the bank.
* **fromBankAndWallet**: If TRUE take the money from both Bank and Wallet, removing first from the Bank.
* **fromWalletAndBank**: If TRUE take the money from both Wallet and Bank, removing first from the Wallet.
* **diff**: 
* **character**: if the character is -1 it will use the current selected character.
* **evcOnly**: 

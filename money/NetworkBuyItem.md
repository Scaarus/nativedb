---
ns: MONEY
aliases: ["0xf0077c797f66a355"]
---
## NETWORK_BUY_ITEM

```c
// 0xF0077C797F66A355
void NETWORK_BUY_ITEM(int amount, int itemhash, int type, int extra1, bool fromBank, string itemIdentifier, int shopNameHash, int extraItemHash, int colorHash, bool fromBankAndWallet);
```

```
Player bought something in a shop extra1 - client view of the current inventory. e.g. if buying bullets include how many bullets the client thinks he owns. itemIdentifier - extra item identifier, like PEGASUS.

Possible values for type:
| Index | Name |
| --- | --- |
| 35 |  |
```

---
ns: MISC
aliases: ["0xe80492a9ac099a93"]
---
## CLEAR_BIT

```c
// 0xE80492A9AC099A93
void CLEAR_BIT(int Variable, int BitIndex);
```

Clear the bit at the index (BitToClearIndex) of the integer (IntToModify) passed.

The index (BitToClearIndex) passed must be between 0 and 31 or the command will ASSERT.


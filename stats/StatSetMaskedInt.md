---
ns: STATS
aliases: ["0x7bbb1b54583ed410"]
---
## STAT_SET_MASKED_INT

```c
// 0x7BBB1B54583ED410
bool STAT_SET_MASKED_INT(int Hash, int data, int offSet, int numberOfBits, bool coderAssert);
```

Set masked element of a stat.


## Parameters
* **Hash**: 
* **data**: 
* **offSet**: number of bits counting from right were the value is going to be set.
* **numberOfBits**: number Of bits that should be changed. STAT_SET_MASKED_INT(statHash, statValue, 8, 8) would set the second byte in a stat
* **coderAssert**: (Default value: `True`)

---
ns: STATS
aliases: ["0x655185a06d9eeaab"]
---
## STAT_GET_MASKED_INT

```c
// 0x655185A06D9EEAAB
bool STAT_GET_MASKED_INT(int Hash, int offSet, int numberOfBits, int playerIndex);
```

Get masked element of a stat.


## Parameters
* **Hash**: 
* **offSet**: number of bits counting from right were the value is going to be set.
* **numberOfBits**: number Of bits that should be changed. eg STAT_GET_MASKED_INT(statHash, statValue, 8, 8) would get the second byte in a stat
* **playerIndex**: 

---
ns: STREAMING
aliases: ["0x07c313f94746702c"]
---
## STREAMVOL_IS_VALID

```c
// 0x07C313F94746702C
bool STREAMVOL_IS_VALID(int volumeIndex);
```

Returns true if the stream volume at the specified index is valid and active, false otherwise


## Parameters
* **volumeIndex**: the index returned from a previous call to STREAMVOL_CREATE

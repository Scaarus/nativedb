---
ns: STREAMING
aliases: ["0x7d41e9d2d17c5b2d"]
---
## STREAMVOL_HAS_LOADED

```c
// 0x7D41E9D2D17C5B2D
bool STREAMVOL_HAS_LOADED(int volumeIndex);
```

```
stream volumes attempt to fully satisfy requirements, but there are no guarantees in terms of memory availability etc.

Returns true if the stream volume at the specified index has been fulled satisfied, false otherwise.
```

## Parameters
* **volumeIndex**: the index returned from a previous call to STREAMVOL_CREATE

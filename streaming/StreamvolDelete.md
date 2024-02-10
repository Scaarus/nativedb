---
ns: STREAMING
aliases: ["0x1ee7d8df4425f053"]
---
## STREAMVOL_DELETE

```c
// 0x1EE7D8DF4425F053
void STREAMVOL_DELETE(int volumeIndex);
```

it is critical to remove a stream volume once it is no longer needed, as they have extremely high memory costs attached.

Destroys an existing stream volume which is no longer required.


## Parameters
* **volumeIndex**: the index returned from a previous call to STREAMVOL_CREATE

---
ns: SOCIALCLUB
aliases: ["0x1d4446a62d35b0d0"]
---
## SC_LICENSEPLATE_GET_PLATE

```c
// 0x1D4446A62D35B0D0
string SC_LICENSEPLATE_GET_PLATE(int token, int index);
```

get the current license plate at a given index retrieved for this token
Use SC_LICENSEPLATE_GET_CHECK_IS_PENDING() and wait for the request to finish.  Once it's finished, use SC_LICENSEPLATE_GET_COUNT() to get the count of license plates retrieved, then iterate using an index to get individual license plates.


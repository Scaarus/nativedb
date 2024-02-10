---
ns: SOCIALCLUB
aliases: ["0x2e89990ddff670c3"]
---
## SC_LICENSEPLATE_GET_PLATE_DATA

```c
// 0x2E89990DDFF670C3
string SC_LICENSEPLATE_GET_PLATE_DATA(int token, int index);
```

get the current license plate data at a given index retrieved for this token.
Use SC_LICENSEPLATE_GET_CHECK_IS_PENDING() and wait for the request to finish.  Once it's finished, use SC_LICENSEPLATE_GET_COUNT() to get the count of license plates retrieved, then iterate using an index to get individual license plates.


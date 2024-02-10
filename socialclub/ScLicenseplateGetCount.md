---
ns: SOCIALCLUB
aliases: ["0x700569dba175a77c"]
---
## SC_LICENSEPLATE_GET_COUNT

```c
// 0x700569DBA175A77C
int SC_LICENSEPLATE_GET_COUNT(int token);
```

get the current count of license plates retrieved for this token
Use SC_LICENSEPLATE_GET_CHECK_IS_PENDING() and wait for the request to finish.  Once it's finished, use SC_LICENSEPLATE_GET_COUNT() to get the count of license plates retrieved.


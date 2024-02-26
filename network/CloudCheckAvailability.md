---
ns: NETWORK
aliases: ["0x4f18196c8d38768d"]
---
## CLOUD_CHECK_AVAILABILITY

```c
// 0x4F18196C8D38768D
void CLOUD_CHECK_AVAILABILITY();
```

Use this to check if cloud is up This just requests a small cloud file but is behind a function so that we can swap out the functionality for something better if needed  CLOUD_GET_AVAILABILITY_CHECK_POSIX is the POSIX of when the check was last run. Will be 0 if never called.


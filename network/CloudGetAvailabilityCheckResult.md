---
ns: NETWORK
aliases: ["0x0b0cc10720653f3b"]
---
## CLOUD_GET_AVAILABILITY_CHECK_RESULT

```c
// 0x0B0CC10720653F3B
bool CLOUD_GET_AVAILABILITY_CHECK_RESULT();
```

Use this to check if cloud is up This just requests a small cloud file but is behind a function so that we can swap out the functionality for something better if needed CLOUD_GET_AVAILABILITY_CHECK_POSIX is the POSIX of when the check was last run. Will be 0 if never called.


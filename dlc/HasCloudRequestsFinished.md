---
ns: DLC
aliases: ["0x46e2b844905bc5f0"]
---
## HAS_CLOUD_REQUESTS_FINISHED

```c
// 0x46E2B844905BC5F0
bool HAS_CLOUD_REQUESTS_FINISHED(int uWaitDuration);
```

for the state of cloud data and compatibility pack configuration. PARAM NOTES : bTimedOut - this boolean is set to true if it keeps returning false for <uWaitDuration> PARAM NOTES : uWaitDuration - timeout duration in milliseconds. PARAM : Passing 0 as uWaitDuration will make it fall back to the value defined in the code (30 sec) NOTES : This function should be queried in a state and we should only leave that state when we time out or return true


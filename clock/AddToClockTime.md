---
ns: CLOCK
aliases: ["0xd716f30d8c8980e2"]
---
## ADD_TO_CLOCK_TIME

```c
// 0xD716F30D8C8980E2
void ADD_TO_CLOCK_TIME(int h, int m, int s);
```

adds the passed in time to the current time

can be negative and out of the normal range e.g. (22, 2, 1) - will add 22 hours 2 minutes and 1 second to the time (-22, 2, -1) - will take 22 hours and a second from the time and add 2 minute (100, 0, -200) - will add 100 hours to the time and subtract 200 seconds


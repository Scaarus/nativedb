---
ns: PLAYER
aliases: ["0x9a41cf4674a12272"]
---
## GET_CAUSE_OF_MOST_RECENT_FORCE_CLEANUP

```c
// 0x9A41CF4674A12272
int GET_CAUSE_OF_MOST_RECENT_FORCE_CLEANUP();
```

```
Returns the flag that caused force cleanup to trigger. It only makes sense to call this after HAS_FORCE_CLEANUP_OCCURRED has returned TRUE
```

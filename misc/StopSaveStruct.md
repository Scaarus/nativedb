---
ns: MISC
aliases: ["0xeb1774df12bb9f12"]
---
## STOP_SAVE_STRUCT

```c
// 0xEB1774DF12BB9F12
void STOP_SAVE_STRUCT();
```

More Info

Each START_SAVE_STRUCT should be matched by a STOP_SAVE_STRUCT after you have called REGISTER_..._TO_SAVE for each member variable that you want to save. You can save STRUCTs within STRUCTs.


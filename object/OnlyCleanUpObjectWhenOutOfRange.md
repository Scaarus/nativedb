---
ns: OBJECT
aliases: ["0xadbe4809f19f927a"]
---
## ONLY_CLEAN_UP_OBJECT_WHEN_OUT_OF_RANGE

```c
// 0xADBE4809F19F927A
void ONLY_CLEAN_UP_OBJECT_WHEN_OUT_OF_RANGE(Object object);
```

after releasing an object, only clean it up when it is out of drawing range

when script a releases an object, it gets cleaned up automatically when a timer expires and it goes off-screen. This command makes it only get cleaned up when it is far away from the player too.


---
ns: SOCIALCLUB
aliases: ["0x8a4416c0db05fa66"]
---
## SC_PAUSE_NEWS_GET_PENDING_STORY

```c
// 0x8A4416C0DB05FA66
bool SC_PAUSE_NEWS_GET_PENDING_STORY();
```

Retrieves pending story data. NOTE: Call this only once, and check return value before using data. WARNING: DO NOT STORE SC_NEWS_STORY_DATA! You should retrieve the data, and operate on it immediately.


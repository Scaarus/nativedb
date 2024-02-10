---
ns: SOCIALCLUB
aliases: ["0x487912fd248efddf"]
---
## SC_PRESENCE_SET_ACTIVITY_RATING

```c
// 0x487912FD248EFDDF
bool SC_PRESENCE_SET_ACTIVITY_RATING(int nActivityID, float fRating);
```

```
For setting a players skill rating at a particular activity
```

## Parameters
* **nActivityID**: ID from 0 to MAX_ACTIVITY_ID (giving MAX_ACTIVITY_ID + 1 distinct attributes)
* **fRating**: Player skill at activity from 0.0 (bad) to 1.0 (good)

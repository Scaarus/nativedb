---
ns: SOCIALCLUB
aliases: ["0x85535acf97fc0969"]
---
## SC_PROFANITY_GET_STRING_PASSED

```c
// 0x85535ACF97FC0969
bool SC_PROFANITY_GET_STRING_PASSED(int token);
```

check to see if the string submitted under the given token passed profanity check
Check IS_VALID(token) AND NOT IS_PENDING(token) before calling this to find whether is passed or fail


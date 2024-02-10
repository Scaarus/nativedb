---
ns: TASK
aliases: ["0xbd2a8ec3af4de7db"]
---
## TASK_USE_MOBILE_PHONE

```c
// 0xBD2A8EC3AF4DE7DB
void TASK_USE_MOBILE_PHONE(bool UsePhone, int PhoneMode);
```

Tells the ped to use a mobile phone.

## PhoneMode Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 279 | Tocall |
| 280 | Totext |
| 281 | Tocamera |
| 282 | Max |


when called with FALSE, this command cannot be used in a sequence. If you want to use this as part of an AI sequence, consider using TASK_USE_MOBILE_PHONE_TIMED.


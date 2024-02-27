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
| 1 | Tocall |
| 2 | Totext |
| 3 | Tocamera |


when called with FALSE, this command cannot be used in a sequence. If you want to use this as part of an AI sequence, consider using [`TASK_USE_MOBILE_PHONE_TIMED`](#_0x5EE02954A14C69DB).


## Parameters
* **UsePhone**: 
* **PhoneMode**: (Default value: `Tocall`)

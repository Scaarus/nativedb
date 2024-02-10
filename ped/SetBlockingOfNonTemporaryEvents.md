---
ns: PED
aliases: ["0x9f8aa94d6d97dbf4"]
---
## SET_BLOCKING_OF_NON_TEMPORARY_EVENTS

```c
// 0x9F8AA94D6D97DBF4
void SET_BLOCKING_OF_NON_TEMPORARY_EVENTS(bool BlockEvents);
```

```
Sets the blocking of non-temporary events.

The main use of this function is to prevent peds from reacting to interrupting events when you want them to be under script control. e.g. To tell a ped to run past a hated ped but ignoring the reaction to attack, set blocking to true at the start, then back to false once the task is completed.
```

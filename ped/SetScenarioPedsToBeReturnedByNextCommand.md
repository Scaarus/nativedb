---
ns: PED
aliases: ["0x14f19a8782c8071e"]
---
## SET_SCENARIO_PEDS_TO_BE_RETURNED_BY_NEXT_COMMAND

```c
// 0x14F19A8782C8071E
void SET_SCENARIO_PEDS_TO_BE_RETURNED_BY_NEXT_COMMAND(bool AllowScenarioPedsToBeGrabbed);
```

Call this with TRUE before [`GET_CLOSEST_PED`](#_0xC33AB876A77F8164) or [`GET_RANDOM_PED_AT_COORD`](#_0x876046A8E3A4B71C) if you want scenario peds to be checked too.


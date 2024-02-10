---
ns: MISC
aliases: ["0xa735353c77334ea0"]
---
## REGISTER_INT64_TO_SAVE

```c
// 0xA735353C77334EA0
void REGISTER_INT64_TO_SAVE(int IntToSave, string pLabel);
```

Registers a 64 bit integer variable for saving in the currently-open block

Label can be up to 63 characters. It can't be the same as a Label used by any other REGISTER_... command


---
ns: MISC
aliases: ["0xc8f4131414c835a1"]
---
## REGISTER_BOOL_TO_SAVE

```c
// 0xC8F4131414C835A1
void REGISTER_BOOL_TO_SAVE(bool BoolToSave, string pLabel);
```

Registers a bool variable for saving in the currently-open block

Label can be up to 63 characters. It can't be the same as a Label used by any other REGISTER_... command


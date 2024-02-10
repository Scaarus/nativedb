---
ns: MISC
aliases: ["0x34c9ee5986258415"]
---
## REGISTER_INT_TO_SAVE

```c
// 0x34C9EE5986258415
void REGISTER_INT_TO_SAVE(int IntToSave, string pLabel);
```

Registers an integer variable for saving in the currently-open block

Label can be up to 63 characters. It can't be the same as a Label used by any other REGISTER_... command


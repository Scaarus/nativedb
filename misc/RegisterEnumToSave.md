---
ns: MISC
aliases: ["0x10c2fa78d0e128a1"]
---
## REGISTER_ENUM_TO_SAVE

```c
// 0x10C2FA78D0E128A1
void REGISTER_ENUM_TO_SAVE(int EnumToSave, string pLabel);
```

Registers an enum variable for saving in the currently-open block

Label can be up to 63 characters. It can't be the same as a Label used by any other REGISTER_... command


---
ns: MISC
aliases: ["0xfaa457ef263e8763"]
---
## REGISTER_TEXT_LABEL_63_TO_SAVE

```c
// 0xFAA457EF263E8763
void REGISTER_TEXT_LABEL_63_TO_SAVE(Any* pTextLabelToSave, string pLabel);
```

Registers a text label variable for saving in the currently-open block

Label can be up to 63 characters. It can't be the same as a Label used by any other REGISTER_... command


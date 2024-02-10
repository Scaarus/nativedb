---
ns: MISC
aliases: ["0xedb1232c5beae62f"]
---
## REGISTER_TEXT_LABEL_TO_SAVE

```c
// 0xEDB1232C5BEAE62F
void REGISTER_TEXT_LABEL_TO_SAVE(text_label pTextLabelToSave, string pLabel);
```

Registers a text label variable for saving in the currently-open block

Label can be up to 63 characters. It can't be the same as a Label used by any other REGISTER_... command


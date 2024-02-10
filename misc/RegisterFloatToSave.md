---
ns: MISC
aliases: ["0x7caec29ecb5dfebb"]
---
## REGISTER_FLOAT_TO_SAVE

```c
// 0x7CAEC29ECB5DFEBB
void REGISTER_FLOAT_TO_SAVE(float FloatToSave, string pLabel);
```

Registers a float variable for saving in the currently-open block

Label can be up to 63 characters. It can't be the same as a Label used by any other REGISTER_... command


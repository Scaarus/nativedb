---
ns: PAD
aliases: ["0xe1615ec03b3bb4fd"]
---
## IS_MOUSE_LOOK_INVERTED

```c
// 0xE1615EC03B3BB4FD
bool IS_MOUSE_LOOK_INVERTED();
```

Checks if the mouse y look is inverted.

Will return false for platforms that do not support the mouse. This does not mean the player is playing with a mouse, they could be playing on a gamepad.


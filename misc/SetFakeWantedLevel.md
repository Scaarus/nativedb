---
ns: MISC
aliases: ["0x1454f2448de30163"]
---
## SET_FAKE_WANTED_LEVEL

```c
// 0x1454F2448DE30163
void SET_FAKE_WANTED_LEVEL();
```

Draws a fake number of wanted stars.

iWantedLevel is the amount of stars you wish to display on the HUD - NOTE this only shows the number of stars - it doesnt do anything with your 'real' wanted level or anything with any police. It will only work if the real wanted level is 0, otherwise the real wanted level will override it.


---
ns: GRAPHICS
aliases: ["0x7ac24eab6d74118d"]
---
## PHONEPHOTOEDITOR_TOGGLE

```c
// 0x7AC24EAB6D74118D
bool PHONEPHOTOEDITOR_TOGGLE(bool Enable);
```

Toggles support for custom border image and text for pictures taken with the in-game phone Returns FALSE (and asserts) only if trying to enable it when already enabled or when disabling it while already disabled. If necessary, use [PHONEPHOTOEDITOR_IS_ACTIVE](#_0xBCEDB009461DA156) to check


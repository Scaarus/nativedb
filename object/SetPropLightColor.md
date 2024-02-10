---
ns: OBJECT
aliases: ["0x5f048334b4a4e774"]
---
## SET_PROP_LIGHT_COLOR

```c
// 0x5F048334B4A4E774
bool SET_PROP_LIGHT_COLOR(Object object, bool enable, int red, int green, int blue);
```

```
If enable=TRUE, then overrides light color with (red,green,blue); If enable=FALSE, then disables color override (so light's original color is used) returns TRUE on success (light(s) attached to object were found and set to a new color), otherwise FALSE
```

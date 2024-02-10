---
ns: AUDIO
aliases: ["0x19f21e63ae6eae4e"]
---
## SET_USER_RADIO_CONTROL_ENABLED

```c
// 0x19F21E63AE6EAE4E
void SET_USER_RADIO_CONTROL_ENABLED(bool enabled);
```

```
Enables/disables user control over radio - retuning etc

Scripts can call this safely without worrying about conflicts with other scripts - calls can be nested, and if any system wants radio control disabled then it will be. This does mean that scripts must ensure they only call this function when their state changes, and not every frame
```

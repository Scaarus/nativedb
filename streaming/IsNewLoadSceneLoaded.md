---
ns: STREAMING
aliases: ["0x01b8247a7a8b9ad1"]
---
## IS_NEW_LOAD_SCENE_LOADED

```c
// 0x01B8247A7A8B9AD1
bool IS_NEW_LOAD_SCENE_LOADED();
```

returns true if the new load scene is active and fully loaded. may never return true if memory is under heavy load

check if a new load scene is fully loaded. this it never guaranteed to eventually return true


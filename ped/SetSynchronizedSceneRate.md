---
ns: PED
aliases: ["0xb6c49f8a5e295a5d"]
---
## SET_SYNCHRONIZED_SCENE_RATE

```c
// 0xB6C49F8A5E295A5D
void SET_SYNCHRONIZED_SCENE_RATE(float rate);
```

Changes the rate of an existing synchronized scene.

Use this command to change a synchronised scene's playback rate after it has been created. Changing the rate of a synced scene will update the playback speed of any objects attached to it.


## Parameters
* **rate**: The new rate of the scene (1.0 is normal rate)

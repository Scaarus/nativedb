---
ns: GRAPHICS
aliases: ["0x27feb5254759cde3"]
---
## PHONEPHOTOEDITOR_SET_FRAME_TXD

```c
// 0x27FEB5254759CDE3
bool PHONEPHOTOEDITOR_SET_FRAME_TXD(string nameOfLoadedTXDForFrame, bool justDisableCurrentFrame);
```

Sets the TXD containing the textures for the frame the system will use whenever the next photo is taken with the phone (if PHONEPHOTOEDITOR is active). The passed in TXD *must* be loaded; the PHONEPHOTOEDITOR will assert and fail (this function will return FALSE) otherwise. This command can also be used to get rid of the current frame without having to disable the PHONEPHOTOEDITOR: just call PHONEPHOTOEDITOR_SET_FRAME_TXD(NULL, TRUE)


## Parameters
* **nameOfLoadedTXDForFrame**: 
* **justDisableCurrentFrame**: (Default value: `False`)

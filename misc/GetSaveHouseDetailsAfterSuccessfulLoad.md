---
ns: MISC
aliases: ["0xa4a0065e39c9f25c"]
---
## GET_SAVE_HOUSE_DETAILS_AFTER_SUCCESSFUL_LOAD

```c
// 0xA4A0065E39C9F25C
bool GET_SAVE_HOUSE_DETAILS_AFTER_SUCCESSFUL_LOAD(Vector3 vecReturnCoords, float fReturnHeading, bool ReturnFadeIn, bool ReturnSnapToGround);
```

After a savegame has loaded, call this command to get the details of where the player should be spawned


## Parameters
* **vecReturnCoords**: the coordinates at which you should load the scene and spawn the player
* **fReturnHeading**: the heading you should give to the player
* **ReturnFadeIn**: you might never need this.
* **ReturnSnapToGround**: if the save happened while the player was in water or in the air then this will be FALSE

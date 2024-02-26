---
ns: GRAPHICS
aliases: ["0x7fa5d82b8f58ec06"]
---
## BEGIN_CREATE_MISSION_CREATOR_PHOTO_PREVIEW

```c
// 0x7FA5D82B8F58EC06
bool BEGIN_CREATE_MISSION_CREATOR_PHOTO_PREVIEW();
```

Creates a copy of a photo taken with [BEGIN_TAKE_MISSION_CREATOR_PHOTO](#_0x1DD2139A9A20DCE8) so that it can be referenced by Scaleform This command can only be called if BEGIN_TAKE_MISSION_CREATOR_PHOTO has successfully completed and hasn't been release; in other words, the valid time window to use this command is in between BEGIN_TAKE_MISSION_CREATOR_PHOTO and [FREE_MEMORY_FOR_MISSION_CREATOR_PHOTO](#_0x0A46AF8A78DC5E0A)


---
ns: TASK
aliases: ["0x621c6e4729388e41"]
---
## IS_PED_PLAYING_BASE_CLIP_IN_SCENARIO

```c
// 0x621C6E4729388E41
bool IS_PED_PLAYING_BASE_CLIP_IN_SCENARIO(Ped ped);
```

Returns TRUE if the ped has the USE_SCENARIO task and playing their base animation.

This is a slightly stronger check than [`IS_PED_ACTIVE_IN_SCENARIO`](#_0xAA135F9482C82CC3). The given ped will not be t-posing or in their low lod base.


---
ns: NETWORK
aliases: ["0x45f35c0edc33b03b"]
---
## NETWORK_ADD_MAP_ENTITY_TO_SYNCHRONISED_SCENE

```c
// 0x45F35C0EDC33B03B
void NETWORK_ADD_MAP_ENTITY_TO_SYNCHRONISED_SCENE(int NetworkSceneID, Hash modelHash, Vector3 ModelPosition, string animDictionary, string anim, float blendInDelta, float blendOutDelta, int flags);
```

```
Adds a map entity and associated animation data to a previous created network synchronised scene.

Possible values for flags:
| Index | Name |
| --- | --- |
| 0 | None |
| 1 | Use Physics |
| 2 | Tag Sync Out |
| 4 | Dont Interrupt |
| 8 | On Abort Stop Scene |
| 16 | Abort On Weapon Damage |
| 32 | Block Mover Update |
| 64 | Loop Within Scene |
| 128 | Preserve Velocity |
| 256 | Expand Ped Capsule From Skeleton |
| 512 | Activate Ragdoll On Collision |
| 1024 | Hide Weapon |
| 2048 | Abort On Death |
| 4096 | Vehicle Abort On Large Impact |
| 8192 | Vehicle Allow Player Entry |
| 16384 | Process Attachments On Start |
| 32768 | Net On Early Non Ped Stop Return To Start |
| 65536 | Set Ped Out Of Vehicle At Start |
| 131072 | Net Disregard Attachment Checks |
```

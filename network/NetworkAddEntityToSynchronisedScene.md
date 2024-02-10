---
ns: NETWORK
aliases: ["0xf2404d68cbc855fa"]
---
## NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE

```c
// 0xF2404D68CBC855FA
void NETWORK_ADD_ENTITY_TO_SYNCHRONISED_SCENE(Entity entity, int NetworkSceneID, string animDictionary, string anim, float blendInDelta, float blendOutDelta, int flags);
```

Adds a non-ped entity and associated animation data to a previous created network synchronised scene.

## flags Values:
| Value | Name |
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


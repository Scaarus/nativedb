---
ns: NETWORK
aliases: ["0xd0afaff5a51d72f7"]
---
## NETWORK_END_TUTORIAL_SESSION

```c
// 0xD0AFAFF5A51D72F7
void NETWORK_END_TUTORIAL_SESSION();
```

Ends a tutorial session previously began via a call to either [NETWORK_START_SOLO_TUTORIAL_SESSION](#_0x17E0198B3882C2CB)() or [NETWORK_ALLOW_GANG_TO_JOIN_TUTORIAL_SESSION](#_0xFB680D403909DC70)() The local player will be able to interact will all connected players again. Any locally controlled ambient population will be removed when this command is called, so ensure the player is placed where this will not be noticeable


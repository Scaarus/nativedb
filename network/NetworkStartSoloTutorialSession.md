---
ns: NETWORK
aliases: ["0x17e0198b3882c2cb"]
---
## NETWORK_START_SOLO_TUTORIAL_SESSION

```c
// 0x17E0198B3882C2CB
void NETWORK_START_SOLO_TUTORIAL_SESSION();
```

Puts the local player in a solo tutorial session - they will remain connected to other players in the session, but will be unable to interact with any of them. Any locally controlled ambient population will be removed when this command is called, so ensure the player is placed where this will not be noticeable


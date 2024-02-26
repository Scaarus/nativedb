---
ns: NETWORK
aliases: ["0xb37e4e6a2388ca7b"]
---
## NETWORK_WAITING_POP_CLEAR_TUTORIAL_SESSION

```c
// 0xB37E4E6A2388CA7B
bool NETWORK_WAITING_POP_CLEAR_TUTORIAL_SESSION();
```

Returns whether the local player is currently waiting for all remaining population to have been removed or a timer for this has timed out after tutorial transistion. Initially set true when [NETWORK_START_SOLO_TUTORIAL_SESSION](#_0x17E0198B3882C2CB)() or [NETWORK_ALLOW_GANG_TO_JOIN_TUTORIAL_SESSION](#_0xFB680D403909DC70)() or [NETWORK_END_TUTORIAL_SESSION](#_0xD0AFAFF5A51D72F7)() is called, and will only be set false some time after [NETWORK_IS_TUTORIAL_SESSION_CHANGE_PENDING](#_0x35F0B98A8387274D)() has completed and returned false. The criteria for being false will be if a timer has timed out or the all the population flagged for clearing has been cleared, whichever happens first.


---
ns: SAVEMIGRATION
aliases: ["0xe5e9746a66359f9d"]
---
## SAVEMIGRATION_MP_REQUEST_STATUS

```c
// 0xE5E9746A66359F9D
bool SAVEMIGRATION_MP_REQUEST_STATUS();
```

```
Request the status of the users save migration. Should be called by the game client before entering into multiplayer, on both gen8 and gen9 consoles, so that a user doesn't enter into MP while a transfer is in progress for them, as this would cause them to stomp on the changes being made, potentially corrupting the account.
```

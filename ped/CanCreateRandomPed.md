---
ns: PED
aliases: ["0x3e8349c08e4b82e4"]
---
## CAN_CREATE_RANDOM_PED

```c
// 0x3E8349C08E4B82E4
bool CAN_CREATE_RANDOM_PED(int Ped_model);
```

Call this before trying to create a ped with a random model, to ensure that a model is available

## Values for `Ped_model`:
| Value | Name |
| --- | --- |
| 0 | Dont Care |
| 1 | Male Ped |
| 2 | Female Ped |


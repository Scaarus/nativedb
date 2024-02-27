---
ns: AUDIO
aliases: ["0xbc9ae166038a5cec"]
---
## PLAY_PAIN

```c
// 0xBC9AE166038A5CEC
void PLAY_PAIN(Ped ped, int DamageReason, float RawDamage, bool SyncOverNetwork);
```

Plays a pain sound from the ped

## Values for `DamageReason`:
| Value | Name |
| --- | --- |
| 0 | Default |
| 1 | Falling |
| 2 | Super Falling |
| 3 | Scream Panic |
| 4 | Scream Panic Short |
| 5 | Scream Scared |
| 6 | Scream Shocked |
| 7 | Scream Terror |
| 8 | On Fire |
| 9 | Drowning |
| 10 | Surface Drowning (Drowning On The Surface Of Water, After We Time Out) |
| 11 | Inhale |
| 12 | Exhale |
| 13 | Post Fall Grunt |
| 14 | Entering Ragdoll Death |
| 15 | Explosion |
| 16 | Melee |
| 17 | Shove |
| 18 | Wheeze |
| 19 | Cough |
| 20 | Tazer |
| 21 | Exhaustion |
| 22 | Climb Large |
| 23 | Climb Small |
| 24 | Jump |
| 25 | Cower |
| 26 | Whimper |
| 27 | Dying Moan |
| 28 | Cycling Exhale |
| 29 | Pain Rapids |
| 30 | Sneeze |
| 31 | Melee Small Grunt |
| 32 | Melee Large Grunt |
| 33 | Post Fall Grunt Low |


## Parameters
* **ped**: 
* **DamageReason**: Reason for the Pain
* **RawDamage**: Damage value (usually won't be needed) (Default value: `0`)
* **SyncOverNetwork**: indicates whether this should automatically play on a locally controlled ped on remote machines (Default value: `False`)

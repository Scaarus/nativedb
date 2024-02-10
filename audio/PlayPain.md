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

## DamageReason Values:
| Value | Name |
| --- | --- |
| 81 | Default |
| 82 | Falling |
| 83 | Super Falling |
| 84 | Scream Panic |
| 85 | Scream Panic Short |
| 86 | Scream Scared |
| 87 | Scream Shocked |
| 88 | Scream Terror |
| 89 | On Fire |
| 90 | Drowning |
| 91 | Surface Drowning Drowning On The Surface Of Water, After We Time Out |
| 92 | Inhale |
| 93 | Exhale |
| 94 | Post Fall Grunt |
| 95 | Entering Ragdoll Death |
| 96 | Explosion |
| 97 | Melee |
| 98 | Shove |
| 99 | Wheeze |
| 100 | Cough |
| 101 | Tazer |
| 102 | Exhaustion |
| 103 | Climb Large |
| 104 | Climb Small |
| 105 | Jump |
| 106 | Cower |
| 107 | Whimper |
| 108 | Dying Moan |
| 109 | Cycling Exhale |
| 110 | Pain Rapids |
| 111 | Sneeze |
| 112 | Melee Small Grunt |
| 113 | Melee Large Grunt |
| 114 | Post Fall Grunt Low |


## Parameters
* **ped**: 
* **DamageReason**: Reason for the Pain
* **RawDamage**: Damage value (usually won't be needed)
* **SyncOverNetwork**: indicates whether this should automatically play on a locally controlled ped on remote machines

---
ns: CAMERA
aliases: ["0x80c8b1846639bb19"]
---
## SET_CAM_DEATH_FAIL_EFFECT_STATE

```c
// 0x80C8B1846639BB19
void SET_CAM_DEATH_FAIL_EFFECT_STATE(int State);
```

Pushes the death/fail camera effect through its states. You must ensure this is reset to CAM_DEATH_FAIL_EFFECT_INACTIVE once the sequence is complete.

## Values for `State`:
| Value | Name |
| --- | --- |
| 0 | Inactive |
| 1 | Intro |
| 2 | Outro |


## Parameters
* **State**: The desired state to apply. See the definition of CAM_DEATH_FAIL_EFFECT_STATE for a list of valid states.

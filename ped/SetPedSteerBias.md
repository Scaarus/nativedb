---
ns: PED
aliases: ["0x288df530c92dad6f"]
---
## SET_PED_STEER_BIAS

```c
// 0x288DF530C92DAD6F
void SET_PED_STEER_BIAS(Ped ped, float Bias);
```

Sets a ped control bias -1.0f (hard right) to 1.0f (hard left).

The steer bias value gets added to the players control input. The bias is in the range -1.0f (hard right) to 1.0f (hard left). Ie If you set the bias to 0.1 the ped will pull to the left a little bit. By modifying the value from frame to frame you can emulate buggered controls or somebody fighting over control of the ped.


---
ns: TASK
aliases: ["0x8634cef2522d987b"]
---
## SET_TASK_MOVE_NETWORK_SIGNAL_FLOAT_LERP_RATE

```c
// 0x8634CEF2522D987B
void SET_TASK_MOVE_NETWORK_SIGNAL_FLOAT_LERP_RATE(Ped ped, string signalName, float fLerpRate);
```

Sets the lerp rate to the passed value - Lerp rate controls rate at which the corresponding MoVE float signal will lerp over frame updates on the clone from the current value to the target value. It is assumed that the corresponding MoVE float signal has already been created using [`SET_TASK_MOVE_NETWORK_SIGNAL_FLOAT`](#_0xD5BB4025AE449A4E) command. Currently the lerp rate defaults to a value of 0.5f. The lerp value has to be above 0.0f and below 1.0f. If a lerp rate of 1.0f is applied then no lerping is used and the exact float value will be synced and applied immediately on the clone.


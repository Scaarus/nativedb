---
ns: SOCIALCLUB
aliases: ["0x225798743970412b"]
---
## SC_ACHIEVEMENT_INFO_STATUS

```c
// 0x225798743970412B
bool SC_ACHIEVEMENT_INFO_STATUS(int status);
```

Retrieve status about social club achievement availability.

(status == -1) - INVALID status request to read achievements has not even started. (status == 0) - Read SUCCEEDED information is available. (status == 1) - Read is PENDING, in progress. (status == 2) - Read FAILED. (status == 3) - Read CANCELED. If the Status is FAILEDCANCELED you can call SC_ACHIEVEMENT_SYNCHRONIZE once to restart everything but make sure the player is online and has ROS credentials.


---
ns: TASK
aliases: ["0x244f70c84c547d2d"]
---
## WAYPOINT_PLAYBACK_RESUME

```c
// 0x244F70C84C547D2D
void WAYPOINT_PLAYBACK_RESUME(Ped ped, bool AchieveHeadingFirst, int iProgressToContinueFrom, int iTimeBeforeResumingMs);
```

```
Resumes the playback of a waypoint-recording on the specified ped. bAchieveHeadingFirst : Optionally allows the ped to turn towards their next waypoint before starting to move (can help avoid navigation problems in tight spaces) iProgressToContinueFrom : Optionally allows you to specify which route point to continue from (use -1 to continue from current position) iTimeBeforeResumingMs : Optionally specifies a delay in millisecs, before the ped resumes their route following
```

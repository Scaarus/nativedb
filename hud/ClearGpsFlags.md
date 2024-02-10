---
ns: HUD
aliases: ["0x21986729d6a3a830"]
---
## CLEAR_GPS_FLAGS

```c
// 0x21986729D6A3A830
void CLEAR_GPS_FLAGS();
```

```
Clears the GPS flags previously set by this script. It is a requirement to call this from any script which has previously called SET_GPS_FLAGS, prior to any other script setting the GPS flags. Alternatively when your script terminates it will automatically call CLEAR_GPS_FLAGS if necessary.
```

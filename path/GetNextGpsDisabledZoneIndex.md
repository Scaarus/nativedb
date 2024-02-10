---
ns: PATH
aliases: ["0xd3a6a0ef48823a8c"]
---
## GET_NEXT_GPS_DISABLED_ZONE_INDEX

```c
// 0xD3A6A0EF48823A8C
int GET_NEXT_GPS_DISABLED_ZONE_INDEX();
```

```
Used to return an index to a free slot for defining a gps disabled zone
Currently only 4 slots are available for use. Will return index 0 -> 3 or -1 if all slots are full

Returns an int which is the next available slot for defining a gps disabled zone
```

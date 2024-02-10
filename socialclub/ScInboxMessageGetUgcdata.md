---
ns: SOCIALCLUB
aliases: ["0x69d82604a1a5a254"]
---
## SC_INBOX_MESSAGE_GET_UGCDATA

```c
// 0x69D82604A1A5A254
bool SC_INBOX_MESSAGE_GET_UGCDATA(int index, ugcstateupdate_data out_data);
```

For UGCStatUpdate messages, get the data associated with that message


## Parameters
* **index**: index of the Inbox message to get the data off of. It should be of type UGCStatUpdate
* **out_data**: struct that will be filled with the data of the message

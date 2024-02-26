---
ns: NETWORK
aliases: ["0xc32ea7a2f6ca7557"]
---
## NETWORK_CLAN_HAS_CREWINFO_METADATA_BEEN_RECEIVED

```c
// 0xC32EA7A2F6CA7557
bool NETWORK_CLAN_HAS_CREWINFO_METADATA_BEEN_RECEIVED();
```

Returns true if the metadata and crewinfo requests have been finished successfully

Because teh metadata and the crew info for crews aren't always complete, just because this function returns true, it doesn't mean that the data you're asking for it there. It may not be included in the crew info. Rely on the return values of the request functions to be sure.


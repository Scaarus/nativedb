---
ns: DATAFILE
aliases: ["0xa5efc3e847d60507"]
---
## UGC_CREATE_MISSION

```c
// 0xA5EFC3E847D60507
bool UGC_CREATE_MISSION(string szDisplayName, Any* szDesc, Any* szTags, string szContentType, bool Publish, int datafileIndex);
```

Create a UGC mission - build the UGC header using datafile commands before calling this. Sideline that using [`DATAFILE_STORE_MISSION_HEADER`](#_0x2ED61456317B8178). And then build the mission data using the datafile commands szDisplayName - Front facing content name ("My Awesome Mission!") szDesc - Description of this mission ("Are you a bad enough dude to rescue the President?") szTags - Comma separated tags to describe searchable tags nType - Of type UGC_TYPE bPublish - Publish this mission on creation (push to Rockstar candidate)


## Parameters
* **szDisplayName**: 
* **szDesc**: 
* **szTags**: 
* **szContentType**: 
* **Publish**: 
* **datafileIndex**: (Default value: `0`)

---
ns: DATAFILE
aliases: ["0x4645de9980999e93"]
---
## UGC_UPDATE_MISSION

```c
// 0x4645DE9980999E93
bool UGC_UPDATE_MISSION(string szContentID, string szDisplayName, ugc_description szDesc, ugc_description szTags, string szContentType, int datafileIndex);
```

Update a UGC file - (optionally) build an updated UGC header using datafile commands before calling this. The parameters are all optional. Pass in NULL for any that should not be updated.


## Parameters
* **szContentID**: UGC content ID
* **szDisplayName**: Front facing content name ("My Awesome Mission!")
* **szDesc**: Description of this mission ("Are you a bad enough dude to rescue the President?")
* **szTags**: Comma separated tags to describe searchable tags
* **szContentType**: 
* **datafileIndex**: Datafile slot containing the data you want to save

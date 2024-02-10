---
ns: DATAFILE
aliases: ["0x648e7a5434af7969"]
---
## UGC_UPDATE_CONTENT

```c
// 0x648E7A5434AF7969
bool UGC_UPDATE_CONTENT(string szContentID, int nFiles, string szDisplayName, ugc_description szDesc, ugc_description szTags, string szContentType, int datafileIndex);
```

Update a UGC file - (optionally) build an updated UGC header using datafile commands before calling this. The parameters are all optional. Pass in NULL for any that should not be updated.


## Parameters
* **szContentID**: UGC content ID
* **nFiles**: How many files are in the array
* **szDisplayName**: Front facing content name ("My Awesome Mission!")
* **szDesc**: Description of this mission ("Are you a bad enough dude to rescue the President?")
* **szTags**: Comma separated tags to describe searchable tags
* **szContentType**: 
* **datafileIndex**: Datafile slot containing the data you want to save

---
ns: DATAFILE
aliases: ["0xc84527e235fca219"]
---
## UGC_CREATE_CONTENT

```c
// 0xC84527E235FCA219
bool UGC_CREATE_CONTENT(int nFiles, string szDisplayName, string szContentType, bool Publish, int datafileIndex);
```

Create a UGC file - build the UGC header using datafile commands before calling this. szFilePaths - Array of file paths nFiles - How many files are in the array szDisplayName - Front facing content name ("My Awesome Mission!") szDesc - Description of this mission ("Are you a bad enough dude to rescue the President?") szTags - Comma separated tags to describe searchable tags nType - Of type UGC_TYPE bPublish - Publish this mission on creation (push to Rockstar candidate)


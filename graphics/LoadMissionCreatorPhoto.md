---
ns: GRAPHICS
aliases: ["0x4862437a486f91b0"]
---
## LOAD_MISSION_CREATOR_PHOTO

```c
// 0x4862437A486F91B0
bool LOAD_MISSION_CREATOR_PHOTO(string szContentID, int nFileID, int nFileVersion, int nLanguage);
```

```
Instead of taking a new photo using BEGIN_TAKE_MISSION_CREATOR_PHOTO, you can load the photo for an existing mission using this command Once GET_STATUS_OF_LOAD_MISSION_CREATOR_PHOTO has returned PHOTO_OPERATION_SUCCEEDED, you can save the photo to the cloud with a new name using SAVE_MISSION_CREATOR_PHOTO Once you're finished with the photo, call FREE_MEMORY_FOR_MISSION_CREATOR_PHOTO

Path and filename to the existing photo on the cloud. The filename should be the unique Id of the UGC content for the existing mission.
```

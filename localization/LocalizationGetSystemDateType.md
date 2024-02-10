---
ns: LOCALIZATION
aliases: ["0xa8ae43aec1a61314"]
---
## LOCALIZATION_GET_SYSTEM_DATE_TYPE

```c
// 0xA8AE43AEC1A61314
date_format LOCALIZATION_GET_SYSTEM_DATE_TYPE();
```

```
Used to check the language/region date formatting of the system

Possible return values:
| Index | Name |
| --- | --- |
| 0 | DATE_FORMAT_DMY |
| 13 | DATE_FORMAT_MDY |
| 14 | DATE_FORMAT_YMD |
| 15 | MAX_DATE_FORMATS |


Returns the current system date formatting type
```

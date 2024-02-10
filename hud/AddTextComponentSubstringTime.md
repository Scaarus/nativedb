---
ns: HUD
aliases: ["0x1115f16b8ab9e8bf"]
---
## ADD_TEXT_COMPONENT_SUBSTRING_TIME

```c
// 0x1115F16B8AB9E8BF
void ADD_TEXT_COMPONENT_SUBSTRING_TIME(int TimeInMillseconds, int TimeFormat);
```

```
Takes a time in milliseconds and converts it to a string. Use ~a~ to mark the position in your line of text where you want this substring inserted

Possible values for TimeFormat:
| Index | Name |
| --- | --- |
| 1 | Ime Format Milliseconds |
| 2 | Ime Format Seconds |
| 4 | Ime Format Minutes |
| 8 | Ime Format Hours |
| 16 | Ime Format Days |
| 32 | Ext Format Hide Leading Units Equal To Zero |
| 64 | Ext Format Hide Leading Zeros On Leading Units |
| 128 | Ext Format Show Unit Dividers As Letters |
| 256 | Ext Format Hide Unit Letter For Smallest Units |
| 512 | Ext Format Hide Milliseconds Units Digit |
| 1024 | Ext Format Hide Milliseconds Tens Digit |
| 2048 | Ext Format Use Dot For Millisecond Divider |
```

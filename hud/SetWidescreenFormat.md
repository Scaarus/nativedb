---
ns: HUD
aliases: ["0xc3b07ba00a83b0f1"]
---
## SET_WIDESCREEN_FORMAT

```c
// 0xC3B07BA00A83B0F1
void SET_WIDESCREEN_FORMAT(int WidescreenSetting);
```

sets the script widescreen format

## WidescreenSetting Values:
| Value | Name |
| --- | --- |
| 0 | Auto          // 4:3 & Automatically Decide Where Based On Original Screen Position - Left If Pos = < 0.5, Right If Pos = > 0.5 And Centre If Pos |
| 859 | Centre Keep 4:3 Perspective Centred In 16:9 |
| 860 | Left Keep 4:3 Perspective But Align To The Left In 16:9 |
| 861 | Right Keep 4:3 Perspective But Align To The Right In 16:9 |


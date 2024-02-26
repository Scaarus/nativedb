---
ns: AUDIO
aliases: ["0xc5ef963405593646"]
---
## ADD_LINE_TO_CONVERSATION

```c
// 0xC5EF963405593646
void ADD_LINE_TO_CONVERSATION(int SpeakerNumber, string Context, string Subtitle, int ListenerNumber, int volumeType, bool isRandom, bool ducksRadio, bool ducksScore, int audibility, bool dontInterruptForSpecialAbility, bool isPadSpeakerRoute);
```

Please keep all NATIVE definitions to a single line of code, to simplify some extra processing we need to do.

## audibility Values:
| Value | Name |
| --- | --- |
| 0 | Normal |
| 1 | Clear |
| 2 | Critical |
| 3 | Lead In |


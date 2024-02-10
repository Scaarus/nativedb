---
ns: HUD
aliases: ["0xb2798643312205c5"]
---
## GET_CHARACTER_FROM_AUDIO_CONVERSATION_FILENAME_WITH_BYTE_LIMIT

```c
// 0xB2798643312205C5
string GET_CHARACTER_FROM_AUDIO_CONVERSATION_FILENAME_WITH_BYTE_LIMIT(string pText, int startCharacter, int endCharacter, int maxBytesToCopy);
```

Does the same as GET_CHARACTER_FROM_AUDIO_CONVERSATION_FILENAME. Copies characters, but will stop when maxBytesToCopy is reached. If that would cause only half of a two-byte character to be copied then neither byte is copied.


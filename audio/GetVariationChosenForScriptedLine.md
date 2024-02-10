---
ns: AUDIO
aliases: ["0xaa19f5572c38b564"]
---
## GET_VARIATION_CHOSEN_FOR_SCRIPTED_LINE

```c
// 0xAA19F5572C38B564
int GET_VARIATION_CHOSEN_FOR_SCRIPTED_LINE(string TextLabel);
```

```
Returns the variation chosen for a given scripte speech line. Returns 0 if it hasn't been chosen yet. Returns -1 if there is no conversation active or if the active conversation doesn't contain this line or if the text label can't be found in the currently loaded text blocks
```

## Parameters
* **TextLabel**: all the text labels for filenames in AmericanDialogueFiles.txt appear to end with the letter 'A' It is the script's responsibility to add this 'A' before calling GET_VARIATION_CHOSEN_FOR_SCRIPTED_LINE

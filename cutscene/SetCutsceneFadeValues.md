---
ns: CUTSCENE
aliases: ["0x8093f23abaccc7d4"]
---
## SET_CUTSCENE_FADE_VALUES

```c
// 0x8093F23ABACCC7D4
void SET_CUTSCENE_FADE_VALUES(bool fadeOutAtStart, bool fadeInAtStart, bool fadeOutAtEnd, bool fadeInAtEnd);
```

Sets the fade values for the command, WARNING: Using this command will change the behaviour of the skip fades, so only call it of you NEED to override fade values.

Please note calling this command will affect the behaviour when skipping. If you call this you will have to make sure that the cutscene fades in at the end for both a skip and non skip, irrespective of any of the values you have set.


## Parameters
* **fadeOutAtStart**: (Default value: `False`)
* **fadeInAtStart**: (Default value: `False`)
* **fadeOutAtEnd**: (Default value: `False`)
* **fadeInAtEnd**: (Default value: `False`)

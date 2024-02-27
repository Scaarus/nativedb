---
ns: CUTSCENE
aliases: ["0x20746f7b1032a3c7"]
---
## SET_CUTSCENE_MULTIHEAD_FADE

```c
// 0x20746F7B1032A3C7
void SET_CUTSCENE_MULTIHEAD_FADE(bool FadeIn, bool Instant, bool Manual, bool FullscreenMovie);
```

Sets the multihead board sides to emulate cutscene style multihead fades to cover up for problems with animations outside of widescreen areas.


## Parameters
* **FadeIn**: Mark if fading in or out.
* **Instant**: Put up blinders right away, no slide in.
* **Manual**: Set to ture if you are taking responsability for turning off the blinders
* **FullscreenMovie**: (Default value: `False`)

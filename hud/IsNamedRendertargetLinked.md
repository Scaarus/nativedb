---
ns: HUD
aliases: ["0x113750538fa31298"]
---
## IS_NAMED_RENDERTARGET_LINKED

```c
// 0x113750538FA31298
bool IS_NAMED_RENDERTARGET_LINKED(Hash modelHash);
```

Return true if a named render tatget has been linked. Use after calling [`LINK_NAMED_RENDERTARGET`](#_0xF6C09E276AEB3F2D) to make sure the render target could be linked to the model. If this function returns false, script should release the render target


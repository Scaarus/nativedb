---
ns: STREAMING
aliases: ["0x95a7dabddbb78ae7"]
---
## IPL_GROUP_SWAP_START

```c
// 0x95A7DABDDBB78AE7
void IPL_GROUP_SWAP_START(string iplGroupBefore, string iplGroupAfter);
```

allows user to pre-stream the end state IPL group. once it is ready the swap can be performed. Once a swap has been started, it must either be cancelled or finished to release the streaming resources.

iplGroupBefore is the currently enabled IPL group, and iplGroupAfter is the desired end state IPL group

starts pre-streaming for a seamless swap from first IPL group to second


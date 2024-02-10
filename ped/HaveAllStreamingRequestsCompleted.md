---
ns: PED
aliases: ["0x7350823473013c02"]
---
## HAVE_ALL_STREAMING_REQUESTS_COMPLETED

```c
// 0x7350823473013C02
bool HAVE_ALL_STREAMING_REQUESTS_COMPLETED(Ped ped);
```

Returns true if all streaming requests on a ped have completed. More...

When a new variation is set on a streamed ped this function can be called right after and returns true when all components have loaded and the ped is ready for render.


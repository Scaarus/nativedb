---
ns: SCRIPT
aliases: ["0x30b4fa1c82dd4b9f"]
---
## SCRIPT_THREAD_ITERATOR_GET_NEXT_THREAD_ID

```c
// 0x30B4FA1C82DD4B9F
int SCRIPT_THREAD_ITERATOR_GET_NEXT_THREAD_ID();
```

Returns the Thread Id of the next valid script and then moves the array index on to the next entry ready for the next call to this command. Returns NULL when the end of the array is reached


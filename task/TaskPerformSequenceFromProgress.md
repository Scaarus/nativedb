---
ns: TASK
aliases: ["0x89221b16730234f0"]
---
## TASK_PERFORM_SEQUENCE_FROM_PROGRESS

```c
// 0x89221B16730234F0
void TASK_PERFORM_SEQUENCE_FROM_PROGRESS(Sequence sequence, int Progress1, int Progress2);
```

```
Performs a sequence except that the ped will skip the elements of the sequence in the range (0 to Progress1 ).

Peds start the sequence at the Progress1’th element. If the Progress1’th element of the sequence is also a sequence it will start at the Progress2’th element.
```

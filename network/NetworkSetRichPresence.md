---
ns: NETWORK
aliases: ["0x1dccacdcfc569362"]
---
## NETWORK_SET_RICH_PRESENCE

```c
// 0x1DCCACDCFC569362
void NETWORK_SET_RICH_PRESENCE(int id, struct data, int sizeOfData, int numFields);
```

Sets a rich presence in xbox

## id Values:
| Value | Name |
| --- | --- |
| 0 | Pres 0 |
| 1 | Pres 1 |
| 2 | Pres 2 |
| 3 | Pres 3 |
| 4 | Pres 4 |
| 5 | Pres 5 |
| 6 | Pres 6 |
| 7 | Pres 7 |
| 8 | Pres 8 |
| 9 | Pres 9 |
| 10 | Pres 10 |
| 11 | Count |


## Parameters
* **id**: rich presence id.
* **data**: struct with all presence fields.
* **sizeOfData**: sizeof Struct.
* **numFields**: number of fields in the struct.

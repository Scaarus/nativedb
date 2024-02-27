---
ns: NETWORK
aliases: ["0x1dccacdcfc569362"]
---
## NETWORK_SET_RICH_PRESENCE

```c
// 0x1DCCACDCFC569362
void NETWORK_SET_RICH_PRESENCE(int id, Any* data, int sizeOfData, int numFields);
```

Sets a rich presence in xbox

ALL FIELDS HAVE TO BE INTS EXAMPLE: Declare a structure that represents a rich presence: STRUCT STRUCT_INVITE_EVENT INT field_0 INT field_1 ENDSTRUCT Use the struct as you which: STRUCT_INVITE_EVENT presence_0 presence_0.field_0 = 10 presence_0.field_1 = 11 Set the rich presence: NETWORK_SET_RICH_PRESENCE(0, presence_0, sizeof(presence_0), 2) On 360 you set only the presence id and the values for the fields in case the presence has fields, for instance, setting the presence Playing Mission A is set by specifying the presence id and the index of the mission A.

## Values for `id`:
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

---
ns: SHAPETEST
aliases: ["0x65287525d951f6be"]
---
## GET_SHAPE_TEST_RESULT_INCLUDING_MATERIAL

```c
// 0x65287525D951F6BE
shapetest_status GET_SHAPE_TEST_RESULT_INCLUDING_MATERIAL(Shapetest shapetest);
```

If status returned is SHAPETEST_STATUS_RESULTS_READY, then returns whether something was hit, and if so nearest hit pos, normal and a hash of the material name which can be tested against the enums defined in material_enums.sch. NOTES: The shapetest request is destroyed by this call if SHAPETEST_STATUS_RESULTS_READY is returned. If this is not called every frame then the request will be destroyed.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Nonexistent |
| 1 | Results Notready Not Ready Yet; Try Again Next Frame |
| 2 | Results Ready The Result Is Ready And The Results Have Been Returned To You. The Shapetest Request Has Also Just Been Destroyed |


---
ns: SHAPETEST
aliases: ["0x3d87450e15d98694"]
---
## GET_SHAPE_TEST_RESULT

```c
// 0x3D87450E15D98694
shapetest_status GET_SHAPE_TEST_RESULT(Shapetest shapetest);
```

If status returned is SHAPETEST_STATUS_RESULTS_READY, then returns whether something was hit, and if so nearest hit pos and normal NOTES: The shapetest request is destroyed by this call if SHAPETEST_STATUS_RESULTS_READY is returned. If this is not called every frame then the request will be destroyed

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Nonexistent |
| 1 | Results Notready Not Ready Yet; Try Again Next Frame |
| 2 | Results Ready The Result Is Ready And The Results Have Been Returned To You. The Shapetest Request Has Also Just Been Destroyed |


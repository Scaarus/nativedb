---
ns: SHAPETEST
aliases: ["0x65287525d951f6be"]
---
## GET_SHAPE_TEST_RESULT_INCLUDING_MATERIAL

```c
// 0x65287525D951F6BE
shapetest_status GET_SHAPE_TEST_RESULT_INCLUDING_MATERIAL(Shapetest shapetest, int bHitSomething, Vector3 vPs, Vector3 vNormal, int material, Entity entity);
```

If status returned is SHAPETEST_STATUS_RESULTS_READY, then returns whether something was hit, and if so nearest hit pos, normal and a hash of the material name which can be tested against the enums defined in material_enums.sch.
The shapetest request is destroyed by this call if SHAPETEST_STATUS_RESULTS_READY is returned. If this is not called every frame then the request will be destroyed.

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Nonexistent |
| 1 | Results Notready Not Ready Yet; Try Again Next Frame |
| 2 | Results Ready The Result Is Ready And The Results Have Been Returned To You. The Shapetest Request Has Also Just Been Destroyed |


## material Values:
| Value | Name |
| --- | --- |
| -2098049209 | TENNIS_FENCE_3 |
| -2073312001 | GOLF_MISC |
| -2041329971 | GOLF_SOFT_VEG |
| -1937569590 | GENERAL_SNOW_LOOSE |
| -1915425863 | GOLF_HARD_VEG4 |
| -1885547121 | GOLF_DIRT_TRACK |
| -1625995479 | TENNIS_BLEACHERS_SEATS |
| -1595148316 | GOLF_BUNKER |
| -1447280105 | GOLF_FENCE_1 |
| -1286696947 | GOLF_GREEN |
| -878560889 | GENERAL_SNOW_COMPACT |
| -840216541 | GOLF_ROCKS |
| -642658848 | TENNIS_INNER_WALLS |
| -461750719 | GOLF_ROUGH |
| -365631240 | TENNIS_BLEACHERS_FLOOR |
| -309121453 | GOLF_HARD_VEG1 |
| -145735917 | TENNIS_TURF_2 |
| 0 | INVALID_MATERIAL |
| 122789469 | TENNIS_NET |
| 125958708 | TENNIS_FENCE_6 |
| 233925547 | TENNIS_FENCE_2 |
| 282940568 | GOLF_PATH2 |
| 435688960 | GOLF_WATER_HAZARD |
| 450003561 | TENNIS_FENCE_4 |
| 510490462 | GOLF_SAND |
| 555004797 | GOLF_HARD_VEG2 |
| 581794674 | GOLF_HARD_VEG3 |
| 592446772 | TENNIS_TURF_3 |
| 627123000 | GOLF_FLAG_POLE |
| 669292054 | TENNIS_TURF_4 |
| 762193613 | GOLF_FENCE_2 |
| 930824497 | GOLF_ROUGH2 |
| 951832588 | GOLF_CART_PATH |
| 1144315879 | TENNIS_TURF_5 |
| 1187676648 | GOLF_PATH1 |
| 1333033863 | GOLF_FAIRWAY |
| 1394765188 | TENNIS_FENCE_5 |
| 1550304810 | GENERAL_SNOW_TARMAC |
| 1619704960 | GENERAL_SNOW_DEEP |
| 1849540536 | TENNIS_BLEACHERS_SEATS_2 |
| 1907048430 | TENNIS_TURF |
| 1925605558 | TRAIN_TRACKS_GRAVEL |
| 2128369009 | TRAIN_TRACKS_GRAVEL_2 |


Using INT as BOOL for out param.


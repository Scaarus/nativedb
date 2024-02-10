---
ns: OBJECT
aliases: ["0x761b0e69ac4d007e"]
---
## HAS_CLOSEST_OBJECT_OF_TYPE_BEEN_BROKEN

```c
// 0x761B0E69AC4D007E
bool HAS_CLOSEST_OBJECT_OF_TYPE_BEEN_BROKEN(Vector3 scrVecPosition, float Radius, Hash modelHash, int SearchFlags);
```

Does a world search and returns TRUE if a broken object with the specified model is found

## SearchFlags Values:
| Value | Name |
| --- | --- |
| 1 | Exteriors |
| 2 | Interiors |


You can speed things up a bit by only specifying one SEARCH_LOCATION_FLAGS if you know that the object is definitely outside or definitely in an interior. If you don't know then pass SEARCH_LOCATION_EXTERIORS|SEARCH_LOCATION_INTERIORS for the SearchFlags


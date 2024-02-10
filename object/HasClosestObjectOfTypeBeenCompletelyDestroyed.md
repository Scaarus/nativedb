---
ns: OBJECT
aliases: ["0x46494a2475701343"]
---
## HAS_CLOSEST_OBJECT_OF_TYPE_BEEN_COMPLETELY_DESTROYED

```c
// 0x46494A2475701343
bool HAS_CLOSEST_OBJECT_OF_TYPE_BEEN_COMPLETELY_DESTROYED(Vector3 scrVecPosition, float Radius, Hash modelHash, int SearchFlags);
```

Does a world search and returns TRUE if the closest fraggable object with the specified model has had all breakable bits broken off.

## SearchFlags Values:
| Value | Name |
| --- | --- |
| 1 | Exteriors |
| 2 | Interiors |


You can speed things up a bit by only specifying one SEARCH_LOCATION_FLAGS if you know that the object is definitely outside or definitely in an interior. If you don't know then pass SEARCH_LOCATION_EXTERIORS|SEARCH_LOCATION_INTERIORS for the SearchFlags


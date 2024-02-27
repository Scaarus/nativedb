---
ns: GRAPHICS
aliases: ["0xfe26117a5841b2ff"]
---
## GET_VEHICLE_CREW_EMBLEM_REQUEST_STATE

```c
// 0xFE26117A5841B2FF
int GET_VEHICLE_CREW_EMBLEM_REQUEST_STATE(Vehicle vehicle, int badgeIndex);
```

Gets the current state of a vehicle crew emblem request made using [`ADD_VEHICLE_CREW_EMBLEM`](#_0x428BDCB9DA58DA53) CERS_NOT_ACTIVE - means that an error has occured as no request is found for this vehicle CERS_REQUESTING_BADGE - means that the request is still in progress (still requesting the texture from the cloud) CERS_APPLYING_DECAL - means that the request is still in progress (still applying the decal) CERS_SUCCEEDED - means that the request has succeeded CERS_FAILED - means that the request has failed Note that if CERS_SUCCEEDED or CERS_FAILED are returned the request will automatically be made not active (CERS_NOT_ACTIVE) so querying it again will produce an error

## Return Type Values:
| Value | Name |
| --- | --- |
| 0 | Not Active |
| 1 | Requesting Badge |
| 2 | Applying Decal |
| 3 | Succeeded |
| 4 | Failed |
| 5 | Failed Cant Get Clan Texture |
| 6 | Failed Cant Add Data Slot |
| 7 | Failed Vehicle No Longer Valid |
| 8 | Failed Vehicle Bone Not Valid |
| 9 | Failed Vehicle Bone Is Zero |
| 10 | Failed Vehicle Probe Failed |
| 11 | Failed Decal Didnt Apply |


## Parameters
* **vehicle**: 
* **badgeIndex**: (Default value: `0`)

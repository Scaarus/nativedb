---
ns: WEAPON
aliases: ["0x0725a4ccfded9a70"]
---
## SET_PED_CURRENT_WEAPON_VISIBLE

```c
// 0x0725A4CCFDED9A70
void SET_PED_CURRENT_WEAPON_VISIBLE(Ped ped, bool VisibleFlag, bool DestroyObject, bool DeadCheck, bool StoreDestroyedWeaponClipValue);
```

Sets the visibility flag for the characters currently equipped weapon


## Parameters
* **ped**: 
* **VisibleFlag**: 
* **DestroyObject**: 
* **DeadCheck**: 
* **StoreDestroyedWeaponClipValue**: only used if "DestroyObject" is TRUE. This flag ensures the weapon clip value if cached when destroyed, ensuring that it gets restored to this value when it is re-created.

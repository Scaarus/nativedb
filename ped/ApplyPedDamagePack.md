---
ns: PED
aliases: ["0x46df918788cb093f"]
---
## APPLY_PED_DAMAGE_PACK

```c
// 0x46DF918788CB093F
void APPLY_PED_DAMAGE_PACK(Ped ped, string packName, float preAge, float alpha_param);
```

Apply a ped damge pack (defined in peddamage.xml) to the specifed ped


## Parameters
* **ped**: 
* **packName**: the name of the damage pack. This should match a damage pack entry in build\dev\common\data\effects\peddamage.xml
* **preAge**: the amount of time to preset the "age" of the damage to (sometime we want old blood, not rfesh wounds, etc)
* **alpha_param**: apply this alpha to the decorations which support alpha (usefull for say accumualting something, apply is as increasingly higher values)

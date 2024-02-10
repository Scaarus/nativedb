---
ns: PED
aliases: ["0x5615e0c5eb2bc6e2"]
---
## SET_RELATIONSHIP_GROUP_AFFECTS_WANTED_LEVEL

```c
// 0x5615E0C5EB2BC6E2
void SET_RELATIONSHIP_GROUP_AFFECTS_WANTED_LEVEL(Hash relGroup, bool ShouldAffectWantedLevel);
```

```
Sets whether a relationship group should influence WL, resolved at same time the per ped flag is resolved when reporting a crime

relGroup is the hash of the relationship group you want to modify, bShouldAffectWantedLevel determines if peds of this type will influence WL
```

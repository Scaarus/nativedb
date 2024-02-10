---
ns: CUTSCENE
aliases: ["0x499ef20c5db25c59"]
---
## DOES_CUTSCENE_ENTITY_EXIST

```c
// 0x499EF20C5DB25C59
bool DOES_CUTSCENE_ENTITY_EXIST(string sEntitySceneName, Hash modelHash);
```

```
Checks that this cutscene entity exits.

Only need to pass the model in if the scene has both an IG_ and CS_ version of the same model
```

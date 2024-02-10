---
ns: BRAINS
aliases: ["0x4ee5367468a65ccc"]
---
## ADD_SCRIPT_TO_RANDOM_PED

```c
// 0x4EE5367468A65CCC
void ADD_SCRIPT_TO_RANDOM_PED(string pScriptName, Hash modelHash, int PercentageChance, bool ScenarioPedsOnly);
```

Associates a script brain with a certain ped model.

PercentageChance should be between 0 and 100. It determines the chance of a new ped with the model getting a brain. Set bScenarioPedsOnly to TRUE if you only want the brain to be given to peds created as scenario peds.


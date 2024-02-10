---
ns: CUTSCENE
aliases: ["0xc0741a26499654cd"]
---
## GET_ENTITY_INDEX_OF_REGISTERED_ENTITY

```c
// 0xC0741A26499654CD
Entity GET_ENTITY_INDEX_OF_REGISTERED_ENTITY(string sEntitySceneName, Hash modelHash);
```

Only use this to get the entity index of an entity registered to be created by the cutscene.

Call this command during the cutscene when REGISTER_ENTITY_FOR_CUTSCENE with CU_CREATE_AND_ANIMATE_NEW_SCRIPT_ENTITY is used. Only need to pass a Model in if the scene contains both an IG_ and CS_ version of the same entity. e.g. The scene is seamless and will swap a the CS_ version for an IG_ at the end of the scene.


---
ns: CUTSCENE
aliases: ["0xe40c1c56df95c2e8"]
---
## REGISTER_ENTITY_FOR_CUTSCENE

```c
// 0xE40C1C56DF95C2E8
void REGISTER_ENTITY_FOR_CUTSCENE(Entity entity, string sSceneHandle, int Usage, Hash modelHash, int Options);
```

Registers an entity with the cut scene system. More info

## Usage Values:
| Value | Name |
| --- | --- |
| 0 | Animate Existing Script Entity Get The Cut Scene To Animate A Script Controlled Entity |
| 1 | Animate And Delete Existing Script Entity Get The Cutscene To Animate A Script Controled Entity And Then Delete It. E.G. If The Entity Dies In The Scene |
| 2 | Create And Animate New Script Entity Get The Cut Scene To Create And Script That Will Be Handed To Script Control At The End Of The Scene. E.G. Player Meets A Buddy In The Scene |
| 3 | Dont Animate Entity Tell The The Cutscene That This Ped Is Dead And Should Not Appera In The Scene. |


## Options Values:
| Value | Name |
| --- | --- |
| 0 | None |
| 1 | Preserve Face Blood Damage |
| 2 | Preserve Body Blood Damage |
| 4 | Remove Body Blood Damage |
| 8 | Clone Damage To Cs Model |
| 16 | Reset Capsule At End |
| 32 | Is Cascade Shadow Focus Entity During Exit |
| 64 | Ignore Model Name |
| 128 | Preserve Hair Scale |
| 256 | Instant Hair Scale Setup |
| 512 | Dont Reset Ped Capsule |
| 1024 | Update As Real Door |


## Parameters
* **entity**: 
* **sSceneHandle**: The name of the asscoiated on the cutscene side with that entites. All entites exported for a cutscene have a unique name, this name references those objects. To find scene handle for peds start your cutscene Rag->Cutscene->Start or End Selected Cutscene tehn go to Rag->Cutscene->Ped Variation-> Display Peds Names and Scene Handles CU_ANIMATE_EXISTING_SCRIPT_ENTITY, Get the cut scene to animate a script controlled entity CU_ANIMATE_AND_DELETE_EXISTING_SCRIPT_ENTITY, Get the cutscene to animate a script controled entity and then delete it. e.g. if the entity dies in the scene CU_CREATE_AND_ANIMATE_NEW_SCRIPT_ENTITY, Get the cut scene to create and script that will be handed to script control at the end of the scene. e.g. player meets a buddy in the scene CU_DONT_ANIMATE_ENTITY Tell the the cutscene that this ped is dead and should not appera in the scene.
* **Usage**: 
* **modelHash**: 
* **Options**: 

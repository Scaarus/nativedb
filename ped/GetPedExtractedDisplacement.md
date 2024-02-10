---
ns: PED
aliases: ["0xe0af41401adf87e3"]
---
## GET_PED_EXTRACTED_DISPLACEMENT

```c
// 0xE0AF41401ADF87E3
Vector3 GET_PED_EXTRACTED_DISPLACEMENT(Ped ped, bool Worldspace);
```

```
Gets the displacement (in meters) that will be applied to the given ped this frame.

If bWorldspace is set to TRUE the result will be in world coordinates (absolute worldspace) If bWorldspace is set to FALSE the result will be in local coordinates (relative to the character)
```

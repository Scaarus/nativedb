---
ns: SHAPETEST
aliases: ["0xff6be494c7987f34"]
---
## START_SHAPE_TEST_MOUSE_CURSOR_LOS_PROBE

```c
// 0xFF6BE494C7987F34
Shapetest START_SHAPE_TEST_MOUSE_CURSOR_LOS_PROBE(Vector3 vProbeStartPosOut, Vector3 vProbeEndPosOut, int LOSFlags, Entity entity, int Options);
```

Works just like [START_SHAPE_TEST_LOS_PROBE](#_0x7EE9F5D83DD4F90E) only the start and end points of the probe are calculated based on the mouse cursor position projected into the world. vProbeStartPosOut and vProbeEndPosOut will be filled with the start and end points of the probe in world space.

Returns SHAPETEST_INDEX of 0 if it fails to create the shapetest request (there is a limit to the number that can be in the system)


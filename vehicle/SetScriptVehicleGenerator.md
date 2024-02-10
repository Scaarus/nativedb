---
ns: VEHICLE
aliases: ["0xd9d620e0ac6dc4b0"]
---
## SET_SCRIPT_VEHICLE_GENERATOR

```c
// 0xD9D620E0AC6DC4B0
void SET_SCRIPT_VEHICLE_GENERATOR(Vehicle_Generator vehicle_generator, int NumberOfCarsToGenerate);
```

```
Sets a script vehicle generator to generate a number of vehicles.

To switch the given car generator off, pass in 0 as the NumberToGenerate. To switch the car generator on, pass in a number greater than 100. If a number less than or equal to 100 is passed in then the generator will generate that number of cars and then switch itself off.
```

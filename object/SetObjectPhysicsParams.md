---
ns: OBJECT
aliases: ["0xf6df6e90de7df90f"]
---
## SET_OBJECT_PHYSICS_PARAMS

```c
// 0xF6DF6E90DE7DF90F
void SET_OBJECT_PHYSICS_PARAMS(Object object, float fMass, float fGravityFactor, Vector3 TranslationalDamping, Vector3 RotationalDamping, float fCollisionMargin, float fMaxAngularSpeed, float fBuoyancyFactor);
```

Set physics parameters on this instance of an object.

Any param set to -1.0 will be ignored, and will remain as defaults. Specifying mass = -1.0 will reset the mass back to the object's default value


## Parameters
* **object**: 
* **fMass**: object mass (rotational inertia is calculated from new mass and volume) fGravityFactor the gravity affecting this object can be modified (default is 1.0)
* **fGravityFactor**: 
* **TranslationalDamping**: x = x = constant friction (doesn't depend on speed) y = y*V = speed dependent friction (multiplied by speed) z = z*V^2 = aerodynamic drag (multiplied by speed squared) RotationalDamping x = x = constant friction (doesn't depend on speed) y = y*V = speed dependent friction (multiplied by speed) z = z*V^2 = aerodynamic drag (multiplied by speed squared) fCollisionMargin Set to thinnist part of object. Default is 10cm fMaxAngularSpeed Increase for objects which are likely to spin fast, e.g. small spheres. Default is 2*PI fBuoyancyFactor Allow scaling of an object's buoyancy in water.
* **RotationalDamping**: 
* **fCollisionMargin**: 
* **fMaxAngularSpeed**: 
* **fBuoyancyFactor**: 

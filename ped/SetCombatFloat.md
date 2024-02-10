---
ns: PED
aliases: ["0xff41b4b141ed981c"]
---
## SET_COMBAT_FLOAT

```c
// 0xFF41B4B141ED981C
void SET_COMBAT_FLOAT(Ped ped, int combatAttribute, float fNewValue);
```

To set a variety of combat attributes (floats) using one function

## combatAttribute Values:
| Value | Name |
| --- | --- |
| 204 | CCF_BLIND_FIRE_CHANCE Chance to blind fire from cover, range is 0.0-1.0 (default is 0.05 for civilians, law doesn't blind fire) |
| 205 | CCF_BURST_DURATION_IN_COVER How long each burst from cover should last (default is 2.0) |
| 207 | CCF_TIME_BETWEEN_BURSTS_IN_COVER How long to wait, in cover, between firing bursts (< 0.0 will disable firing, unless cover fire is requested, default is 1.25) |
| 208 | CCF_TIME_BETWEEN_PEEKS How long to wait before attempting to peek again (default is 10.0) |
| 209 | CCF_STRAFE_WHEN_MOVING_CHANCE A chance to strafe to cover, range is 0.0-1.0 (0.0 will force them to run, 1.0 will force strafe and shoot, default is 1.0) |
| 210 | CCF_WEAPON_ACCURACY default is 0.4 |
| 211 | CCF_FIGHT_PROFICIENCY How well an opponent can melee fight, range is 0.0-1.0 (default is 0.5) |
| 212 | CCF_WALK_WHEN_STRAFING_CHANCE The possibility of a ped walking while strafing rather than jog/run, range is 0.0-1.0 (default is 0.0) |
| 213 | CCF_HELI_SPEED_MODIFIER The speed modifier when driving a heli in combat |
| 214 | CCF_HELI_SENSES_RANGE The range of the ped's senses (sight, identification, hearing) when in a heli |
| 215 | CCF_ATTACK_WINDOW_DISTANCE_FOR_COVER The distance we'll use for cover based behaviour in attack windows Default is -1.0 (disabled), range is -1.0 to 150.0 |
| 216 | CCF_TIME_TO_INVALIDATE_INJURED_TARGET How long to stop combat an injured target if there is no other valid target, if target is player in singleplayer |
| 217 | CCF_MIN_DISTANCE_TO_TARGET Min distance the ped will use if CA_MAINTAIN_MIN_DISTANCE_TO_TARGET is set, default 5.0 (currently only for cover search + usage) |
| 218 | CCF_BULLET_IMPACT_DETECTION_RANGE The range at which the ped will detect the bullet impact event |
| 219 | CCF_AIM_TURN_THRESHOLD The threshold at which the ped will perform an aim turn |
| 220 | CCF_OPTIMAL_COVER_DISTANCE  |
| 221 | CCF_AUTOMOBILE_SPEED_MODIFIER The speed modifier when driving an automobile in combat |
| 222 | CCF_SPEED_TO_FLEE_IN_VEHICLE  |
| 223 | CCF_TRIGGER_CHARGE_TIME_NEAR How long to wait before charging a close target hiding in cover |
| 224 | CCF_TRIGGER_CHARGE_TIME_FAR How long to wait before charging a distant target hiding in cover |
| 227 | CCF_HOMING_ROCKET_BREAK_LOCK_ANGLE Angle between the rocket and target where lock-on will stop, range is 0.0-1.0, (default is 0.2), the bigger the number the easier to break lock |
| 228 | CCF_HOMING_ROCKET_BREAK_LOCK_ANGLE_CLOSE Angle between the rocket and target where lock-on will stop, when rocket is within CCF_HOMING_ROCKET_BREAK_LOCK_CLOSE_DISTANCE, range is 0.0-1.0, (default is 0.6), the bigger the number the easier to break lock |
| 229 | CCF_HOMING_ROCKET_BREAK_LOCK_CLOSE_DISTANCE Distance at which we check CCF_HOMING_ROCKET_BREAK_LOCK_ANGLE_CLOSE rather than CCF_HOMING_ROCKET_BREAK_LOCK_ANGLE |
| 230 | CCF_HOMING_ROCKET_TURN_RATE_MODIFIER Alters homing characteristics defined for the weapon (1.0 is default, <1.0 slow turn rates, >1.0 speed them up |
| 231 | CCF_TIME_BETWEEN_AGGRESSIVE_MOVES_DURING_VEHICLE_CHASE Sets the time delay between aggressive moves during vehicle chases. -1.0 means use random values, 0.0 means never |
| 233 | CCF_WEAPON_DAMAGE_MODIFIER Multiplies the weapon damage dealt by the ped, range is 0.0-10.0 (default is 1.0) |
| 234 | MAX_COMBAT_FLOATS |


Need to pass in which combat attribute is being set and what the value you are setting it to is

This is the function that is used to set the majority of combat float attributes, like time between bursts in cover or time betweek peeks, etc. See COMBAT_ATTRIBUTE_FLOATS for information on the default values of each combat float


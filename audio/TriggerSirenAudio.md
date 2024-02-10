---
ns: AUDIO
aliases: ["0x66c3fb05206041ba"]
---
## TRIGGER_SIREN_AUDIO

```c
// 0x66C3FB05206041BA
void TRIGGER_SIREN_AUDIO(Vehicle vehicle);
```

```
Actually sets the siren audio active. If attempting to enable a siren on a driverless vehicle, you may need to use this to kick off the actual sound (generally we only trigger the audio if a driver is in the vehicle)
```

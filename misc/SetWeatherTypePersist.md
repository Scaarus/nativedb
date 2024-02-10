---
ns: MISC
aliases: ["0x704983df373b198f"]
---
## SET_WEATHER_TYPE_PERSIST

```c
// 0x704983DF373B198F
void SET_WEATHER_TYPE_PERSIST(string NewWeather);
```

Sets the weather type to persist for ever.

The weather type for each level is stored in weather.dat in X:\"current project"\build\dev\common\data\levels\"the level you want"\weather.dat The weather types currently are EXTRASUNNY, CLEAR, CLOUDS, SMOG, CLOUDY, OVERCAST, RAIN, THUNDER, CLEARING, NEUTRAL, SNOWLIGHT, SNOW, BLIZZARD


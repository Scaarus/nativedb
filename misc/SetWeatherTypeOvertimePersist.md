---
ns: MISC
aliases: ["0xfb5045b7c42b75bf"]
---
## SET_WEATHER_TYPE_OVERTIME_PERSIST

```c
// 0xFB5045B7C42B75BF
void SET_WEATHER_TYPE_OVERTIME_PERSIST(string NewWeather, float time);
```

Sets the weather type overt time, once time has passed and the transition is done, it will behave like a [`SET_WEATHER_TYPE_NOW_PERSIST`](#_0xED712CA327900C8A).

time is the transition time, in seconds.

The weather string are in weather.dat file


---
ns: AUDIO
aliases: ["0xad6b3148a78ae9b6"]
---
## SET_VARIABLE_ON_SOUND

```c
// 0xAD6B3148A78AE9B6
void SET_VARIABLE_ON_SOUND(int SoundId, string VariableName, float VariableValue);
```

Sets a variable on a sound.

This command allows a scripter to communicate with the sound engine in complex ways, by passing a floating point value to a specific sound object. This allows some nice effects such as adjusting the pitch of a sample being to be played back, or varying a lowpass cutoff. The VariableName parameter must be set up in RAVE (the audio scripting tool) as well as instruction on its usage on a case-by-case basis therefore a sound designer must be consulted with before using this command.


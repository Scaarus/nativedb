---
ns: AUDIO
aliases: ["0x2f9d3834aeb9ef79"]
---
## SET_VARIABLE_ON_STREAM

```c
// 0x2F9D3834AEB9EF79
void SET_VARIABLE_ON_STREAM(string VariableName, float VariableValue);
```

```
Sets a variable on the current streaming sound.

This command allows a scripter to communicate with the sound engine in complex ways, by passing a floating point value to a specific sound object. This allows some nice effects such as adjusting the pitch of a sample being to be played back, or varying a lowpass cutoff. The VariableName parameter must be set up in RAVE (the audio scripting tool) as well as instruction on its usage on a case-by-case basis therefore a sound designer must be consulted with before using this command.
```

---
ns: AUDIO
aliases: ["0x430386fe9bf80b45"]
---
## GET_SOUND_ID

```c
// 0x430386FE9BF80B45
int GET_SOUND_ID();
```

Gets an id of a triggered sound.

This function returns a new SoundId, which is used for keeping track of sounds after they've been triggered - use this if you need to control a sound after it's been started, for instance to stop a looping sound, or to change a sound's pitch midway through playback. The SoundId is always an integer greater than or equal to zero; if a playback function has a SoundId field but the sound doesn't need to be altered after triggering then pass a value of -1 for fire-and-forget playback, rather than getting a SoundId. SoundIds can be reused, without needing to release them and grab a new one. If a sound's finished playing, you can reuse its SoundId to kick off another one. If the sound's not finished playing, it'll be stopped first (fading out or whatever is set up in RAVE by the sound designer), and the new one kicked off; usually it is safer to just get a new SoundId.


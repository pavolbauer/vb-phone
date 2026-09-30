# Voice Blaster

A voice effects recorder for phones, inspired by the Roland E-4. Record with the phone's microphone, then change the voice.

- **Voices:** Normal, Trap (hard autotune, deeper voice, beat-timed echo), Mouse, Monster, Autotune (your own voice, snapped to the notes), Robot, Alien, Choir, Cave
- **Tweak:** pitch (±12 semitones), autotune, robot, echo, reverb, harmony (duet, trio, deep)
- **Recordings:** saved clean on the phone, so any voice can be tried later. Loop them, play several at once, or save one as a WAV with the current voice.
- **Live mode:** hear your changed voice in real time (use headphones).

It is a single `index.html` with no build step. The microphone only works over https, so host it with GitHub Pages:
Settings → Pages → Deploy from a branch → pick this branch and `/ (root)`.

On iPhone, turn off silent mode to hear the effects.

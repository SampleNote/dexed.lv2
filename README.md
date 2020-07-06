Dexed - FM Plugin Synth
=======================

Dexed is a multi platform, multi format plugin synth that is closely modeled on the Yamaha DX7. 
Under the hood it uses [music-synthesizer-for-android](https://github.com/google/music-synthesizer-for-android) 
for the synth engine and [JUCE](http://wwww.juce.com) as a plugin wrapper.

The goal of this project is to be a tool/companion for the original DX7. Sound engine 
with 'float' value parameters, different waveform à la TX81z would be great but anything that 
goes beyond the DX7 should and will be a fork of this project. This is to keep the compatibility with
the original machine.

Dexed is licensed on the GPL v3. The msfa component (acronym for music synthesizer for android, see msfa 
in the source folder) stays on the Apache 2.0 license to able to collaborate between projects.

[Dexed User Website](http://asb2m10.github.io/dexed)

__This is a fork of the original Dexed JUCE plugin that provides Dexed as LV2 plugin.__
It's a stripped down version which has no own UI and should be used only as a
LV2 plugin (e.g. for mod-host).

If someone has time and fun developing or finds a bug please contact dcoredump@gmail.com!

```
git clone https://github.com/dcoredump/dexed.git
cd dexed/src
make install
```
 

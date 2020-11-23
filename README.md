# musical-speaker

A Factorio mod that provides an enhanced version of the programmable speaker, mostly intended for music production.

Sound data for this mod was generated by [FluidSynth](http://www.fluidsynth.org/) (GPL licensed) from the [FluidR3_GM2 soundfont](https://member.keymusician.com/Member/FluidR3_GM/index.html) (MIT licensed). Much thanks goes to the developers of these projects.

Features:
- Includes 189 instruments
 - Provides all instruments specified by [General Midi Level II](https://en.wikipedia.org/wiki/General_MIDI_Level_2)
- _All_ melodic (non-percussion) instruments have a range of A0 to C8, AKA standard 88-key piano
- All percussion instruments provide GM2 drum sounds.
- Crazy-high polyphony setting of 128, because Why Not.

# Example usage
This [video](https://www.youtube.com/watch?v=bkav_L3kp4E) was made entirely in Factorio by utilizing musical-speaker.

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/bkav_L3kp4E" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Helpful Tips
- To convert a midi note number to a melodic pitch, subtract 21.
- To convert a midi note number to a percussion sound, subtract 35

# Future Plans
- Circuit-network signal to control instrument, volume, and polyphony
- Support GM2_SM (?)

This is a potential Apple 2 hardware mod I hope to eventually bring it into physical existence. It’s meant to add the capability to:

- route sound card audio to the stock speaker,
- support mixing motherboard audio into the sound card audio (i believe some sound cards don’t come with this feature),
- support use of a second speaker mounted into the case for stereo,
- output to a line-out jack at the back of the case (attached to one of those mounts for a //e, not sure what yet for older ][’s),
- output to a second jack for headphone output,
- control speaker and headphone volume with a volume knob, presumably protruding from a modded case beneath the keyboard,
- feature a second knob to control:
 * line-out output only,
 * speakers / headphones on (depending on whether headphone are plugged in),
 * speakers on only and headphones off (to support headphones always connected)

These features should be possible using a small circuit board to be mounted within the case beneath the keyboard with some minor modifications. It should require no controller or firmware, and the plan is to power it from a pass-through hat on the motherboard’s game port.

The schematic originates from a specification fed to Gemini and this KiCad project created according to its design. Next I’ll implementing this schematic on a breadboard and, if testing going well, I’ll later design a PCB and fab some prototypes. Assistance appreciated, especially feedback on the schematic since I really a beginner in all this.

![schematic](schematic.png)

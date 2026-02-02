This is a potential Apple II hardware mod I hope to eventually turn into a working physical add-on for any ][, ][+, //e. It’s meant to add these capabilities:

- route sound card audio to the stock speaker
- mixing motherboard audio into the sound card audio (i believe some sound cards don’t come with this feature)
- an optional second speaker mounted into the case for stereo (mounting strategy not determined yet)
- control volume with a knob protruding through a hole dremel'd into case beneath the keyboard (willing to accept feedback about an alternate volume control and placement, of if volume control should be made optional)
- when volume knob turned off, output to a line-out jack at the back of the case (attached to one of those mounts for a //e, not sure what yet for older ][’s)
- output to headphone jack at the back of the case, also controlled by the volume knob, disabling the speaker(s) when connected (also attached to one of those mounts for a //e, maybe both jacks out one wide slot)
- optionally output to another headphone jack at the front of the case (via a second hole in the case beside the volume knob)

These features should be possible using a small circuit board to be mounted within the case beneath the keyboard with some minor modifications, either one or two holes drilled into the case's metal base, the part that's angled upwards. It should require no controller or firmware, and the plan is to connect it to power and ground via the motherboard’s game port (potentially using a pass-through socket to permit its use for joysticks or whatever else). 

The schematic originates from a specification fed to Gemini and a KiCad project created according to its design, making use of a 8403 amplifier module. Needless to say there were numerous back and forth sessions. I created a simple PCB design as a proof of concept, currently all through-hole components. Well it leverages a ready-to-use amplifier module with its own surface-mount components, but that itself needs connection with pin headers.

The latest iteration of the PCB is 4.5cm wide and 6.3cn tall, and I'm hoping they will fit, on a //e between the motherboard and the end of the flat part of the base, somewhat in the center or right of the case. On a ][ / ][+ I'm hoping there's room in front of the power supply. I know the stock speaker is in that area, I'll have to see more 2's in the wild and see. For both models there should also be space at the far right side of the vents for an second speaker to be mounted somehow.

Volume and front headphone are on a small daughterboard, connected via a ribbon cable, that can mount flush to the upwardly angled part of the base, I'm hoping there's room directly under the keyboard at this angle and still allow the knob and jack to be high enough off the table to be useful. The main board however is also able to have the volume and headphone jack populated on it directly instead, for those wanting to mount it with those controls protruding out the side of the case. I'm making it support this just for me really, as my own case if damaged and I don't mind making holes in the beige plastic, and especially if I run into space issues under the keybaord. I suspect this option will be less of an interest to others since making holes in the beige plastic is not something they'd want to do, and not something I'd recommend.

I also am planning how to mount line-out and optionally a second headphone jack to the back of the case. I've found what might be good jack components, and I think they'll work in one of the long //e openings, but not sure yet. I suspect some 3D-printed thing will be involved in making this work.

I'm putting the cart before the horse a bit iterating over the PCB layout and pondering these physical issues, as I’ve still yet to test an implementation of the schematic on a breadboard.

Feedback and assistance are appreciated on the Discussions page for this repo, especially feedback on the schematic and PCB since I really a beginner in all this. Especially feedback on the physical mounting and modding challenges for this thing. Thanks.

![schematic](schematic.png)

![schematic](schematic%202.png)

![schematic](render.jpg)

![schematic](render%202.jpg)

![schematic](render%203.jpg)

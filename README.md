# Guitar_effect_MIDI_footswitch
MIDI controller for guitar effect

USB MIDI controller for controlling software on PC

I could not find any MIDI controller that would meet my requirements, so I made one.
Controller has 10 phisical switches, switch #11 serves as "shift", so box has 20 effective switches. 6 LEDs are used, one Power, one Shift and four Presets.
Arduino is sending CC commands to PC via USB. Windows needs to run Hairless MIDI and LoopMIDI. I am using standalone ToneLib, but it should work with any DAW that can be controlled by MIDI commands.

Box is 3d printed with wood filament, but any filament can be used. I printed it on 235x235 bed.

The way that ToneLib works, when bank is changed, first preset is always active, so first led will lit. others will be on when respective presets are selected. It does not pull preset state from Tonelib, it is programmed that way. 
Switches are fi7mm momentary non latching. If you use different switches, drill bigger holes in cover plates. 
Cover plates are screwed with 3x8mm wood screws, all other is crewed with M3 different lengths.
![IMG_20221103_191115](https://user-images.githubusercontent.com/68291385/205467280-94868e8b-c3e7-41e0-a836-838e557ae26f.jpg)
![IMG_20221103_191126](https://user-images.githubusercontent.com/68291385/205467282-0541f40b-c8e5-4357-940a-d4fe8602ea99.jpg)
![IMG_20221109_201814](https://user-images.githubusercontent.com/68291385/205467284-79582783-f2d6-4762-b9cf-e693125a4cfe.jpg)
![IMG_20221103_072459](https://user-images.githubusercontent.com/68291385/205467286-9a9d5981-ed5c-4a15-a214-7d74bba01465.jpg)

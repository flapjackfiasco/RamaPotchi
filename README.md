# RamaPotchi
 Digital Pet

## Hello!
This is a project I started with my kids, for fun. It's based on the following project:
    
[Picotamachibi - website](https://www.kevsrobots.com/blog/picotamachibi.html)

[Picotamachibi - Github](https://github.com/kevinmcaleer/picotamachibi)

## Changes
The idea is to make a smaller hardware platform than the Pi Pico used in the original, using the same RP2040 mcu, and adding some missing essentials.
Here are some of the additions that are implemented/planned/considered:

- [x] Rechargable battery (implemented).
- [x] Battery charging status LEDs (implemented).
- [x] A Game Status RGB LED (hardware: implemented / software: planned).
- [x] A speaker/buzzer (implemented).
- [ ] A haptic feedback motor (considered).
- [ ] Environment sensors (considered).

## Progress
![](https://geps.dev/progress/100) Schematic: v1.0 of the schematic is complete! Time for PCB layout to get started! A PDF file of the schematic, and JPEG images 
 of the individual pages can be found in the Prints directory.

![](https://geps.dev/progress/5) PCB: PCB layout has started! I'll be following the official Pi Pico layout, excising unneeded GPIO pinouts and ADC to
 reduce the overall size. This is intended to be a pocket/keychain size device, so keeping it small critical. That means all SMD components where possible, and the 
 tightest acheivable spacing, taking cheap board manufacturer's (JLCPCB, PCBWay, etc.) design constraints into consideration.
 
 This precludes it from being a hand-soldering project for the kids. Really, the only things keeping it from being hand-solderable are the RP2040, and the intention to 
 keep things small. Perhaps a project board could be developed in the future with through hole footprints for everything, and a 40-pin ZIF socket to mount 
 a Pi Pico? If only to make it more accessible for kids to be able to solder some of the components themselves.

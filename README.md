# Sofle Choc MAXXING
Guide for upgrading a [Sofle Choc Wireless](https://github.com/db-ok/SofleChocWireless), to add Trackpads, huge batteries, tenting feet and more!

Note: these are my personal notes on how I upgraded it. Your experience will be different depending on your starting point

Note: i bought all parts **for this guide** on Aliexpress. All items that don't say "shipping" in their price i was able to find them as "Choice" in Italy as of 2026-03-31.

## Starting point
TODO: add picture
- 2 EC11 Encoders
- 110 mAh batteries
- 3D printed keycaps
- Red Pro switches
- No RGB LEDs
- No Screens
- No tenting feet (always flat)
- Separate "Dongle" with a screen

I built it by following the guide on the https://github.com/db-ok/SofleChocWireless repo.

## Upgrades

### Case
This case is a remix of the [Sofle Choc magnetic](https://www.thingiverse.com/thing:5683287) case.

I extruded the bottom part by ~3mm, and added holes for a 306080 battery, tenting feet and magnets (which are needed for a future upgrade).

#### Guide
TODO

#### BOM
- Batteries: 306080 2500 mAh (2x) [~10 EUR + 7 EUR Shipping]
- Magnets: N35 8x1.5 (50x) [~3 EUR]
- Heat set insert: TODO
- Rubber feet (any)
- Tenting feet: TODO add link (4x) [~10 EUR]

### RGB LEDs
I actually skipped this component when building my keyboard originally out of pure laziness. I actually don't like any RGB at all, 
I just want them for indicating layers (which is genuinely useful), plus the LEDs are dirt cheap, so why not? 
Just don't leave them on all the time, or your battery life will be very short

#### Guide
TODO

#### BOM
- SK6812 MINI-E RGB LED (60+) [~4 EUR]

### Trackpad
This upgrade a trackpad, but is the hardest as it requires a custom PCB or Handwiring (extremely janky, not recommended)
In the future, I might add a second trackpad on the left side for redundancy.

#### Guide
TODO

#### BOM
- Azoteq TPS43-201A-S [~10 EUR + 7 EUR shipping]
- FCC Cable, 5CM, Type A connector, 6 pins, 0.5MM pitch (10x) [~3 EUR]
- FCC connector 6 pins, 0.5MM pitch (10x) [~3 EUR]
- Sideways Momentary Tactile DIP switch 3x6x4.3 (50x) [~3 EUR] (needed because the trackpad covers the reset button if it is installed upwards)

  
### Other
For now, the only other upgrade I did is i changed the keycaps set.

#### BOM
- Keycaps: Chosfox CFX BOW (Alpha set) [~22 EUR + 5 EUR Shipping]

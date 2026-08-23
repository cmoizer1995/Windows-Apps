# ETS2 vJoy H\-Shifter for Stream Deck

**Version:** 1\.38
**Author:** Connor Moizer
**Website:** ConnorMoizer\.com
**Last edited:** 23 August 2026

A Stream Deck plugin for controlling a vJoy\-based H\-shifter in Euro Truck Simulator 2\.

Download https://github.com/cmoizer1995/Windows-Apps/releases/tag/Streamdeck
## Features

- Uses vJoy Device 1\.
- Six H\-shifter positions use vJoy buttons 1–6\.
- Manual LOW/HIGH range switching\.
- LOW = gears 1–6\.
- HIGH = gears 7–12\.
- Range toggle = vJoy Button 12\.
- Neutral bind = vJoy Button 11\.
- Engine = vJoy Button 14\.
- Reverse = vJoy Button 15\.
- Selected gear stays highlighted on Stream Deck\.
- v1\.38 remembers the last selected gear and LOW/HIGH range instead of resetting to Neutral when changing Stream Deck pages or working in OBS\.
- Truck Settings can load supported stock ETS2 truck/gearbox information\.
- SETUP writes the ETS2 controller configuration while ETS2 is closed\.
- ETS2 H\-Shifter layout is set to **Range**\.
- Includes OBS support files\.

## vJoy mapping

|Function      |Button|
|--------------|-----:|
|H position 1  |1     |
|H position 2  |2     |
|H position 3  |3     |
|H position 4  |4     |
|H position 5  |5     |
|H position 6  |6     |
|Neutral bind  |11    |
|LOW/HIGH range|12    |
|Engine        |14    |
|Reverse       |15    |

A 12\-speed gearbox reuses the same six physical positions across LOW and HIGH ranges\.

## Installation

1. Install/configure vJoy with Device 1 available\.
2. Double\-click `com.connormoizer.vjoy-hshifter-v1.38.streamDeckPlugin`\.
3. Allow Stream Deck to install it\.
4. Restart Stream Deck if required\.
5. Add the ETS2 H\-Shifter actions to your profile\.
6. Run **SETUP** with ETS2 closed when you want the plugin to write the controller configuration\.

## Important ETS2 setting

Use:

**Controls → H\-SHIFTER → Shifter layout → Range**

## OBS

The combined package includes OBS support\. The stable OBS folder used by the project is:

`%USERPROFILE%\Documents\Connor Moizer\ETS2 H-Shifter\OBS\`

v1\.37\+ includes a local live\-state feed for reliable OBS gear/status refresh\.

## Files

- `com.connormoizer.vjoy-hshifter-v1.38.streamDeckPlugin`
- `ETS2-HShifter-v1.38-StreamDeck-and-OBS.zip`
- `vjoy-hshifter-v1.38-source.zip`

## Disclaimer

This project is not affiliated with or endorsed by SCS Software, Elgato, OBS Project or vJoy\. Euro Truck Simulator 2 and related trademarks/assets belong to their respective owners\.

## Copyright

Copyright © 2026 Connor Moizer
ConnorMoizer\.com
All rights reserved\.

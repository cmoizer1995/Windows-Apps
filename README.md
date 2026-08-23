# ETS2 SimHub OBS Lower Third

**Version:** 4
**Author:** Connor Moizer
**Website:** ConnorMoizer\.com
**Last edited:** 23 August 2026

A 1920×1080 transparent SimHub dashboard designed as an OBS lower third for Euro Truck Simulator 2\.

## Current working behaviour

The dashboard displays:

- **Current Truck** — human\-readable truck brand/model/series\.
- **Current Job** — active cargo/job name\.
- **FREE ROAM** — automatically displayed when there is no active job\.
- **Registration** — current truck registration/licence plate\.
- **Gear** — live current gear\.
- **ConnorMoizer\.com** branding\.

The older raw Truck ID box is hidden in v4 because Current Truck now provides the useful truck/model display\.

## Installation

1. Make sure SimHub is installed\.
2. Double\-click `Connor-Moizer-ETS2-Lower-Third-v4.simhubdash`\.
3. Choose **Install**\.
4. Open Dash Studio and select the installed dashboard\.

A manual\-install ZIP is also included as a fallback\.

## OBS setup

Use the dashboard\-specific SimHub OBS URL:

1. Find the dashboard in SimHub\.
2. Open **More / …**\.
3. Choose **Copy OBS URL** / **Copy OBS Browser Address**\.
4. In OBS add a **Browser Source**\.
5. Paste that exact URL\.
6. Set the Browser Source to **1920 × 1080**\.
7. Put the Browser Source above ETS2 Game Capture\.

Using the specific OBS URL means the lower third opens directly instead of loading SimHub’s general dashboard selection page\.

## Transparency

The dashboard is transparent so you can place it over gameplay or add your own background\.

Its working screen structure is:

- `MainScreen` = supporting/background layer\.
- `Screen` = normal In Game \+ Idle render screen\.
- Visible lower\-third elements render on the normal screen for OBS compatibility\.

## Job behaviour

- No active cargo/job → **FREE ROAM**
- Active delivery → displays the cargo/job name

The truck display also updates automatically when changing truck/profile in ETS2\.

## Files

- `Connor-Moizer-ETS2-Lower-Third-v4.simhubdash`
- `Connor-Moizer-ETS2-Lower-Third-v4-manual-install.zip`

## Disclaimer

This project is not affiliated with or endorsed by SCS Software, SimHub or OBS Project\. Euro Truck Simulator 2 and related trademarks/assets belong to their respective owners\.

## Copyright

Copyright © 2026 Connor Moizer
ConnorMoizer\.com
All rights reserved\.

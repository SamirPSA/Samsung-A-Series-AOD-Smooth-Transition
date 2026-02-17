	# One UI 7 AOD Smooth Transition for Galaxy A Series(Root)

This Magisk module enables high-end system animations and unlocks the smooth Always On Display (AOD) transition on the Samsung Galaxy A Series

## IMPORTANT
THIS WAS TESTED ON A SAMSUNG GALAXY A34 5G WITH ONEUI 7 ANDROID 15, IM NOT SURE IF THIS WOULD WORK ON OTHER SAMSUNG DEVICES, BUT YOU HAVE NOTHING TO LOSE, I READ THAT SOME PEOPLE HAVE THIS ISSUE ON ONEUI 7 SO IM HERE TO TRY TO HELP. | THIS MAYBE WOULD DRY YOUR BATERRY A LITTLE BIT MORE, NOTHING TO WORRY IF YOUR DISPLAY IS OLED.

## Why this module?
By default, Samsung limits the Galaxy A-series to "LowEnd" or "Mid" animation profiles (`sep_lite`). This module "spoofs" the system features to match flagship devices (S23/S24), enabling smoother fades and visual continuity that are otherwise disabled.

## Key Features
- **System Category Upgrade**: Switches `sep_basic` to `sep_main`.
- **High-End Animations**: Changes animation type to `HighEnd` for richer blurs and scales.
- **AOD Transition**: Enables `SEC_FLOATING_FEATURE_FRAMEWORK_CONFIG_AOD_TRANSITION`.
- **Continuity**: Unlocks continuous lockscreen transition types.
- **Improved Refresh Rate**: Optimizes AOD refresh rate logic for a less "choppy" feel.

## Installation
1. Download the repository as a `.zip` file (or download from the [Releases] section).
2. Open the **Magisk** app, go to the **Modules** tab, and select **"Install from storage"**.
3. Flash the ZIP and **Reboot**.

## Recommended Settings
For the best visual experience, please set the following on your device:
- **Motion Smoothness**: High (120Hz).
- **AOD Style**: Enable "Show Lock screen wallpaper" (Fullscreen AOD).
- **Wallpaper**: Use the same wallpaper for both Lock screen and Home screen.

## Requirements 
- Magisk or Kitsune Mask ( ROOT )

## Credits
Developed by SamirPSA.
Special thanks to my mama

---
*Disclaimer: I am not responsible for bricked devices. Always have a backup and know how to use the Key Combo to enter Safe Mode to disable modules. | You can also use TWRP Terminal to deactivate Magisk Modules or delete Modules*

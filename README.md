# Ender-3-Pro-CR-Touch-Board-4.2.2

My printer is an Ender 3 Pro (v1.5) (version 4.2.2 board) with CR Touch

## The configuration I have:
* Windows 64 bit
* I used the BUGFIX branch of marlin 2.0.x
* I used Visual Studio Code, with Auto Build Marlin and PlatformIO extensions

After clicking the build icon in Auto Build Marlin, I had two environments that showed up. I clicked the button next to **STM32F103RET6_creality**, not STM32F103RET6_creality_maple

I suggest using a program such as [WinMerge (For Windows)](http://winmerge.org) to view the differences between my configuration files and yours.


8/3/2021 - change Extruder Steps/mm
configuration.h
/**
 * Default Axis Steps Per Unit (steps/mm)
 * Override with M92
 *                                      X, Y, Z [, I [, J [, K]]], E0 [, E1[, E2...]]
 */
line 904   #define DEFAULT_AXIS_STEPS_PER_UNIT   { 80, 80, 400, 95.8 }

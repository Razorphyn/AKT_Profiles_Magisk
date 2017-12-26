# AKT Profile for Magsik
AKT Profile by Asiier & Senthil360 for Magisk in order to use service.d (LATESTARTSERVICE).

### Is this necessary?
I can't fully mount the /system partition and so /system/etc/init.d/99AKT is not editable.
The result is that at each boot/reboot I have to go through the whole procedure to apply the setting.

This module should make things easier: instead of rely on init.d, it uses the built-in function of magisk.

## Profiles Credits:
// Nameless by @Senthil360 | Fusion by @patalao | Burnout PR3 by @Mostafa Wael \\

// Project Zhana & X.A.N.A by @Asiier | GhostPepper, HawkPepper and FairPark by @Asiier \\

I have just editet the /system/bin/AKT file to make it compatible with Magisk

## XDA links
[[AKT] Advanced Kernel Tweaks v1.6 FINAL | Insane Battery & Performance(SD820/1|OP3/T)](https://forum.xda-developers.com/oneplus-3/how-to/advanced-interactive-governor-tweaks-t3476589)
[[AKT] Advanced Kernel Tweaks v1.0 For OP5 & S835 devices](https://forum.xda-developers.com/oneplus-5/how-to/akt-advanced-kernel-tweaks-v1-0-op5-t3688259)

## Change Log
v1.0
    - Initial release
v1.1 
    - Fixed apply profile on boot (moved to service.d)
v1.2
    - Support for OP5 (check xda links to thanks)
    - Magisk 15 template

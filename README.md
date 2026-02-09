Android 16 Kernel-Rooted ROM for Exynos 8895 Devices

This is a kernel-rooted Android 16 ROM compatible with Samsung devices such as the Galaxy S8, S8+, Note 8, and other Exynos 8895-based devices

Disclaimer: This ROM is not developed by me. I am not responsible for any device issues, including bricked phones. The GSI was created by Doze-Off. The base comes from @thewinner02 (Telegram). The brightness fix was implemented by @JIeMoHuCHuKeT (Telegram)

Known Issues and Fixes

Fixable Issues

Brightness: Fixed via the included KernelSU module

Wi-Fi: Flash the included TWRP ZIP after installing the ROM

Camera: On some devices the camera may not work initially. Recommended steps include reflashing the ROM. If the issue persists, flash BreezeOS ROM first, boot into setup, format in TWRP (only format /data), and then flash the Evolution X ROM again

Non-Fixable Issues

Soft Reboots: Occur when uninstalling applications

Brightness Flickering: May happen during boot or randomly. Disable adaptive brightness to resolve

Installation Instructions

Boot into TWRP recovery

Format the /data partition

Go to Advanced Wipe and wipe the following partitions: Dalvik, Cache, Data, System, Vendor

Reboot to TWRP

Flash repartitioner.zip and cleaner.zip

Flash the Evolution X ROM

Allow the installation to complete and boot the system

If the device does not boot: Boot into TWRP, change the /data partition filesystem to F2FS, reboot into the system and the installation should succeed

Installing Fixes

Brightness Fix (Mandatory): Install the KernelSU Manager APK version 0.7.5 included in the package. Flash the brightness module through KernelSU Manager and reboot the device

Wi-Fi Fix: Flash the included Wi-Fi TWRP ZIP after installing the ROM

The ROM includes a pre-rooted kernel (FURINA 4.4)

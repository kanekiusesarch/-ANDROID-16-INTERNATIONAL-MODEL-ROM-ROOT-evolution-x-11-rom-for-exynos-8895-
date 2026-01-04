A kernel-rooted + Android 16 ROM for Samsung phones such as the S8, S8+, Note 8, and other Exynos 8895 devices.
I AM NOT RESPONSIBLE FOR BRICKED PHONES, GUNS, NUKES, AND LIGHT YAGAMI GETTING A DEATH NOTE (reference).
Heyo, it’s me Kaneki again, and today I’ll be giving ya a guide on how to get this amazing ROM for 8895 phones. BTW, this is NOT MY ROM. The GSI is made by Doze-Off. The base comes from @thewinner02 (Telegram), and the brightness fix is made by @JIeMoHuCHuKeT (Telegram).

BUGS / HOW TO FIX
Brightness  The fix is a KernelSU module included in the release
Wi-Fi  This is just a fix that you need to flash in TWRP
Camera  On some devices, if it doesn’t work, try to reflash it. If that doesn’t work, I will release a BreezeOS ROM too. I also found out that if you install that ROM first, then boot into setup, then proceed to format it in TWRP (ONLY FORMAT IT, NOTHING ELSE), then proceed to flash the Evo X ROM, it might be fixed. It did on my Galaxy S8.

NON-FIXABLE BUGS
There are some weird bugs that even I can’t manage to fix.
• Soft reboots every time you uninstall an app
• Sometimes flickers when you boot it up
If it keeps flickering out of nowhere, simply disable the setting for adaptive brightness.

INSTALLATION
Boot to TWRP, format your data, then proceed to Advanced Wipe and wipe the Dalvik, Cache, Data, System, and Vendor partitions.
Then reboot to TWRP.
Flash repartitioner.zip, flash cleaner.zip, then flash the Evolution X ROM.
Let it install and boot.
If it doesn’t boot, go to TWRP, then change the /data partition to F2FS, reboot to the OS, and boom you just installed Android 16 on a damn 7 to 8 year-old phone.

HOW TO INSTALL THE FIXES
Brightness fix (MANDATORY IF YOU WANT TO SEE SOMETHING ON THE SCREEN):
Install the KernelSU Manager APK included (manager version 0.7.5), then flash the brightness module, reboot, and boom.
If Wi-Fi doesn’t work, just flash the Wi-Fi fix in TWRP after you’ve installed the ROM.
The ROM comes with a pre-rooted kernel (FURINA 4.4). Enjoy the ROM.
I released this ROM here because I’m annoyed by people making ROMs yet never really publicly releasing them, or they do but they’re super hard to find. There are amazing devs making ROMs, yet not many use them because people can’t find them easily on the clearnet, and it’s mostly in some kind of Telegram group.

MY EXPERIENCE
Evo X is a really customizable ROM and gives you a super premium like experience compared to other custom ROMs. It’s kind of an all-in-one ROM: you get root and Evo X settings and quirks, like being able to change the boot animation, font, system theme, icons, fully customizable navbar, and having built-in Play Integrity fixes.
I’ve been using it for about 4 weeks on my S8. Using benchmarking software like AnTuTu gives a score of 398,732, and the average for the S8 is 372,105. This shows it adds more than 20K points 26,627 to be exact.
Battery life is average, and smoothness is like you’re using One UI 7 on a Galaxy S25 like it’s built for it.
One drawback: if you run games like Roblox, Pokémon GO, FNAF, or play 2K–4K videos on YouTube, it tends to heat up.
Still, having root is always nice. It’s KernelSU, and KernelSU vs Magisk has differences: Magisk is systemless root, while KernelSU is newer and offers more integration since it’s kernel-level root and lightweight.
I’d give it an 8/10—Android 16 on a 7-year-old device that runs super smooth. Other Android 16 ROMs I’ve tested/used (coming soon) were a bit more unstable compared to this beast of a ROM.
Bye bye, have fun.
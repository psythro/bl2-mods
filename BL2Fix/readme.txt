----------------------------------------
BL2Fix Readme
----------------------------------------
-------------------------
CONTENTS
-------------------------
1. Installation
2. Mod Details/Credits
3. Discord/Links
4. FAQ/Help

-------------------------
1. INSTALLATION
-------------------------
BL2Fix comes in two versions:
A. BL2FixInstall.zip (Automatic Installation)
B. BL2FixManualInstall.zip (Manual Installation)

BL2FixInstall.zip includes the one-click installer, which is going to be the one you want. Because it is a .exe file, however, some "antivirus" or "antimalware" will detect it as a threat, and automatically block or delete it. It's not a virus, but if you don't trust us, you can do a manual install with BL2FixManualInstall.zip.

BL2FixFiles includes the manual installation. We made this for the people that are more hesitant to run .exe files off the internet, which is understandable. You're more likely to run into issues and it's harder to install so you really should just use the automatic installer, though.



A. Automatic Installation

First download BL2FixInstall.zip. After downloading BL2FixInstall.zip, all you need to do is open the zip file (double click) and then run BL2FixInstall.exe (double click again). If clicking the .exe inside the .zip doesn't work, you might have to right click the .zip file first and "extract" it to be able to run the installer. Once you've successfully run the installer, it should automatically find your Borderlands 2 installation folder and ask for the OK to install. If your Steam or Epic folder is in a very unusual location, however, it may not be able to find it, so you'll have to hit "browse" and manually navigate to your steam or epic folder. If it has found it, just click OK and installation will resume. Once installation is complete, it'll give you the option to automatically set your levelcap to 72. We highly recommend this. If at any point you change your mind and want to choose a different levelcap, all you need to do is navigate to your BL2Fix folder (filepath below) and double click either Level72.bat or Level80.bat while the game isn't running.

Steam Filepath: Steam\steamapps\common\Borderlands 2\Binaries\Win32\Mods\BL2Fix
Epic Filepath: Epic Games\Borderlands 2\Binaries\Win32\Mods\BL2Fix

(You can usually find your Steam or Epic Games installation in \Program Files (x86))

And that's it! The mod will now automatically be running when you launch Borderlands 2. Have Fun!



B. Manual Installation

Download BL2FixManualInstall.zip. Put the contents of the .zip file (should be a Binaries file) in your Borderlands 2 Installation. Do not delete the binaries folder. Replace all when given the option. This will install everything except for the levelcap, which you'll need to do manually with c0dycode's Hex Multitool. It's also an executable, which gets flagged as a virus, so we couldn't include it here. With Hex Multitool, you'll have to navigate to your BL2 install (again) to adjust the level cap yourself. The installer normally installs Hex Multitool creates 2 bat files you can double click to automatically make this change, and also offers to adjust levelcap during install. Link to multitool is in Section 3.

-------------------------
2. MOD DETAILS/CREDITS
-------------------------
BL2Fix is primarily a PythonSDK mod that run a .txt for cutscene skip and utilizes the borderlands hex multitool to adjust your level cap. It may have compatibility issues with other mods if they modify existing loot pools. It includes the functionality of already existing mods, such as cutscene disabler, NoAds, pauseinair, and a select few fixes from the Unofficial Community Patch (UCP). BL2FixInstall.exe will automatically install the PythonSDK, the .py mod and the multitool for you automatically.



BL2Fix was made possible by the following people:

alienoliver - programming, playtesting
Flare2V - design, playtesting
apple1417 - PythonSDK, NoAds, HUGE programming support
c0dycode - hex multitool, programming support
FromDarkHell - cutscene disabler, ucp, programming support
Abahbob - PythonSDK, pauseinair
ShadowEvil - UCP
UCP Team - UCP
Our Beta Testers - basket weaving
You - for gaming

-------------------------
3. DISCORD/LINKS
-------------------------
BL2Fix Discord - https://discord.gg/8NYzdBEUhP
BL2Fix on NexusMods - https://www.nexusmods.com/borderlands2/mods/277
c0dycode's Borderlands Hex Multitool - https://github.com/c0dycode/Borderlands-Hex-Multitool
apple1417's NoAds - https://github.com/apple1417/bl-sdk-mods/tree/master/NoAds
Unofficial Community Patch - https://github.com/BLCM/BLCMods/tree/master/Borderlands%202%20mods/Community%20Patch%20Team
Flare2V's twitch stream - https://www.twitch.tv/flare2v
-------------------------
4. FAQ/HELP
-------------------------
A list of commonly asked questions, with the answers included below.

-Help! Borderlands 2 won't start!
-Help! Borderlands 2 crashed!
-Help! A terrible bug!
-How do I install the mod?
-How do I update the mod?
-How do I disable the mod?
-How do I uninstall the mod?
-How do I change the level cap?
-How do I change the OP level cap?
-Is this mod compatible with other mods?
-Does this mod work in multiplayer?
-Can I use my old characters?
-Why can't I create an online public lobby?
-If I turn off or uninstall the mod, will I lose anything?
-Who made this mod?
-This mod is really really fun/boring/awesome/terrible/broken/etc, how can I give feedback to the devs?
-How can I support the mod creators?
-Help! My question wasn't answered here!


Q: Help! Borderlands 2 won't start!
A: If you're getting the runtime error, that happens sometimes with the PythonSDK. It happens on occasion, just try to run Borderlands 2 again. You might be able to reduce the rate at which it happens by doing the following:
-Restarting your computer
-Updating your GPU drivers
-Downloading the most recent .net Framework https://dotnet.microsoft.com/download/dotnet-framework

Q: Help! Borderlands 2 crashed!
A: Borderlands 2 does that frequently because of Gearbox's most recent updates to the game. Alt-Tabbing out of the game while angel is talking consistently crashes it, so don't do that. The new Ultra HD texture pack also causes it to crash on occasion. You can disable the UHD DLC on steam by right clicking Borderlands 2 in your steam library -> properties -> dlc -> uncheck Borderlands 2 Ultra HD Texture Pack. Should also improve performance and fix a couple lighting issues. If you didn't tab on angel and also don't have the UHD textures installed, please report your crash to the developers in the discord.

Q: Help! A terrible bug!
A: Open your console with tilde and scroll through until you see an error. Take a screenshot of the error and post it on the discord with a brief description of what you were doing when it happened.

Q: How do I install the mod?
A: You can find a complete guide on installing the mod in This Very Readme, under section 1.

Q: How do I update the mod?
A: Download the newest version of the installer and run it like you would to install. It's that easy.

Q: How do I disable the mod?
A: When Borderlands 2 is running, open the "mods" menu (which is found on the main menu), scroll until you find the BL2Fix mod, and hit enter to disable it. You'll have to restart your game for the changes to take effect.

Q: How do I uninstall the mod?
A: Deleting the mod files. This is probably unnecessary, as you can just disable the BL2Fix mod and still have the PythonSDK automaticlly installed in case you want to try other mods, but deleting your binaries folder and then trying to run BL2 on steam should remove the mod. The Binaries folder shouldn't contain any important information (aside from your mod settings), and is only ~40MB.

Q: How do I change the level cap?
A: Navigate to your BL2Fix folder (filepath can be found in section 1. of this readme) and then, while Borderlands 2 is not running, double click either Level72.bat or Level80.bat. If you did the manual install, these won't exist. See section 1.

Q: How do I change the OP level cap?
A: The OP level cap is an option ingame. It can be found under Options -> Mod Options -> BL2Fix.

Q: Is this mod compatible with other mods?
A: Probably not. It should work fine if the other mods don't modify the things we modify (loot pools, xp rates, etc.). We recommend you run this mod without other mods anyways, since this mod is entirely gameplay focused. We playtested it pretty thoroughly, to make sure you get the best possible experience, but if you don't mind nothing working feel free to try it with other mods.

Q: Does this mod work in multiplayer?
A: Yes! Multiplayer is a huge focus with BL2Fix, as we made almost all the loot in the game scale with number of players (multiplayer barely does anything in vanilla). A small few features don't work if you're not the host, such as mission reward rerolling, and cutscene skip only works if everyone has it, but it absolutely works in multiplayer.

Q: Can I use my old characters?
A: Yes. You won't be able to continue your game with a level 80 character if you've selected 72 as your levelcap, however, as it will probably sanitycheck (delete) most of the items in your backpack.

Q: Why can't I create an online public lobby?
A: For the aforementioned reason. Level 80 characters joining levelcap 72 games get wiped.

Q: If I turn off or uninstall the mod, will I lose anything?
A: You'll lose all the fun! Aside from that, your game settings and characters will be fine.

Q: Who made this mod?
A: See Section 3 of the readme.

Q: This mod is really really fun/boring/awesome/terrible/broken/etc, how can I give feedback to the devs?
A: Join the BL2Fix discord! We're looking for any and all feedback. The more information the better. - https://discord.gg/8NYzdBEUhP

Q: How can I support the mod creators?
A: Tell your friends about the mod! The more people playing the mod, the better! Also check the links in section 3.

Q: Help! My question wasn't answered here!
A: Please read through the readme thoroughly. If it doesn't answer your question, read it again. If it really doesn't answer your question, check the nexusmods page. Then read the readme again. If your question isn't answered here, feel free to ask us on discord.













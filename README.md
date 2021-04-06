
![Latest Release](https://img.shields.io/github/v/release/GwendolyneFreddy/Shuri-Ninja?include_prereleases&color=gold)<a name="top" id="top"></a>
![GitHub (Pre-)Release Date](https://img.shields.io/github/release-date-pre/GwendolyneFreddy/Shuri-Ninja?color=gold)
![Platform](https://img.shields.io/static/v1?label=platform&message=windows%20%7C%20Mac%20%7C%20linux&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French&color=limegreen)
<a href="README-FR.md"><img align="right" src="shurininja/readme/images/fr-flag-32.png" title="Readme français"></a>


<div align="center"><h1>Shuri Ninja - Thief kit</h1>

<h3>A mod for Baldur's Gate II:ToB (original and EE games),<br>
Baldur's Gate Trilogy, Tutu, BG:EE, SoD and EET<h3>

</div><br />


**Original Author:** Twinblades2  
**Mod forum:** <a href="https://www.baldursgateworld.fr/lacouronne/modules-crees-ou-en-cours-de-developpement/33164-kit-le-mod-shuri-ninja-est-disponible-pour-les-jeux-ee.html">Shuri Ninja Kit</a>  

## 

[![Created Badge](https://badges.pufler.dev/created/GwendolyneFreddy/Shuri-Ninja?style=plastic)](https://badges.pufler.dev)
![GitHub repo size](https://img.shields.io/github/repo-size/GwendolyneFreddy/Shuri-Ninja?style=plastic)
[![Visits Badge](https://badges.pufler.dev/visits/GwendolyneFreddy/Shuri-Ninja?color=cyan&style=plastic)](https://badges.pufler.dev) 
![Maintenance](https://img.shields.io/static/v1?label=maintained%3F&message=yes&color=greenlight&style=plastic)
![GitHub contributors](https://img.shields.io/github/contributors/GwendolyneFreddy/Shuri-Ninja?color=blueviolet&style=plastic) [![Contributors Display](https://badges.pufler.dev/contributors/GwendolyneFreddy/Shuri-Ninja?size=30&padding=5&bots=true)](https://badges.pufler.dev)

## 

[Read the mod's readme](https://gwendolynefreddy.github.io/docs/lcc/shurininja-readme-english.txt)
## 

<div align="center">
<a href="#intro">Overview</a> &#x2B25; <a href="#compat">Compatibility</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Components</a> &#x2B25; <a href="#credits">Credits</a> &#x2B25; <a href="#version">Version History</a></br>
</div>


<hr>


## <a name="intro" id="intro"></a>Overview

This mod adds a new thief kit to the game: the Shuri Ninja.

Created many years ago by Twinblades2, it has been rewritten to the WeiDU modern standard way of coding and ported to Enhanced Editions games by Aalkaor and Gwendolyne.
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="compat" id="compat"></a>Compatibility

#### Games supported

This mod is designed to work on most Infinity Engine games. This includes:

- The series of Enhanced Editions published by Beamdog, which at present includes Baldur's Gate: Enhanced Edition (BGEE) and Baldur's Gate II: Enhanced Edition (BG2EE). The BGEE Siege of Dragonspear expansion (SoD) is supported as well. All of the Enhanced Edition games include the original expansion packs.
- The original Baldur's Gate II (BG2, or just SoA) with the Throne of Bhaal (ToB) expansion. **Make sure you have Throne of Bhaal patched to version 26498.** Check the ReadMe files related to your patch in your game folder and the <a href="http://www.bioware.com/games/throne_bhaal/support/patches/">BioWare</a> website if necessary.
- The conversion projects based on ToB: <a href="http://www.shsforums.net/forum/261-bgt-weidu/">Baldur's Gate Trilogy (BGT)</a> <a href="https://www.pocketplane.net/bg1tutu/">Baldur's Gate Tutu</a> (Tutu) and <a href="https://github.com/K4thos/EET/releases">Enhanced Edition Trilogy</a> (EET).

## 

#### Other Mods Compatibility

This is a WeiDU mod, and therefore should be compatible with all WeiDU mods. However, we cannot test every single one. Though we are striving to make it compatible with as many other mods as possible, there is always a chance that incompatibilities will arise. Below are the ones discovered thus far:

- <a href="">Kit Revisions</a>

If you encounter any bugs, please <a href="https://www.baldursgateworld.fr/lacouronne/modules-crees-ou-en-cours-de-developpement/33164-kit-le-mod-shuri-ninja-est-disponible-pour-les-jeux-ee.html">report them on the forum!</a>

## 

#### Installation Order

>Although it is not required for the Shuri Ninja mod to function properly, ToB players are strongly recommended to download and install the latest version of the <a href="https://www.gibberlings3.net/mods/fixes/bg2fixpack/">BG2 Fixpack</a> before proceeding with the installation of this mod.<br>

Here is the recommended installation order:
- Please install Shuri Ninja after ToBEx, BG2 Fixpack and EET.
- Please install Shuri Ninja before EET_end, and any final "biffing" routines.
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

*If you've previously installed the mod, remove it before extracting the new version. To do this, run __`setup-shurininja.exe`__, un-install all previously installed components and delete the :file_folder: __shurininja__ folder.*

*When installing or un-installing, __do not close the DOS window__ by clicking on the __X__ button! Instead, press the __Enter__ key whenever instructed to do so.*

*__Disable any antivirus__ or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.*

You can extract files from the archive using <a href="https://www.7-zip.org/download.html">7zip</a>, <a href="https://www.rarlab.com/download.htm">WinRAR</a>, <a href="https://zipgenius.com/">ZipGenius</a> or another file compression utility that handles .zip files.

## 

#### Special Note for Siege of Dragonspear from Steam/GOG</h3>

Good Old Games (GOG) and Steam both package the additional content for Siege of Dragonspear in a method that WeiDU, the tool used to install this mod, cannot access. You must run a program called <a href="https://github.com/Argent77/A7-DlcMerger/releases/latest">DLC Merger</a> on your SoD installation before you can install this or any other WeiDU-based mod.

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### Windows

Shuri Ninja for Windows is distributed as an extractable compressed archive and includes a WeiDU installer.

Extract the contents of the mod archive into the folder of the game you wish to modify (*the folder which contains the "CHITIN.KEY" file*). On successful extraction, there should be a :file_folder: shurininja folder and a setup-shurininja.exe file in your game folder. To install, simply double-click **`setup-shurininja.exe`** and follow the instructions on screen.

Run **`setup-shurininja.exe`** in your game folder to reinstall, un-install or otherwise change components.

## 

#### Mac OS X

Shuri Ninja for Mac OS X is distributed in the same compressed archive and includes a WeiDU installer.

First, extract the files from the archive into your game directory. On successful extraction, there should be a :file_folder: shurininja folder, setup-shurininja and setup-shurininja.command files in your game folder. To install, simply double-click **`setup-shurininja.command`** and follow the instructions on screen.

Run **`setup-shurininja.command`** in your game folder to reinstall, un-install or otherwise change the components settings.

## 

#### Linux

Shuri Ninja for Linux is distributed in the same compressed archive and does not include a WeiDU installer.

Extract the contents of the mod to the folder of the game you wish to modify.

Download the latest version of WeiDU for Linux from <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU</a> and copy weidu and weinstall to `/usr/bin`. Following that, open a terminal, **`cd`** to your game installation directory, run tolower and answer 'Y' to both queries. You can avoid running the second option (linux.ini) if you've already ran it once in the same directory. To save time, the archive is already tolowered, so there's no need to run the first option (lowercasing file names) either if you've extracted only this mod since the last time you lowercased file names. If you're unsure, running tolower and choosing both options is the safe bet.

To install, run **`weinstall setup-shurininja`** in your game folder. Then run **`wine bgmain.exe`** (or **`wine baldur.exe`** for EE games), and start playing.

## 

#### Note for Complete Un-installation

In addition to the methods above for removing individual components, you can completely un-install the mod using **`setup-shurininja --uninstall`** at the command line to remove all components without wading through prompts.
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

The installer includes the following components. The number of each is the component *`DESIGNATED`* number which gives it a fixed install position, lets other components detect it and allows automated installers to specify component choices.

## 

#### [10] Shuri Ninja Kit (legacy)

This component installs the original thief kit.

&#9755; :warning: Due to IE limitations, it is not possible to restrict weapons the Shuri Ninja can equip to katana, scimitar, dagger, short bow and dart, without breaking other mods compatibility. **This feature is only available in EE games.**

<details><summary><ins>Kit description</ins></summary>
<p></br>
Shuri Ninjas are trained by the Shurikai, an organisation of ninja assassins that operate across Kara-Tur. They are quick, deadly, masters of stealth and highly skilled in the use of oriental blades, hand thrown weapons and archery. It is guaranteed if one is marked by the Shurikai they will die that night. Their lethal skills have earned them the respect and intense hatred of Samurai and other rival ninja clans. Very few warriors have crossed blade with a shuri ninja and lived to tell the tale.

Many leave the Shurikai to follow their own paths at the cost of constantly watching their backs for the blades of former comrades. Their services are highly sought after by the western thief guilds if they make it to the western lands alive. None dare double cross them as entire guilds have met their deaths by a single Shuri Ninja. Due to the rarity of demi-humans in Kara-Tur only humans are trusted with the secrets of Shurikai Ninjutsu.

Advantages:
- +20% bonus to Hide in Shadows and Move Silently.
- +2 bonus to Dexterity.
- At high levels, gains the fighter's special abilities.
- +1 bonus to hit and damage rolls every 4 levels, starting at 4th level.
- +1 bonus to Armor Class every 5 levels, starting at 5th level.
- May Specialize (two slots) in katana, scimitar, dagger, dart and short bow.
- May achieve Specialization (two slots) in Single-Weapon Style and allocate three slots in Two-Weapon Style.

As Shuri Ninjas increase in level, they learn new deadly techniques to aid them in combat or assassination:
- 5th level (Blue Belt): Learns to detect illusions (may use the True sight ability twice per day).
- 10th level (Purple Belt): Learns to strike opponents at pressure points (may use the Stunning Blow ability twice per day). All successful attacks within the next round force the victim to save vs. Spell or be stunned. spcl811
- 15th level (Red Belt): Learns to maximise the damage they deal for a limited time (may use the Blinding Strike ability once per day, and gains an additional use every 10 levels thereafter). All successful attacks within the next 10 seconds deal maximum damage.
- 20th level (Brown Belt): Learns to use the monk's Quivering Palm ability once per day (The secret was stolen from an eastern monastery). The next successful attack forces the opponent to save vs. Spell or die.  spcl820
- 25th level (Black Belt): Learns to coat their weapons with poison (may use the Poison Weapon ability once a day).
- 30th level: Learns to strengthen their minds against all mental attacks (may use the Chaotic Commands ability once per day). Gains an additional +20% bonus to Hide in Shadows and Move Silently.
- 35th level (First Dan): Their skill in combat increases (+1 bonus to THAC0). Gains an additional use of the Poison Weapon ability.

POISON WEAPON</br>
Each successful hit within the next 5 rounds will inject poison into the target. Each target can only be affected once per round. The amount of poison damage depends on the character's level:
- 1st: Target suffers 1 poison damage per second for 6 seconds (Save vs. Death at +1 negates)
- 5th: Target suffers 1 poison damage per second for 12 seconds (Save vs. Death negates), and also immediately suffers 2 poison damage (no save)
- 9th: Target suffers 1 poison damage per second for 18 seconds (Save vs. Death at -1 negates), and also immediately suffers 4 poison damage (no save)
- 13th: Target suffers 1 poison damage per second for 24 seconds (Save vs. Death at -2 negates), and also immediately suffers 6 poison damage (no save)


Disadvantages:
- May not use the Set Snare ability.
- Incurs a -2 penalty to Strength, Constitution and Charisma.
- May only use the following weapons: katana, scimitar, dagger, short bow and dart. (**EE games**)
- May only use the following weapons: long sword, short sword, katana, scimitar, dagger, club, quarterstaff, crossbow, short bow, dart and sling. (**classic games**)
- May not place any slots in Two-Handed Weapon Style and Sword and Shield Style.
- May not dual class.
- Alignment restricted to any chaotic.
- Race restricted to human.
</p>
</details>

## 

The two next components don't need further explanation, I guess. &#128521;</br>

#### [20] Shuri Ninja Kit may not wear heavier armor than leather (EE only)

## 

#### [30] Shuri Ninja Kit may not wear any armor (EE only)
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

&#9755; For support or questions, please visit the <a href="https://www.baldursgateworld.fr/lacouronne/modules-crees-ou-en-cours-de-developpement/33166-shuri-ninja-kit-rapport-de-bugs-bug-reports.html">mod forum</a>.

## 

**Author:** Twinblades2 (at twblds@hotmail.com)  
**Support:** <a href="https://www.baldursgateworld.fr/lacouronne/members/freddy_gwendo.html">Gwendolyne</a>

## 

#### Special Acknowledgements to:

- <a href="https://www.baldursgateworld.fr/lacouronne/members/aalkaor.html">Aalkaor</a> for having dug up this old mod, translated it into French and begun its WeiDU coding.
- <a href="https://www.baldursgateworld.fr/lacouronne/members/freddy_gwendo.html">Gwendolyne</a> for having completed the WeiDU coding, made it EE compatible, and proofread the translation.

## 

#### Programs/tools used in creation (among others)

- <a href="https://github.com/WeiDUorg/weidu/releases">WeiDU</a> by Wes Weimer, the bigg and Wisp.
- <a href="https://gibberlings3.github.io/iesdp/">IESDP</a>, maintained by igi and lynx.
- <a href="https://github.com/Argent77/NearInfinity/releases">Near Infinity</a>, by Jon Olav Hauglid, FredSRichardson, and Argent77.
- <a href="https://www.gibberlings3.net/mods/tools/dltcep/">DLTCEP</a>, by Avenger.
- <a href="http://notepad-plus-plus.org/">Notepad++</a> by the Notepad++ team, Don Ho, and the spellcheck plug-in.
- <a href="http://www.shsforums.net/files/file/1048-weidu-highlighter-for-notepad/">WeiDU Notepad++ Highlighters </a> by Argent77.
- <a href="https://www.bulkrenameutility.co.uk/">Bulk Rename Utility</a>, by TGRMN Software.

## 

#### Copyrights Information

###### Shuri Ninja is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Twinblades2, based on material from the game Baldur's Gate II and its expansion.
###### All mod content is &copy;Twinblades2.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.

###### This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.<br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Versions History

##### Version 2.0.0 &nbsp;(April 6, 2021)

- Added *shurininja.ini* metadata file to support AL|EN's "Project Infinity".
- Renamed *Setup-Shurinin.tp2* -> *shurininja.tp2* to support AL|EN's "Project Infinity".
- Replaced `AUTHOR` keyword with `SUPPORT`.
- Added `VERSION` flag.
- Replaced `AT_INTERACTIVE_EXIT` deprecated command with `README`.
- Added `HANDLE_CHARSETS` function to convert string entries for EE games.
- Added `REQUIRE_PREDICATE` conditions to avoid installing the mod in inaccurate games.
- Added components `DESIGNATED` numbers and "*gw_shuri_ninja_kit_original*", "*gw_shuri_ninja_kit_only_leather*" and "*gw_shuri_ninja_kit_no_armor*" `LABELS`.
- Added "*always.tpa*" library.
- Externalized tp2 code into *main_component.tpa* library for more comfortable readability and maintenance. :wink:.
- Commented code as much as possible.
- Added two sub-components (EE only): "*Shuri Ninja may not wear heavier armor than leather*" and "*Shuri Ninja may not wear any armor*".
- Added native BG:EE and BG2EE compatibility (probably with EET, but not yet tested):
  - Added armor restrictions (new sub-components).
  - Added weapons restriction: from now on, Shuri Ninja can't equip long sword, short sword, quarterstaff, club, crossbow and sling, as per description. Unfortunately, IE limitations does not allow to code it for classic games, without breaking other mods compatibility.
  - Shuri Ninja can't wear any shield.
  - Added specific Stunning Blow and Quivering Palm abilities: applied op#248 to any weapon wielded (EE games: parameter2 is set to 4 - fists only).
- BGT, tutu and IWD:EE: Added katanas, Ninjatos and Wakizashis to the games, so that she Shuri Ninja kit should be friendly playable.
- Removed one extra Blinding strike at 40th level.
- Fixed innate Chaotic Commands ability: duration reduced to 1 turn and included a few <a href="https://www.gibberlings3.net/forums/topic/29670-is-this-possible-to-add-in-bg2-fixpack/?tab=comments#comment-263138">fixes</a>.
- Fixed wrong proficiencies pips.
- No longer overwrites system files (cloned and patched existing SPL files to improve compatibility).
- Handled special classic game engine restriction: kit descriptions can't exceed 4815 characters, or the game crashes at chargen!.
- Updated and renamed readme file to "*shurininja-readme-%LANGUAGE%.txt*" (Shuri Ninja now supports translated readmes).
- Proofread English texts (Gwendolyne).
- Added French translation, including readme (Aalkaor and Gwendolyne).
- Traification. Feel free to provide me with translations. I will include them as soon as possible.
- Removed unused files and "*backup*" folder.
- Reorganized mod architecture tree: created or renamed folders to sort files according to their types.
- Lower cased files. 
- Included Linux and Mac Os X versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Added archive libiconv-1.9.2-1-src.7z with iconv licence info.
- Updated WeiDU installer to v247.

## 

##### Version 1 &nbsp;(February 10, 2004)

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>

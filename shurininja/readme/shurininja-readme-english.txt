Shuri Ninja kit
_______________

 
Version:    2.0.0
Author:     Twinblades2
Support:    Aalkaor and Gwendolyne
Languages:  English, French
Platform:   Windows

Download:   https://github.com/GwendolyneFreddy/Shuri-Ninja/releases/latest
Discussion: 
https://lynxlynx.info/ie/modhub.php?GwendolyneFreddy/Shuri-Ninja



Overview
========

This mod adds a new thief kit to the game: the Shuri Ninja.
Created many years ago by Twinblades2, it has been rewritten to the WeiDU modern standard way of coding and ported to Enhanced Editions games by Aalkaor and Gwendolyne.



Compatibility
=============

This mod is designed to work on the following Infinity Engine games: Baldur's Gate: Enhanced Edition (BGEE), Baldur's Gate II: Enhanced Edition (BG2EE), the original Baldur's Gate II (BG2 or just SoA) with the Throne of Bhaal (ToB) expansion, the conversion projects Baldur's Gate Trilogy (BGT) and Enhanced Edition Trilogy (EET). The BGEE Siege of Dragonspear expansion (SoD) is supported as well.

Shuri Ninja is a WeiDU mod, and therefore should be compatible with all WeiDU mods. However, we cannot test every single one. If you encounter any bugs, please report them on the forum!

Though I am striving to make Shuri-Ninja compatible with as many other mods as possible, there is always a chance that incompatibilities will arise. Below are the ones discovered thus far:

  - Shuri-Ninja is not compatible with Kit Revisions.


Classical games player are also strongly recommended to download and install the BG2 Fixpack (http://www.gibberlings3.net/bg2fixpack/ ) before proceeding with the installation of this mod.



Installation
============

1. Notes

If you have previously installed the mod, remove it before extracting the new version. To do this, run setup-shurininja.exe, uninstall the previously installed main component and delete the shurininja folder.

When installing or uninstalling, do not close the DOS window by clicking on the X button! Instead, press the Enter key whenever instructed to do so.

Disable any antivirus or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.


2. Special Note for Siege of Dragonspear from Steam/GOG

Good Old Games (GOG) and Steam both package the additional content for Siege of Dragonspear in a method that WeiDU, the tool used to install this mod, cannot access. You must run a program called Modmerge (https://forums.beamdog.com/discussion/50441/modmerge-merge-your-steam-gog-zip-based-dlc-into-something-weidu-nearinfinity-dltcep-can-use/p1 ) on your SoD installation before you can install this or any other WeiDU-based mod.


3. Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.


4. Windows

Shuri-Ninja for Windows is distributed as an extractable compressed archive and includes a WeiDU installer.

Extract the contents of the mod archive into the folder of the game you wish to modify (the folder which contains the "CHITIN.KEY" file, using 7zip (http://www.7-zip.org/download.html ), WinRAR (http://www.rarlab.com/download.htm ), or another file compression utility that handles .zip files. On successful extraction, there should be a shurininja folder and a setup-shurininja.exe file in your game folder. To install, double-click setup-shurininja.exe and follow the instructions on screen.

You can run setup-shurininja.exe in your game folder to reinstall, uninstall or otherwise change the component settings.

5. Note for Complete Uninstallation

In addition to the methods above for removing individual components, you can completely uninstall the mod using "setup-shurininja --uninstall" at the command line to remove all components without wading through prompts.



Components
==========

The installer includes the following components. The number of each is the component DESIGNATED number which gives it a fixed install position, lets other components detect it and allows automated installers like the BiG World Setup specify component choices.

10. Shuri Ninja Kit (legacy)

Kit Description:

Shuri Ninja are trained by the Shurikai, an organisation of ninja assassins that operate across Kara-Tur. They are quick, deadly, masters of stealth and highly skilled in the use of oriental blades, hand thrown weapons and archery. It is guaranteed if one is marked by the Shurikai they will die that night. Their lethal skills have earned them the respect and intense hatred of Samurai and other rival ninja clans. Very few warriors have crossed blade with a shuri ninja and lived to tell the tale.

Many leave the Shurikai to follow their own paths at the cost of constantly watching their backs for the blades of former comrades. Their services are highly sought after by the western thief guilds if they make it to the western lands alive. None dare double cross them as entire guilds have met their deaths by a single shuri ninja. Due to the rarity of demi-humans in Kara-Tur only humans are trusted with the secrets of Shurikai Ninjutsu.

Advantages:
- +20% bonus to Hide In Shadows and Move Silently.
- +2 bonus to Dexterity.
- At high levels, gain the fighter's special abilities.
- +1 bonus to hit and damage rolls every 4 levels, starting at 4th level.
- +1 bonus to Armor Class every 5 levels, starting at 5th level.
- May Specialize (two slots) in katana, scimitar, dagger, dart and short bow.
- May achieve Specialization (two slots) in Single-Weapon Style and allocate three slots in Two-Weapon Style.

- As Shuri Ninja increase in level they learn new deadly techniques to aid them in combat or assassination.
  * 5th level (Blue Belt): Learns to detect illusions (may use the True sight ability twice per day).
  * 10th level (Purple Belt): Learns to strike opponents at pressure points (may use the Stunning Blow ability twice per day). All successful attacks within the next round force the victim to save vs. Spell or be stunned.
  * 15th level (Red Belt): Learns to maximise the damage they deal for a limited time (may use the Blinding Strike ability once per day, and gains an additional use every 10 levels thereafter). All successful attacks within the next 10 seconds deal maximum damage.
  * 20th level (Brown Belt): Learns to use the monk's Quivering Palm ability once per day (The secret was stolen from an eastern monastery). The next successful attack forces the opponent to save vs. Spell or die. 
  * 25th level (Black Belt): Learns to coat their weapons with poison (may use the Poison Weapon ability once a day).
  * 30th level: Learns to strengthen their minds against all mental attacks (may use the Chaotic Commands ability once per day). Gains an additional +20% bonus to Hide In Shadows and Move Silently.
  * 35th level (First Dan): Their skill in combat increases (+1 bonus THAC0). Gains an additional use of the Poison Weapon ability.

POISON WEAPON
Each successful hit within the next 5 rounds will inject poison into the target. Each target can only be affected once per round. The amount of poison damage depends on the character's level:
1st - Target suffers 1 poison damage per second for 6 seconds (Save vs. Death at +1 negates)
5th - Target suffers 1 poison damage per second for 12 seconds (Save vs. Death negates), and also immediately suffers 2 poison damage (no save)
9th - Target suffers 1 poison damage per second for 18 seconds (Save vs. Death at -1 negates), and also immediately suffers 4 poison damage (no save)
13th - Target suffers 1 poison damage per second for 24 seconds (Save vs. Death at -2 negates), and also immediately suffers 6 poison damage (no save)


Disadvantages:
- May not use the Set Snare ability
- Incurs a -2 penalty to Strength, Constitution and Charisma.
- May only use the following weapons: katana, scimitar, dagger, dart and bow.
- May not place any slots in Two-Handed Weapon Style and Sword and Shield Style.
- May not dual class.
- Alignment restricted to any chaotic.
- Race restricted to human.


The two next components don't need further explanation, I guess...

20. Shuri Ninja Kit may not wear heavier armor than leather (EE only)

30. Shuri Ninja Kit may not wear any armor (EE only)



Credits and Acknowledgements
============================

- Author: Twinblades2 (at twblds@hotmail.com)


- Special Acknowledgements to:

    - Aalkaor for having dug up this old mod, translated it into French and begun its WeiDU coding.
    - Gwendolyne for having completed the WeiDU coding, made it EE compatible, and proofread the translation.


- Copyright Information

Shuri Ninja is not developed, supported, or endorsed by BioWare™ or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Twinblades2, based on material from the game Baldur's Gate II and its expansion.
Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal © TSR, Inc. The BioWare Infinity Engine is © BioWare Corp. All other trademarks and copyrights are property of their respective owners.

This mod was created to be freely enjoyed by all Baldur's Gate II players, and its content is free of rights. However, it should not be sold, published, compiled or redistributed in any form without the consent of the author.



Versions History
================

Version 2.0.0 - September nn, 2019

- tp2 split into components and commented for easier further updates.
- Reorganized components (DESIGNATED numbers).
- Added two sub-components (EE only): Shuri Ninja Kit may not wear heavier armor than leather and may not wear any armor.
- Added BG2EE compatibility (probably with EET, but not yet tested).
- No longer overwrites system files.
- Used HANDLE_CHARSETS function to add BG2EE compatibility for languages other than English.
- Deleted unused files from mod folder.
- Updated readme (Shri-Ninja now supports translated readmes).
- Added French translation, including readme (Aalkaor and Gwendolyne).
- Traification.
- Added shurininja.ini metadata file to support AL|EN's "Project Infinity".
- Updated installer WeiDU to v246.


Version 1 - February 10, 2004
- Initial release


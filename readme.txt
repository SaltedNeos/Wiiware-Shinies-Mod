Pokémon Mystery Dungeon: Adventure Squad Shiny Patch Readme:
Version 1.0
Shiny Patch By: SaltedNeos

This mod was built on top of the previous English Translation project for these games,
and attempts to add all missing shiny Pokemon into the game. Currently shiny Pokemon
will only use their shiny textures in games where they can normally be recruited due
to a corruption error that I couldn't figure out how to get around. Additionally,
Arceus does not currently use its shiny textures when shiny. These two issues will
hopefully be addressed in a future patch. 

Shiny Pokemon taken from one game to another still functionally behave as shinies
would, including the 200 belly stat upon entering dungeons, and will use their
shiny textures again when brought back to the game that has them.

Only regular wild Pokemon in dungeons have been verified to be functioning as of 
right now. It is unknown if mission clients, bosses, or the Legendary Beasts that 
join in town can be shiny.

The readme for the original translation patch is included below, which includes installation instructions
(with the new patch names replacing the old ones), an FAQ, and the credits for the original project!

Would also like to thank AbsolBlogsPokemon or "WindyPrairie" for allowing me to use textures from Rumble
Weekend Edition for this project and the team behind the original English Translation Project for all their
hard work on both researching these games, and translating the games to make them more accessible!
========================================================================================================================
Pokémon Mystery Dungeon: Adventure Squad Series Readme:
Version 1.03

NOTE:
 If you had the Japanese version or an earlier release previously played on Dolphin, be sure to uninstall it from
 your NAND by right clicking it on Dolphin's home screen before loading the translated .WAD file. If updating on 
 a homebrewed Wii, first uninstall the game from the home screen and reinstall the game with a Wad Manager.
========================================================================================================================
Changelog:
-1.03 Team Name limit extended from 5 to 8. No other changes. Go into the Main Menu->Others->Team Name to update
 your team name with this new limit, if you like.
-1.02
 .Added "Change Nickname" option to party menu to allow people who originally played the Japanese game to correct
  their names (or anyone to change nickname whenever, really.)
 .Typo fixes to Pokémon names, misc script fixes
 .Corrected error with header patch
-1.01 Fix error with descriptions of: Mud-Slap through Leer. Typo/linebreak error fixes.
-1.0  initial release
========================================================================================================================
Instructions: Use a .bps patcher such as Flips: https://www.smwcentral.net/?p=section&a=details&id=11474
PMD_Radiant_AllShinies_v1.0.bps can be applied to: Pokémon Fushigi no Dungeon: Mezase! Hikari no Boukendan : Pokémon Mystery Dungeon: Radiant  Adventure Squad
PMD_Wildfire_AllShinies_v1.0.bps  can be applied to: Pokémon Fushigi no Dungeon: Susume! Honoo  no Boukendan : Pokémon Mystery Dungeon: Wildfire Adventure Squad
PMD_Tempest_AllShinies_v1.0.bps  can be applied to: Pokémon Fushigi no Dungeon: Ikuzo!  Arashi no Boukendan : Pokémon Mystery Dungeon: Tempest  Adventure Squad

If Flips says the file is incorrect, try applying the header patch to your base WAD first.
There are two dumps of the WAD floating around with differences in header/footer.

Known Errors:
-Slowking's team sort menu does not properly sort alphabetically due to changes to the name screen.

-DS Download Play features have not been translated. They are still functional, but your team
 leader's name may appear incorrectly and move names remain in Japanese.

========================================================================================================================
FAQ about the game/translation:
1:Which version should I play? What's the difference?
 The games have the same plot, but Pokémon appearing in dungeons differ between the three.
  -Radiant version has primarily Elecric-type/yellow-colored starters
  -Tempest version has primarily Water-type/blue-colored starters
  -Wildfire version has primarly Fire-type/red-colored starters
 The save files for all three games are linked. Recruiting a team member or placing an item
 in storage allows it to be used in all three games, so please pick whichever one you'd like.
 
2:What should I expect from the game compared to the other Pokémon Mystery Dungeon games?
 These games were released on the Japanese Wii Shop Channel for 1,200 Nintendo Points each;
 that's about a third of the price of a regular Pokémon Mystery Dungeon game. The plot is
 relatively light, but the games include every Pokémon through Generation 4 and have unique
 mechanics that haven't reappeared in the series since. 

3: Why these titles over X title? Why was this term translated this way?
 The three subtitles were named after Looplets in Super Mystery Dungeon; the set included
 names of other games in the series, and we wanted to preserve the connection to the 3DS
 title, as characters and items from this game also made appearances there. Names of new
 mechanics and items have been localized to the best of our ability.
 
4:Do passwords to unlock Pokémon still work in the translation?
 The new Buddy Passwords can be found by pushing the Home button on your Wii console or emulator,
 then clicking Operations Guide. Due to a few changes to the name entry screen, the passwords are
 different from the original Japanese game. We opted not to use certain currently-in-use terms
 among fans, like "Pal Password", over concerns that those looking for the updated passwords from
 this game only find the listings from the original release. Note that the online manual for this
 game is inactive, and may crash, so please do not attempt to access it via the Operations Guide
 screen.
 
5:Are event Pokémon included in the game/can every Pokémon be recruited? Is there online support?
 This translation is prepatched with Wiimmfi and RiiConnect24. Our team worked with the server owners
 to restore these lost events. All of the known event Pokémon have been restored and should be fully
 functional. From the Main Menu, turn the Distribution Service on to allow connection to RiiConnect24,
 and check for Wii-Mail on your home menu. To receive the other event Pokémon, access Wonder Mail W to
 see a list of event missions and enter Buddy Passwords for other exclusive Pokémon.
 
 For information on setting your system up for Wiimmfi support, please check https://wii.guide/wiimmfi.html
 For information on setting your system up for RiiConnect24 support, please check https://wii.guide/riiconnect24

Events distributed:
 -Wiimmfi: Dialga, Giratina, and Arceus are available at all times via Wonder Mail W.
 -RiiConnect24: cycles Mew, Darkrai, Jirachi and Palkia on a monthly basis, with the Pokémon switching on the first of each month.
  Your Wii Console's date must be set to match the current timeframe or the events will not work. Talk to Farfetch'd after receiving
  the Wii-Mail to activate them.
 
Friend Rescues are not currently supported as of 4-28-2020 (v1.0 release date).
If they are restored in the future, the changes necessary are server-side, so there should be no need to update
the patch. Dates sent via Wii-Mail reflect the original distributions and may not be accurate, but the events
will be in rotation each month.

6: How do I make this work on my PAL/NTSC/etc. Wii:
 You can use ShowMiiWads to change the .wad file's region. For PAL users: Due to a difference in the way the
 games are rendered between NTSC/PAL the game may show a black screen upon loading. This is remedied by going
 into Wii System Settings > Screen and changing the display settings from 60hz mode to 50hz mode.
 https://www.wiibrew.org/wiki/ShowMiiWads

7:Are the games canon to the series?
 A few characters and items originating in this game also appear as cameos in Super Mystery Dungeon,
 but its plot and events are overall not connected. We worked to keep those references intact and
 consistent

8: Why am I getting doubled inputs (Dolphin)?
 This game supports multiple controller types. By default, Dolphin has both the Wii Remote and a standard
 controller sumultaneously enabled. Please go into your controller settings and disable the Wii Remote or
 controller so that only one is active.
========================================================================================================================

Additional Info/Technical Modifications:

This game's item database was modified from Explorers of Sky's. Unused items in the code were found
to have leftover data from this port; most were fully functional, and some even had unique models, so
these have been restored. They have not been added into the main game, however, so they require
Action Replay/cheats to access. In the original Japanese game, these did not have their names (these were blank)
and all displayed as Plain Seeds until a bit was unset in order to re-enable them.

 These include the following fully-functional items:
  -Trap Scarf, Goggle Specs, Space Globe, the Seven Treasures, Amber Tear, Gabite Scale, Sizebust Orb
   Lost Loot, Gold Fang, Corsola Twig, Cacnea Spike, Rare Fossil, Tight Belt, Wonder Chest,
   Unown Stones, some TMs, and the color Bow items.

 Partial functionality exists for the following items, which may have unique models not seen elsewhere:
  -Link Box (opens the move menu, but does not allow move linking; code does still exist for
    linking, however, which seems to work fine even with the Stack mechanic)
  -Exclusive Items: No functionality, but some have unique models.

 Unused moves from Rescue Team: Excavate, and Spin Slash, remained in the code, but had their names
  blanked out. These have been assigned their proper names, but beyond script modifications, remained
  untouched. Please enjoy discovering some of these unique development relics via cheats.
---
Item Icons from Super Mystery Dungeon have been upscaled and used in the game. These were not in the
original Japanese release.
---
SOS Mail system has been reworked to use keywords from Pokémon Ruby/Sapphire/Emerald's EasyChat as a basis for
space reasons.
========================================================================================================================
 Thank you for playing our translation. Please support official Pokémon merchandise, including an official translation
 in the event one is released.
========================================================================================================================
Credits:
SpecialAgentApe: 	Hacking, Gameplay Text Porting, Splash Screen Artwork, Localization
Higsby: 			Story Translation
Lonechallenger: 	Minor Translation
Megaminerd: 		Hacking
kkzero:				Hacking
wowjinxy:			Splash Screen Hacking
Anonymous (Linoone):Font
ShinxHijinx: 		Testing/Gummi artwork
Rocket: 			Testing
Aaron: 				Testing
MandL27:			Testing
Lady Ariel:			Testing
Sliter:				Logos
Davin Ockerby:		AT7 Research
Gericom:			AT7 Research
Darkshade: 			Graphic Design/Wi-Fi Restoration
Friendsxix: 		Wi-Fi Restoration
shutterbug2000:		Wi-Fi Restoration
Larsenv:			Wi-Fi Restoration
mm201:  			Wi-Fi Restoration
Billy-: 			Wi-Fi Restoration
Special Thanks to Project Pokémon staff and researchers 

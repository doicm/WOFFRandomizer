Randomizer - World of Final Fantasy
=====================================================================
Mod Created By:	Doicm (decentdoicm)

Special Thanks:	WoFF modding community for tools and information,
various Discord servers for information on advice for programming,
and Surihia for csv/csh conversion tool that this tool uses.

Version: 
=====================================================================
0.1.7

Notes:
=====================================================================

1.) In order to install and uninstall this, you will need to 
locate your WOFF executable as part of the process.
To find, go to Steam and right-click the game "World of Final
Fantasy, click Manage -> Browse local files.... It should take
you to the folder. 

2.) I highly recommend creating a backup of your primary
save file. You can usually find it on Windows in the following:

&ensp;%USERPROFILE%\Documents\My Games\WOFF\<user-id>\savedata\

or in Linux on the following:

&ensp;<SteamLibrary-folder>/steamapps/compatdata/552700/pfx/

Description:
=====================================================================
This mod is designed to work with World of Final Fantasy: Maxima
for Steam. The regular version without the expansion will not work.

These are the features currently implemented for randomizing:

- **Shuffle Treasure Chests:** This shuffles most of the treasure
chest contents in the game up to ending. Counts of items and some
specialty items not included.
- **Shuffle Random Encounters:** This shuffles the random encounters
around that appear up to ending. This doesn't include postgame
encounters.
- **Shuffle Rare Mirages:** This shuffles most of the rare monster
battles.
- **Shuffle Bosses:** This shuffles bosses that appear during the
main story, starting from Watchplains. This doesn't include some
bosses such as Exnine fights.
- **Shuffle Murkrifts:** This shuffles murkrift enemies except
for Behemoth at the beginning and the rare monster fight in the
Train Graveyard.
- **Shuffle Nodes:** This shuffles most of the nodes between
mirageboards for mirages. Some nodes are excluded that are either
not functional or cause the game to softlock. Some nodes may also
repeat or be entirely useless, but that's how shuffling works for
now. Mirage-specific ability animations have interesting effects,
but should not cause crashes.
- **Shuffle Sizes:** This shuffles the sizes around that mirages can
be. This does not include XL. This may cause some interesting
behaviors with stacks. Stack ability animations are disabled to
prevent crashes. **WARNING:** If randomizing in the middle of a
playthrough, please remove mirages from all stacks and save
before shuffling.
- **Shuffle Intervention/Coliseum Rewards:** This shuffles the prizes
that can be obtained between the arena and intervention quests. NPC
quests are not included. Repeat attempts are not included. This also
includes the Tama quest. ??? mementos are no longer hidden.
- **Randomize Mirage Stats:** This randomizes the stats and growths
that each mirage has. This may affect enemies as well as mirage allies.
This only randomizes HP, Str, Def, Mag, MDef, and Agi.

There are also the following features for QoL or for fun:

- **Double Exp and Gil Earned:** This doubles experience and gil
earned in all battles.

Instructions:
=====================================================================
Find the latest release in the releases section on Github, then
download the zip and extract it to a destination of your choosing.
Run WOFFRandomizer.exe and follow the directions for installing. 

If you run into issues with uninstalling, you should be able to 
restore your files by verifying your files on Steam. Hopefully
it won't come to this, but this is just in case.

For those who are stuck or need additional help, there are log
files that will show information upon generating a randomizer seed.
These are available in the logs directory.

Please do not modify the files in the database directory, as this
can break things.

Changelog:
=====================================================================
2025-13-4 - 0.1.7 - Mirage stat randomization added. Fixed enemy 
logs, mirage maps, boss/rare mirage level balance. Changed some 
murkrift rando features to exclude some airship fights. Put Mel back
in mirageboard rotation.

2025-9-4 - 0.1.6 completed. Murkrift shuffling added. Fixed 
mirageboard shuffling. Experience points for bosses and rare 
monster fights adjusted. Mirageboard log added. Maxima is full
focus, so Coeurl/Lesser Coeurl added to random encounter pool.
Kyubi added in boss shuffle.

2025-6-4 - 0.1.5 completed. Added intervention/coliseum reward
  shuffle, mirage size shuffle, and double exp/gil earn feature

2025-4-4 - 0.1.2 completed, implemented treasure chest rando,
  split random encounter/rare monster/boss rando
  
2025-1-4 - 0.1.1 completed, implemented boss rando

2025-30-3 - 0.1.0 completed





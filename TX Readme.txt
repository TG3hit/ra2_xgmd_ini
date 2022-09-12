Terrain Expansion 2.02. 09/02/04
Home site http://tx.cannis.net/
Forum http://cannis.net/
For most maps for Yuri's Revenge
Contents
1. Updates and fixes to (TX) 2.02
2. Install Information
3. Uninstall Information
4. Requirements
5. Modifications
6. Known Bugs
7. Credits
8. Disclaimer
9. Legal

Important NOTE: This may not work properly with a on-line player with out the (TX) 2.02 installed do to some of the tile fixes. If you do encounter a internal error will playing on-line have the other player upgrade to (TX) 2.02. Sorry for the inconvenience but it was the only way to fix some of the annoying problem.

===1 Updates and fixes to (TX) 2.02===

1 Lunar contral.ini file fix the mono tunnels had the incorrect name. old dtunnt, new tunnel.

=== Updates and fixes to (TX) 2.01===


1 Tunnel top “covering large units” fix. Except lunar that has its on problems. And snow where blade reallocated the tops witch has no problem.
2 A part of the tunnel not passable fixed. "note this is part of a hard code problem but I found a way around it"
3 Broken roads not passable fixed now passable.*
4 Grass train crossing graphics fixit. 
5 Graphics fixed for water tunnels (if you don’t like them to bad I have a limited color pallet to work from). 
6 New Urban bridge’s graphics fixed.
7 New Urban “urban water caves” graphics fixed.
8 New Urban “water breakers” graphics fixed.
9 Some miscellaneous tiles fixed.
10 Waterfalls overlay problem when the overlay overlaps the cliffs is fixed.
11 parking/swimming pool terrain type fix "for both (TX) and original game."*

Note * this may cause game problems if both players don't have Terrain Expansion 2.01.


===2 To install===
To install the (TX) simply place the expandmd06.mix into the RA2 directory. No changes will be obvious without (TX) maps or (TX) ready mod.

Note if you play multiplayer (TX) maps online, the other players must have the (TX) installed. The (TX) should be installed by all players even if you play the original (non- 

(TX)) maps on-line there are tile types fixes that may cause some problems like internal error during play. In these cases they may need to install to the terrain 

expansion).There are only a few mods that will require you to remove the (TX) module. In all other cases you can leave the (TX) module in the RA2 directory. It will only be 

used when called for by a map or a mod.

To edit maps with the Terrain Expansion use XCC mixer to extract the desertmd.ini, lunarmd.ini, snowmd.ini, temperatmd.ini, urbanmd.ini and urbannmd.ini into the RA2 

directory from expandmd06.mix and place the FAData.ini and FALanguage.ini file into you Final Alert directory so that Final Alert 2 can see the new tiles.

P.S. keep a copy of the original FAData.ini and FALanguage.ini file so you can restore them if you need to.

===3 To Uninstall===
To remove the (TX) module move these files out of the RA2 Directory:

expandmd06.mix

If you extracted the files for map making you will need to also remove:

desertmd.ini
lunarmd.ini
snowmd.ini
temperatmd.ini
urbanmd.ini
urbannmd.ini

===4 Requirements===
You will need RA2 and RA2/YR disk and the latest patch (v1.001 at the time of writing). This was tested with legally copies of RA2 and RA2 /YR If you have an illegally 

copy and have a problem then you are "SHIT OUT OF LUCK" since we don't support hacks.
This was also tested with FA2/YR 1.2 the unofficial map editor with some problems. See know bug section. 

===5 Modifications ===
All tiles with "*" around the name are new additions to the tile list but are not the only changes. This just indicates what tiles you cannot use if you are making a map that 

has to be compatible with players that do not use the TX.

All theatres have tracks added as overlays and tiles. The lunar theatre uses the monorail from Tiberian Sun so as not to look out of place on the moon. Switches, track, 

cross tracks, road cross tracks and sloped tracks have been added to all but lunar terrain.

Note: there is a replacement tile for the overlay tracks for under Bridges. 
This fixes a known problem with path finding. Only one overlay can occupy a cell and both bridge and track are overlay. If you want a track under a high bridge, in this case 

the track would not work. The fix tiles are used in place of the overlay under the bridge as a workaround to the problem.

Tunnels have been implemented for all terrains and they work correctly if you set a [Tubes] section in the map file (FA2 1.02 can do this for you with our FAData.ini 

installed). This covers dirt, road, track and water tunnels. Lunar has Tiberian Sun tunnels. Frame mode tiles for the tunnels where added to make it easier to setup the tubes 

for the 
tunnels.
Note: water tunnels do not work with water bound ships but will work with infantry. It seems to be hard coded & no changes to this are planned.

Caves have been added for all terrains accept for lunar for both directions.

Natural Waterfalls have been fixed or added for all terrains accept for lunar and urban.
Urban waterfalls have been added to urban, new urban and snow.
Note: new urban falls animation has been added but requires a fix in the rules 
and arts ini file to work and so can only be implemented in mods. The TX site will eventually have tutorials for this and other new features found in the TX.
New dirt slopes have been added to urban and new urban for the dirt tiles.

Destroyable Cliffs have been added. These only work if they are hit by a weapon that has AmbientDamage=1 or greater.

Urban cliffs have been added to snow terrain. Both snow covered and paved. Urban road has also been added. 
The old Tiberian Sun Beached Oil Tanker has also been added.

Natural cliffs, highway and dirt roads for lunar.

Bridges for desert and a natural set for new urban. 

Miscellaneous tiles. Helipad, Water Breakers, Pavement Circles, Parking Borders, 
Highway Junctions, Highway dividers, Urban Features and a lot of miscellaneous 
fix tiles. Too many to list.

===6 Known Bugs===
Shows incorrectly in Final Alert but appears correctly in game (due to how game and FinalAlert read tilesets differently)

All train track overlays in Snow, Desert, NewUrban and Lunar will look like incorrect pallet Tiberian Sun tracks but will look correct in game. Some track overlay in 

Temperate and Urban looks off center in the editor but looks correct in game.

Desert terrain (Looks temperate or old TS in editor but in game looks like desert)
0019 sand bridges
0053 sand road tunnels
0054 sand tunnel sides
0056 Rubble cliffs
0073 tunnels
0080 sand wood bridges
0102 sand train ramps
0103 train tunnels
0119 Destroyable Cliffs

Snow terrain
0102 snow train ramps

You will see tunnels with over 60-80 tiles in them most of them look like marble sets. This is not a mistake they are reserve tiles for further version and modder use. The 

game only allows a 4-sets of tunnels and we have to think ahead since a set can have any number of tunnels tiles in it but you can't change the number of tiles in set once 

we make further additions or maps that were made previously will become corrupt using newer TX versions (this was a problem in an early version of the TX). We call this 'Tile Stacking' since we are stacking all the tiles that share the same limited feature into one set so they can all use it.


===7. Credits===
main developers 
-Blade		blade@mysanctuary.demon.co.uk
-DJBREIT	DJBREIT@ptd.net
-Mooman65 

-Additionally, I'd like to thank the play testers, graphical additions 
mapmakers, technical and other help.
Concolor1
CannisRabidus 
Sypher_5
tmapm
Dark_Desolator "paved circles"
Tetracide
WISHMASTER tm
Blaze_X
fraser101
Marshall

XTF for help with TMP editor.

DeeZire for technical assistance along the way. 

And many more people whom helped one way or another along the way.

Matze, for fixing some of the shortcomings of WW version and giving us the Final Alert 2 ver1.02.

===8 Disclaimer===
The author does not make any warranties regarding the files in this archive. 
Users assume responsibility for the results achieved for computer program use 
and should verify applicability and accuracy.

===9 Legal===
The Yuri's Revenge Terrain Expansion 2.02 is © 2003, © 2004 by Blade

You MAY NOT include the Yuri's Revenge Terrain Expansion or any of its components as part of any sort of commercial or promotional product without permission of Blade. 

blade@mysanctuary.demon.co.uk

You MAY NOT distribute the Yuri's Revenge Terrain Expansion or any of its components through any other means, except as part of a map or modification, and only when 

absolutely necessary to support mod-specific features which are not supported by the unaltered Yuri's Revenge Terrain Expansion. This .txt file (unaltered) must be included 

with any such map or mod, which requires bundling a modified version of the Yuri's Revenge Terrain Expansion. Please do use the Yuri's Revenge Terrain Expansion as a 

base for other mods or maps. If an alteration is needed for a map or mod, the files should be shipped with the map or mod as stated above.

If you make a tile set that you think can be added to the Terrain Expansion please post them at http://www.cannis.net/forum and will see if we can add them to the next 

version. We would like to maintain one Terrain Expansion so players, mappers and modders will have a minimum of compatibility problems and maximum technical support 

from the development team wherever possible.

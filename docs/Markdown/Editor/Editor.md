# Editor
The game style intended to be produced by the FGMK interface is usually called
JRPG and is inspired by the old RPGs from the SNES era.

The central idea of the games are a series of maps, that the player explores
in 2D fashion, in a Front Top Down view. These maps can contain characters for
the player interact with (called Charas in the FGMK Editor) and also with the
map itself (called Events), and these interactions lead things to happen
(called Actions). By using these elements the user can create interactive
stories.

Interesting stories usually require struggle and growth from the player and
the classic way of dealing with this in RPGs is through Battle and Leveling.
The editor denominates the playable characters as Heroes, and anything you
fight with are called Monsters. The player can also during it's journey
collect Items that can help the Heroes or even be important to advance the
story.

## Overview
When the interface launches, it will show your last opened project. If no
project is open, you can create a new one or open an existing project by using
the project entry in the menu. Using the project menu you can also access the
editors for other parts of the game, as the Charas (the characters), the
Charasets (their animation frames), Items (like swords, potions, ...), and
every other parts important to building your game.

The interface contains a map editor at it's core. Each map in a game project
is available at the Map Explorer dock, which you can use to create and delete
maps also, other than navigate. Using the Palette dock you can select the
current tile and draw using one of the available tools in the Tool dock.

The Events dock allow drawing Events, adding actions to them, and also drawing
in the collision layer. You can change the current layer by using the Layers
dock.

## The Map Editor
The central thing in the FGMK Games are the maps. This is where the user will
spend most of his time.

The **Tools** dock will allow the user to configure a tool for the left or right
mouse button, by clicking or right clicking in a tool. Holding the spacebar
while browsing the map will switch to the *pan* tool, and releasing the spacebar
will return to the previous selected tool.  The *line* and the *rectangle* tool
require two clicks at different tiles to work, one will connect both tiles
with a line, and the other will draw a rectangle between selected tiles. Charas
are placed with a special *charaplacer* tool.

The **Palette** dock will allow selecting the current tile, and the **Charas**
dock will allow selecting the current chara.

Double clicking a tile in the **Palette** will select the *pen* tool in the
**Tools** dock. Double clicking a chara in the **Charas** will select the
*charaplacer* tool.

You can select a layer by using the **Layers** dock, but clicking in the
Events selector or the Collision selector will change the current layer to
the Events layer or the Collision layer, respectively.

### Shortcuts

 - **ctrl + shift + n :** new project screen.

 - **ctrl + n :** new map.

 - **ctrl + s :** save map.

 - **f5 :** save map, run server, open default browser.

 - **Tab :** hides all docks, tap Tab again to show them.

 - **f11 :** switches to full screen.

 - **ctrl + mouse wheel or ctrl + +/- :** zomm in or zoom out

 - **press and hold space bar :** switches to pan tool while on hold.

### The server

When a project is loaded, you can open a browser at any time an point it to the
address shown in the status bar - assuming the server loaded correctly - to test
the current game. Each time you save the map, if you reload the browser that is
pointing to the server, it will update to the current state of the map.

The browser doesn't have to be in the same computer as FGMK, just in the same
local network, so assuming you have a WiFi network at home, you could load FGMK
in your computer and test the game in a smartphone or other computer.

## Palette Editor
When you draw a map, it uses selected tiles, grouped in a palette, this is how
you make your own palettes.

## Item Editor
Items are an important part of how the player interacts with the map. This is
where you make them.

## Charaset Editor
Charasets are a file that points to pieces of an image, and describe the
animations used by Charas (and the player chara).

## Charas Editor
Usually the NPCs you interact appear in the form of a Chara, in the Chara editor
you can set how a Chara moves or which actions would be executed.

## Jokenpo Editor
Here you can set the elements available in your world, and how they relate with
each other (paper wins over rock).

*still to be developed*

## Heroes, Monsters and Skills Editor
You can calibrate how each hero should level up, develop new skills, and specify
the monsters.

*still to be developed*

## Scripted Battle Editor
Meaningful battles should work like puzzles, the scripted battle editor is
design for just that.

*still to be developed*

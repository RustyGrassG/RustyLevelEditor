![image](https://github.com/user-attachments/assets/b5d17b82-2d22-4de7-bfbc-cd18c7fa85b7)
![image](https://github.com/user-attachments/assets/2c47603f-1819-44ba-96dd-c3c58c901710)


Hello!

This is a personal project of mine to help me get more familiar with python and pygame

about this program:

The window size is 1280x960
The display is 320x240(1/4th scale). There is no way to resize running application as of yet. Will be added in a future update

HOW TO GET IT TO WORK:
the file itself will work out of the box. If you want to be able to use it in game, all you have to do is put the 'tilemap.py' file into any of your projects, then instance a variable.
for example:

'import tilemap

world = tilemap

world.load('map directory')'

keybinds:

W,A,S,D - Camera Movement

1 - Disable/enable Grid

2 - Disable/enable World origin

G - Turn on/off grid snapping

O - Save project

DEL - Clear map

Mouse Scroll up/down - change tile group

Shift+scroll up/down - change tile variant

. - Layer up

, - Layer down


The best use case for this version of the editor is to use 16x16 pixel art assets.
This might be changed in future updates to where it can be modified to any size, but as of right now, this is the size i want

camera movement:

camera is at a set speed

Save/Load:

the file spaces are hard set in code right now, but there will be a UI update soon that fixes that issue

Clear map:

Deletes the entire tilemap. Will not save unless you press the save key

Tile group vs Tile variant:

Tile group refers to the folder that holds the tiles(decor, wood, stone, small decor, etc.)
The tile variant refers to each individual image within the tile group

Layers:

![image](https://github.com/user-attachments/assets/e2d9d62b-5ec1-4786-844e-afe0e7ffff71)


with the way it renders tiles, offgrid tiles will always be behind on grid tiles within the same layer. If the
offgrid tiles are 1 layer above the on grid tiles, then they will be placed in front of the on grid tiles.
You can delete only the tiles that were placed on the layer you are currently on,
I know this can get a bit frustrating when deleting a lot of things, so I will add some keybinds in the future to toggle this on/off

how to add more tile assets:
You can not add any assets through the editor, you need to go into the code and manually drag and drop your tile folder into the data/images/tiles section. It will read it from there

autotile:
There is no autotile function. there is skeleton code for it, but i plan on adding auto tile UI to the editor

Flood fill:
I do have plans to add flood fill to the editor in the near future, but i want to work on basic UI first before i get to that part


Planned updates:

near future- 

-Save UI

-Load UI

-Tile collision

-Alt. window for tiles

-Layer tile delete- Implemented 06/16

further out-

-Flood Fill

-Autotile

-TileMaps(will be released with autotile)

-Drag and drop files




even further out-

-tiles with code(being able to link code to a specific tile in engine, rather than through code)

-game testing in engine

If anyone actually decided to give this editor a go, please give me feedback in any way possible.

Here is my discord if you have any questions or feedback: hentur06,





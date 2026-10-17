# Introduction
Portal 2 maps that I, PlatypusBEEPBEEP, have made! This read me will teach you the installation, how to get into the maps, and about the maps.

# Installation
1. Find where Portal 2 is stored for you (e.g. C:\Program Files (x86)\Steam\steamapps\common\Portal 2\).
2. At the Portal 2 directory, navigate to ...\Portal 2\portal2\maps\.
3. Extract the maps into the map directory.
4. (Optional) Add the maps to extras:
    1. Back at the main Portal 2 directory, navigate to ...\Portal 2\portal2_dlc2\scripts\.
    2. Open extras.txt using any text editor.
    3. Add the code below to extras.txt for all the maps you want in extras.

```
"Extras"
{
    "<ExtrasID>"
    {
        "title"     "<SelectionBarName>"
        "subtitle"  "<PreviewName>"
        "pic"       "<PreviewPicture>"
        "map"       "<MapFileName>"
    }

    "Video1"	[!$GAMECONSOLE]
    {
    ...
}
```

- \<ExtrasID>: A unique ID for this extra
- \<SelectionBarName>: The name of the extra that appears on the side of the menu where you select the extra you want.
- \<PreviewName>: The name that appears in the preview.
- \<PreviewPicture>: The picture that appears for the extra:
    - vgui/extras/attract01
    - vgui/extras/attract02
    - vgui/extras/attract_bot_trust
    - vgui/extras/attract_panels
    - vgui/extras/attract_turrets
    - vgui/extras/attract_boots
    - vgui/extras/comic
    - vgui/extras/e1912
    - And any other portal 2 texture!
 - \<MapFileName>: The name of the map's file (e.g. 'playground' inherited from playground.bsp).

# Running the Maps

### In extras
If you added the maps to extras, you should be able to go to the extras menu and load the map from there.

### Manually
If you did not add the map to extras, you can load it by going into the developer console[^1] and typing in <ins>**map \<MapName>**</ins>[^2], then press Enter to load in.

# About the Maps

### ball_suffocation_machine
I got the idea of this map randomly, and it's pretty stupid and weird. When the map starts, you fall down into a chamber, when you press a button, each corresponding to a SPB (seconds per ball), the map goes dark and edgeless safety cubes start spawning from the hole you dropped down from. The speed the edgeless safety cubes spawn corresponds to your selected SPB.

### playground
This is a map where you can play with Portal 2 mechanics.

[^1]: You can do this by pressing the [\~\`] key. If that does not work, make sure developer console is enabled by going to [Options > Keyboard/Mouse > Allow Developer Console], once enabled, try pressing the [~`] key again.
[^2]: \<MapName>: The name of the map's file (e.g. 'playground' inherited from playground.bsp).

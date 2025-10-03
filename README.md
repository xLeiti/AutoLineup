# AutoLineup
A small experimental AutoLineup menu

This radialradio menu tracks your mouse position and auto selects and snaps to the lineup when you hover over it (similar to ```cl_inventory_radial_immediate_select 1``` in the weaponwheel).
Additionally the correct jumpthrow is performed afterwards by simply scrolling the mousewheel.

Note the mouse tracking could be used on any menu (buymenu for example). Furthermore it could be used to move your mouse to lineup positions without insta snapping.


# How to install and use:

1. Place ```platform_english.txt``` into ```game\csgo\resource```.
2. Place the ```AutoLineup```-folder into ```game\csgo\cfg```.
3. Adjust your keybindings and sensitivity in ```exec AutoLineup/main```
4. Launch the game and ```exec AutoLineup/main```
5. Press and hold ```p``` or the key you've configured. Then hover over the lineup you want to select.
6. The selection and snapping progress is completed when a sound is played. Wait till you have equipped  the smoke if you haven't already.
7. Scroll up with your mousewheel till you hear another sound.
8. You've finished.

   
X. Let go of ```p``` during any step if you want to abort.

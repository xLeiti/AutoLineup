# AutoLineup
A small experimental AutoLineup menu

This radialradio menu tracks your mouse position and auto selects and snaps to the lineup when you hover over it (similar to ```cl_inventory_radial_immediate_select 1``` in the weaponwheel).
Additionally the correct jumpthrow is performed afterwards by simply scrolling the mousewheel.

Note the mouse tracking could be used on any menu (buymenu for example). Furthermore it could be used to move your mouse to lineup positions without insta snapping.


# How to install:

1. Download the configuration:

<img width="965" height="422" alt="image" src="https://github.com/user-attachments/assets/f64bf38f-c32b-4132-a080-6e938a7d9a78" />

2. Unzip the file

3. Go to you steam library and open CS2's properties:

<img width="681" height="527" alt="image" src="https://github.com/user-attachments/assets/cf23f100-fc1d-4492-b6c9-02cd232887bd" />

4. Add following snipet to your launch options ```-testscript "../../csgo/cfg/autolineup/init.aveyo"```.

<img width="1204" height="557" alt="image" src="https://github.com/user-attachments/assets/38bafcf9-7039-46fa-b2c2-66ec959beb99" />

5. Go to "Installed Files" and click "Browse":

<img width="1626" height="417" alt="image" src="https://github.com/user-attachments/assets/4f2de625-a6e4-4a31-950d-f50ce36c03c8" />

6. And Explorer opens at ```steamapps\common\Counter-Strike Global Offensive```. Head to ```steamapps\common\Counter-Strike Global Offensive\game\csgo```

7. Paste the ```cfg``` and ```resource``` folder into your ```steamapps\common\Counter-Strike Global Offensive\game\csgo``` directory:

<img width="1610" height="610" alt="image" src="https://github.com/user-attachments/assets/0991d908-c60b-401d-a4d8-54c52c942c5c" />

8. Now head to ```steamapps\common\Counter-Strike Global Offensive\game\csgo\autolineup\main``` and open the ```main.cfg```

<img width="817" height="462" alt="image" src="https://github.com/user-attachments/assets/81522f82-d50f-44d3-a021-b9116fd87301" />

9. Adjust your keybinds and settings. Then save the file.

10. Launch the game & have fun!

# How to use:

1. Press and hold ```o``` or the key you've configured. Hover over the map you want to select. Release ```o``` when you're done.
2. Press and hold ```p``` or the key you've configured. Then hover over the lineup you want to select.
3. The selection and snapping progress is completed when a sound is played. Wait till you have equipped the smoke if you haven't already.
4. Scroll up with your mousewheel to performe the correct (jump-)throw.
5. If you do an execute, press your mousewheel-button to cycle between the different lineups.
6. You've finished.

   
X. Let go of ```p``` during any step if you want to abort.

# New in V2:
- Improved consistency and responsivness
- Implemented AveYo-Ticker
- Added Anubis [CT] T-Ramp Insta Smokes
- Added Inferno Insta Mid/Ramp Smokes via Fancythrow
- Cleaned up the project
- Now automatically using the FaceIt-Mode when on Faceit

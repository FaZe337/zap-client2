# xap-client  [LINUX]
**Updated to Game Version v3.0.55.37 (27.01.24)**

By **Gerosity**

All credits to original owners

Instructions & Menu Previews are down below

# Current Changelog:
    27.01.24 - The Advanced Update
    Main Things:
       - Removed Theme + Menu Tab, moved to Home.
       - Loading ASCII Art (If it looks wrong, make your terminal window larger)
           - Customisable (5 options)
       - Crashing (SHOULD) now be fixed!!!
       - Colors still do not save, I will make something for this in the future.
       - Testing performance/optimizations, ignore the warnings that show up when making the cheat.
    Home (NEW!):
       - Information about the cheat.
       - Team Gamemode (Moved from Misc to here, make sure to save config after changing)
       - Menu Customization, Menu Size, Themes, Styling + More! (Themes sometimes save?)
       - Error Logging (For debugging, no point having on unless your experiencing crashes/bugs)
    Aimbot:
       - Added Visibility Check.
       - Added Distance Smoothing (Not sure if it does anything, and I may replace the entire code anyway in the future)
       - Advanced Aim Settings (NEW!)
           - You can now configure each weapon to have different speed & smoothing levels!
    RCS:
       - Advanced RCS Settings (NEW!)
           - You can now configure each weapon to have different pitch & yaw levels (Weapon(s) not there? Check your RCS Weapon Selection)
    Glow (NEW!):
       - Seperated Glow from sense
       - Fixed Glow - https://www.unknowncheats.me/forum/apex-legends/605888-grinder-simple-linux-sense-aimbot-triggerbot.html / https://github.com/arturzxc/grinder
       - Added Color Modes (Shield Based or Custom Colors)
           - Shield Color Modes (Current Shield or Max Shield)
       - Added Invisible & Visible Color Pickers
       - Added Outline Thickness
       - Added Body Style ("None", "Pink", "Pink Visible Only", "Pulsing 1", "Pulsing Line Invisible Only", "Dark Pulsing Line", "Sharp Pulsing Visible", "Sharp Pulsing", "Pulsing Red Line", "Fast Pulsing Invisible Only", "Pulsing Up Visible Only", "Solid Pulsing", "Solid Pulsing 2", "Bright", "Bright 2", "Light", "Light Solid", "Red Pulsing Visible Only", "Wave", "Shaded Visible", "Wireframe", "Wireframe Visible Only", "Black", "Black Visible Only")
       - Added Outline Style ("None", "Bright", "Bright Invisible Only", "Dark", "Pink", "White", "Gold Flashing", "Gold", "Brown", "Wave", "Red Visible Only", "Red Bright", "Heartbeat Visible Only", "Green Invisible Only", "Visible Only", "Bright Orange", "Red 2")
       - Moved Item Glow to here
    Sense:
       - Moved Glow to Glow Tab
       - Added Show Legend (See what legend the other player is)
       - Added Draw Weapon (See what weapon the other player is currently holding)
           - Added Weapon Color Type (One Color or Multiple Colors, based on what type of gun they are holding (Also customisable))
       ! Show Near not working
       ! I recommend only choosing either Show Legend, Draw Distance or Draw Names as I havent scaled them individually and they will go over eachother
    Misc:
       - Removed Superglide due to breaking, may add back in the future

# Previews

![Terminal and Home Tab](https://i.imgur.com/xfb1zPx.png)
![Aimbot Tab](https://i.imgur.com/eZEnUd3.png)
![RCS Tab](https://i.imgur.com/RjPRmtz.png)
![Triggerbot Tab](https://i.imgur.com/O1HrvUd.png)
![Glow Tab](https://i.imgur.com/3Y1ofvE.png)
![ESP Tab](https://i.imgur.com/f0l7bIA.png)
![Misc Tab](https://i.imgur.com/zXgkdLY.png)
![Config Tab](https://i.imgur.com/tYDBzKY.png)

# Installation
**1.Install dependencies**

    sudo apt-get install -y libudev-dev
    sudo apt install cmake xorg-dev libglu1-mesa-dev libxrandr-dev libxinerama-dev libxcursor-dev libxi-dev
    sudo apt-get install build-essential
    sudo apt-get install libx11-dev
    sudo apt-get install libxtst-dev

**2.Build glfw**

    git clone https://github.com/glfw/glfw.git
    cd glfw
    mkdir build
    cd build
    cmake ..
    make
    sudo make install

**3. Clone repo**

    git clone https://github.com/Gerosity/zap-client.git
    cd zap-client

**4. Build and Run**

    mkdir build
    cd build
    cmake ..
    make
    sudo ./zapclient
    
**5. Press Insert to toggle the Menu (You can only interact with the Menu and the game when the menu is active).**


# Old Changelogs:
    21.01.24
    Aimbot
       - Fixed Weapon selection
    Sense
       - Added Health & Shield Bar (Rushed, will make better sometime)
    Misc
       - Added SkinChanger (Id's are capped at 11 until I find the max id for each weapon (Going over it can crash)
    Menu
       - Can now change the size of the menu
    Might have missed something
    Havent fully tested this + May still crash


    20.01.24 #2
    RCS - Recoil Control:
       - Fixed Recoil Control
       - Seperated Aimbot + Recoil control, now standalone (Credits: https://github.com/GitDev28/xap-client-CG)
       - Weapon Selection
       - Conditions (OnADS)
    Themes
       - Finally figured out how to add themes. There are currently 4, will be adding many as time goes on
       - Advanced Menu Settings
           - Change (almost) everything about the menu. DOES NOT save, will try and add this
    Other
       - Fixed Saving/Loading issues

    20.01.24 #1
    Aimbot:
       - Fixed shaking/Twitching?
    No Recoil Fixed (Offset issue)

    19.01.24
    Aimbot:
       - Added Delay (Not sure what its called, but it affects smoothing speed? So good for legit players ig
    Sense:
       - Added Status Text (Current Health & Armor)
           - Added Max Status Text (Max Health & Armor)
       - Moved Name and distance positions, distance may get in the way of box/skeleton, will fix eventually

    Crashing still occurs after going back to the lobby, not sure while and will do some testing about it tommorow.
    Not a big deal since you can just run the cheat again after crashing

    18.01.24
    Updated Offsets to v3.0.54.31

    17.01.24
    Aimbot:
       - Removed Keybinds, replaced with On ADS? or On Fire? Self explanitory
    Triggerbot:
       - Removed Keybinds, replaced with On ADS? Self explanitory
    ESP:
       - Filled Box ESP
       - Filled FOV Circle
    Other:
       - Fixed Config Saving/Loading issues
           - Colors do not save!

    16.01.24
    Updated Offsets - UC Forum
    Aimbot:
       - Keybind & Extra Keybind (If you want aimbot to be on left + right click) - https://github.com/GitDev28/xap-client-CG
       - Select Bone (Head, Neck, Upper Chest, Lower Chest, Stomach, Hip) - https://github.com/GitDev28/xap-client-CG
       - Select Weapons (e.g. only aim with R-99) - https://github.com/GitDev28/xap-client-CG
    Triggerbot:
       - Keybind (Hold to enabled)
       - Always On (Ignores keybind, always on)
       - Select Weapons (e.g. only with snipers) - https://github.com/GitDev28/xap-client-CG
    Sense/ESP:
       - Color Picker (Change Visible & Invisible colors for most features)
       - Visibile Only (Only draws ESP on those who are visible)
       - Show Near (?)
           - Not sure if it works anymore
       - Draw Team (Displays ESP on teammates)
           - Draw Team Names
       - Tracer Screen Position (Where tracers start e.g. Top, Middle (Crosshair), Bottom)
       - Tracer Bone Position (Where tracers goto/end e.g. Top (Head), Bottom)
       - Thickness Slider
           - For Box, Tracers, Skeleton, FOV Circle, Crosshair
       - Crosshair
           - Color, Size, Thickness
    Misc:
       - Team Gamemode (Enable for BR, Gun Run or Training. Disable for Control or TDM)
       - Superglide [!] - https://github.com/Savage3e/Nika or https://github.com/FlixEarth/nika-fixed
           - Works (most) of the time, freezes overlay until space is no longer held down (Needs Fix)
    Menu:
       - Layout (Simple or Compact)

# Help
**Features not working after changing them? (e.g. aim bind)**
Save config/Load config

**Aimbot not working?**

Check the speed/smoothness, keybind and if you have team gamemode on/off in the wrong mode

**ESP not working?**

Check team gamemode

# Original README.md

xap-client UC Link: https://www.unknowncheats.me/forum/apex-legends/606842-xap-client-aimbot-esp-triggerbot.html

So yeah, this thing was made by me, I was very bored so I took T_Tape's Menu and grinder's features and put them together to create this monstrosity. The code is still very messy so if you want to improve it, go ahead.
I'll will be very grateful if you do so.

**Disclaimer: This code is for educational purposes only .**

# Credits
arturzxc: for the features (ESP, Triggerbot, Aimbot) and X11Display's XTestFakeRelativeMotionEvent

Koelion (Braziliana): menu, aimbot calculations

unguhelvu : Seer-Styled ESP

unknowncheats: basic knowledge and offsets


# Previews

![enter image description here](https://i.imgur.com/7mVlPrr.png)

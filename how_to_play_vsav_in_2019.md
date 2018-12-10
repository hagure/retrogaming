# 	Playing Vampire Savior in 2018 (VSAV)

Welcome! If you're reading this I'm guessing you're interested in starting to play Vampire Savior. This document will help get you going with some kind of playable setup, with a focus on getting online play & training modes setup. 

The VSAV community has an active online scene on multiple platforms, and is a great way to have fun, learn & compete with others around North America & abroad!

One of the most common questions and issues that comes up for new players without access to a console is, "How do I set up a training mode?", which we'll go over here. In addition, we'll do a run down on every other console training mode & online play option available for Vampire Savior so you can pick the one that right for your needs.

## 	Community Standards

In the past few years, the North American Vampire Savior scene has started to standardize running their tournaments on actual CPS2 Arcade hardware. As such, the closest you can get to playing on this setup, the better. With that said, there are excellent options on both the console side—PS3 & XBOX 360's Dark Stalkers Ressurection, as well as great emulation solutions available for Desktop computers. Hell, there's even a decent way to run VSAV on a SNES mini!

Generally, the "closest to arcade perfect" is thought of along the lines of:

CPS2 >>> ShmupsMAME > Latest MAME RetroArch > DSR > FBA/FightCade > xxx ???

Don't be discouraged though, online warriors! VSAV's online scene is quite active & competitive! If you live outside of a hotbed of VSAV action, then online play is a great way to find opponents, level up & have fun! We'll start off with desktop pc emulation, then discuss console and other ways to play.

--- - --- - --- - --- - --- - --- - --- - ---

# 	Playing on PC (Emulation)

## 	General PC/Emulation Info

To start off with, you'll generally need 4 things to get started with emulating CPS2 hardware to run VSAV for online & training play.

1. An **Emulator** capable of stable CPS2 emulation
2. The **"vsav.zip"** rom
3. The **"qsound.zip"** rom
4. **Training Mode Scripts/Hacks** for your emulator


## MAME

### Works On:
	- PC
	- MacOS
    - Linux

### 	MAME Installation & Setup

#### 	PCs
Shmups MAME
MAME-RR

#### 	Macs

Here’s what you’ll need to download first:

- [SDL](http://www.libsdl.org/download-2.0.php) (2.0.8 as of this writing)
- [MAME](http://sdlmame.lngn.net) (0.198 as of this writing)[^1]

##### MAME MACOS Installation

1. Copy the SDL2.framework to /Library/Frameworks
2. Move the “mame0198-64bit” folder to wherever you want to put it.
3. Copy the path to the “mame64” executable. Note that if you change this location, you will also have to change it in your “.bash_profile” file Step X.
4. Next, you’ll have to add this to your .bash_profile ```alias mame=“PATH/TO/mame64"```
5. Now open up terminal, and type in ```mame``` after a loading screen, you should see something like this ![mame_startup]().
6. Now, you’ll have to acquire the appropriate ROM files. Note that as MAME is updated, romsets are also updated (usually). Make sure that the romset you have matches the version of mame you are running. Most romsets for MAME can be found here on [archive.org](https://archive.org/details/messmame?sort=-publicdate)[^2]. For MAME 0.198, we can use the 0.184 through 0.197 romsets.
7. First, create a few folders: "cheat", "roms". To get VSAV working, you’ll need to place these files into the "roms" folder: ??? new rom links
	- [qsound.zip](https://www.emuparadise.me/M.A.M.E._-_Multiple_Arcade_Machine_Emulator_ROMs/Q-Sound/164687-download)
	- [vsav.zip](https://www.emuparadise.me/M.A.M.E._-_Multiple_Arcade_Machine_Emulator_ROMs/Vampire_Savior:_The_Lord_of_Vampire_(Euro_970519)/17974)
	- [vsavj.zip](https://www.emuparadise.me/M.A.M.E._-_Multiple_Arcade_Machine_Emulator_ROMs/Vampire_Savior:_The_Lord_of_Vampire_(Japan_970519)/17972) (optional)

[^1]: I had trouble using v0181 & lua. v0198 worked fine though. I haven't tried v0203, current as of 2018-11-21.
[^2]: Note that full romsets for MAME run at around 60GB. If you’re only in it for a handful of games, it might be better to find them somewhere else. Just make sure you have the right version!

--- - --- - --- - --- - --- - --- - --- - ---

# 	MAME Cheats
![Image](http://wiki.mizuumi.net/images/f/f7/Vsav-mame-rr-cheats.png)

While the LUAs have most of these features, MAME Has a few things that the training Mode LUA is missing, like infinite Dark-Force time. It is especially useful when using the Hitbox Viewer LUA as you can only run one LUA at a time. You'll still have access to Infinite Time, Health, and Meter.

Cheat  					 | Effect |
 ----------------------- | ------ |
Infinite Time 			 | Timer will not decrease from 99.
Finish this Round Now!	 | Makes the match end immediately in a timeover.
Select background		 | Lets you select any background. Set before entering the match, otherwise the game will crash.
No Background Music		 | Turns off background music.
Hide Background			 | Hides the background, life bars, meter and timer.
Select Region			 | Changes region.
Select Title			 | Switches the title screen to "Darkstalkers: Jedah's Damnation" (I couldn't get this to work properly)
Sound Test Timer Stop	 | ???
Sound Test				 | Listen to different sound effects and music tracks. Best done from the Service Menu (Press F2).
**The cheats below have separate sections for Player 1 and Player 2.** ||
Soul Keeper 'ON'		 | Activates Shadow.
Soul Keeper 'OFF'		 | Deactivates Shadow. Must set "Soul Keeper 'ON'" back to "Off" first.
Maximum POW				 | Meter will not decrease below 99.
Infinite Energy			 | Life is set to full the character will not take any damage.
Drain All Energy Now!	 | Sets Life to zero, the next hit will kill. Infinite Energy must be set to "Off"
Infinite Dark Force Time | Dark-Force timer will not decrease.
Select Character		 | Selects any character, include test/hidden characters and Oboro Bishamon. Use on the character select screen to avoid glitches.

**Installation & Setup**
 1. Follow all the steps to set up MAME listed above.
 2. Start the game in a versus match, selecting both Player 1 and 2.
 3. Once in the game, press "Tab" and select "Cheat". From there, the typical cheats to enable are:
 4. *Infinite Time
 5. *Maximum Pow P1 & P2
 6. *Infinite Energy P1 & P2
 7. *Infinite Dark Force Time (Optional, depending on what you are testing.)
 8. At this point you are free to train!

## 	Shmups MAME

### Works On:
- PC

Shmups MAME is generally considered to be the closest match to Arcade perfect as far as emulation.

## 	MAME-RR (v0139)

### Works On:
- PC

MAME-RR is a powerful version of MAME that has extra debugging tools and allows for scripts (LUAs) to be ran. Though, we'll be using its abilities to create a Vampire Savior training mode on the PC.

It isn't perfect though, as you can only run one LUA at a time, but utilizing the cheats in tandem lets you still accomplish many things.

Below is a compiled .zip with Vampire Savior and MAME pre-configured with the correct settings and all the scripts in the right location. Just download it and you're good to go!

**[MAME-RR Vampire Savior Training Pack](http://www.mediafire.com/download/sbaf4wb6apby3qf/MAME-RR_v0139_vsav_train.zip)**
- MAME-RR v0139
- Vampire Savior Training LUA by Jed Possum
- Vampire Savior MAME Cheat File
- Hitbox Viewer LUA by Dammit
- Framedata Viewer LUA by Dammit
- Properly configured MAME and Vampire Savior settings

**Installation & Setup**
1. Download and unzip the "MAME-RR Vampire Savior Training Pack"
2. Get a copy of "vsav.zip" and place it in the "roms" folder located in the "MAME-RR v0139" folder.
3. If you have an arcade stick, pad, hitbox or another controller device plug it in now, as it will not register if you plug it in after you launch MAME.
4. Launch "mame.exe" and load "Vampire Savior: The Lord of Vampire (Euro 970519)"
5. When the game starts, press the "Tab" button and navigate to "Input (this Game)" and bind your controls.
6. MAME itself is now all set! Look under the sections below (Vampire Savior Training Mode, Hitbox Viewer and so on...) to see how to load the scripts and cheats.


## 	RetroArch

### Works On:
	- PC
    - MacOS
    - Linux
    - SNESmini

## 	Final Burn Alpha (FBA)

### Works On:
	- PC

![Image](http://wiki.mizuumi.net/images/a/a9/Vsav_fba_cheats.png)
Generally a quick and easy training mode to set up, but doesn't provide anything beyond standard emulator cheats like Infinite Time, Health and Meter. This will work with either the version of FBA that came with GGPO, or the most up to date version of FBA which is linked below. The older version of FBA has you place the cheat file in a different location than the newest version, so be sure to read the "Installation & Setup" process listed at the bottom of this section.

**[Final Burn Alpha Vampire Savior Cheat File Download](http://www.mediafire.com/download/fa03f4q2n3g8mg2/vsav.ini](Download the FBA Vampire Savior Cheat File)**

This cheat file has been pre-configured, so as soon as you place it in the correct folder and load up the game the following cheats will be turned on: Infinite Time, Infinite Health P1 & P2, Infinite Meter P1 & P2 and Infinite Dark-Force Timer P1 & P2. 
If you want to turn them off, load up the game and select "Misc > Enable Cheats" and turn off the ones you don't need. You can also directly edit this .ini cheat file yourself as needed.

### Installation & Setup

#### Newest Version of FBA''
1. [Download the latest release of Final Burn Alpha](http://www.barryharris.me.uk/fba_downloads.php).
	- Windows XP: Download **Windows XP Binary**
	- Windows Vista/7/8: Download **UniCode Binary**
2. Create a folder named "Final Burn Alpha" and unzip Final Burn Alpha to there.
3. Launch "fba.exe" to generate the necessary folders and files.
4. Get a copy of "vsav.zip" game rom and place it in your "roms" folder. If it is not displaying when you go to "Load Game", make sure you check the "Show available" box. If you are still having trouble, click on "ROMs Dirs...", navigate to your "ROMs" folder, and after that click on "Scan ROMs".
5. You have two options for this next step, it is important that you do one of them:
	1. [Download "vsav.fs"](http://www.mediafire.com/download/ddkhmac81iz2v63/vsav.fs) and put it in your "GGPO-030\config\games" folder. If there is already a "vsav.fs" file in that folder, delete it and replace it with this one.
	2. Change the settings for Vampire Savior yourself (Set it to TURBO3 and FREE PLAY) by entering the CPS-2 menu (Press F2).
6. Download the "FBA Vampire Savior Cheat File" from up above, and place it in your "Final Burn Alpha\support\cheats" folder.
7. You are now free to train!

#### 	GGPO Final Burn Alpha
1. Download GGPO from [http://ggpo.net/ HERE].
2. Create a folder named "GGPO-030".
3. Unzip the contents of "ggpo-build-030.zip" into "GGPO-030"
4. Launch "ggpofba.exe" to create the necessary folders and files inside of your "GGPO-030" folder.
5. Get a copy of "vsav.zip" game rom and place it in your "ROMs" folder. FBA may ask for you to set a path to a ROMs folder but just hit "Cancel". From the "Select Game" window, check the "Show Available Only" box, and click on "Scan ROMs".
6. You have two options for this next step, it is important that you do one of them:
	1. [Download "vsav.fs"](http://www.mediafire.com/download/ddkhmac81iz2v63/vsav.fs) and put it in your "GGPO-030\config\games" folder. If there is already a "vsav.fs" file in that folder, delete it and replace it with this one.
	2. Change the settings for Vampire Savior yourself (Set it to TURBO3 and FREE PLAY) by entering the CPS-2 menu (Press F2).
7. Download the "FBA Vampire Savior Cheat File" from up above, and place it in your "GGPO-030\cheats" folder.
8. You are now free to train!
	- If the game is displaying in wide screen (CPS-2 games should be displayed in 4:3), go to "Video > Monitor Properties" and select either "16:9" or "16:10", whichever aspect ratio your monitor has.


# 	Vampire Savior Training Mode LUA Script

![Image](http://wiki.mizuumi.net/images/7/70/Vsav-mame-rr-trainingscript.png)

Created by Jed Possum, this is an extremely handy script with a lot of functions. This is the best way to practice Vampire Savior on emulators at the moment! It's still in development, with integration of a Hitbox viewer along with some other features in the next version. It may be a while before the next release, so get what use you can from it right now!

Its very feature rich at the moment, with things you would not find in a console training mode, so be sure to read the below carefully!


Functions | Notes
--------- | ----------
Automatic Life Recovery	 | Once a character is damaged to a certain point, life will automatically return to full. It is still possible to kill a character though, if you do a single powerful attack when they already have low health.
Infinite Meter	 | Meter will not decrease below 99.
Infinite Time	 | Timer will not decrease from 99.

HUD | Notes
--------- | ----------
Red/White Health Values	 | Each full lifebar is 144 points, however this does not mean every character has the same health. There are defense modifiers at work in the background, making hits do more or less damage to each character.
Meter Values	 | Each full bar of meter is 144 points.
Numeric Dark-Force Timer	 | Activate Dark-Force and you'll have a numeric overlay telling you how much time is remaining.
Input Display	 | Inputs are on the left side of the screen, and scroll from the top as new inputs are made. After a few seconds with no inputs it will clear next time you take an action.
Special Move Input Display	 | An awesome function. As you make direction or button inputs, each number will light up (based on Numeric Notation). Since it is showing your inputs as you make them, you can immediately see at what point you are dropping the special move input. It also shows you exactly how long each input is held in the buffer, so if the directional inputs become unlit before you press the button, your special move will not come out. For charge moves, the directional input is Yellow until charged, at which point it turns Green.
Character Placement	 | Listed right above the Meter Bar as "Place". The numbers provided are a bit overwhelming, but it lists the ''exact'' position of both characters on the screen.
Push Block Timer/Gauge	 | This will appear above the Meter Bar when a character blocks an attack. It displays "Mash: x" and "Timer: x". "Mash" is how many successful Push Block inputs are made while in blockstun, and "Timer" is how many frames are remaining to Push Block.
Bubble Timer	 | This will appear above the Meter Bar when a character is in Aulbath's Bubble. This displays how much longer the character will remain in the bubble. It is possible to ''mash'' to reduce this time.
Curse Timer	 | This will appear above the Meter Bar when a character is Cursed by Anakaris. This displays how much longer the character will remain cursed.
Remaining Taunts	 | Limited to 16 per match.
Projectile O.K.!	 | The green box below Player 1's lifebar is supposed to represent if they can throw out a projectile or not (say if one is already on the screen), but is currently not functioning.


**Setup**

1. Follow all the steps to set up MAME listed above.
2. Start the game in a versus match, selecting both Player 1 and 2.
3. Once in the game, press "Ctrl + L" to open up the Lua Script loader from where you will:
4. *Select "Browse", and if not already in the "MAME-RR v0139" folder navigate to it and open "vsavscriptv2.lua".
5. *Simply click on "Run" to start the script.
6. You're now free to train!

**Optional**
- Combinable with MAME cheats, including "Infinite Dark-Force Time". Use what suits your needs.
- It is possible to change the value at which life automatically recovers at.
- Before starting I recommend creating a "save state", since as I said previously it is possible to kill your opponent still under certain conditions. To create a save state, hold "Shift" and press a key between "F3 to F11" (avoid F2 since it is the "Service Menu" button). Press whichever F-key, without holding Shift, to load the save state.

# 	Hitbox Viewer LUA Script

http://wiki.mizuumi.net/w/Vampire_Savior/Hitbox

# 	Frame Data LUA Script

# 	Tips
One of most important training mode features missing when doing PC Emulation is the ability to make the opponent roll. If you're using an 8-button stick or controller, you can set one of the extra two buttons to [P2: Left + LP] and the second free button to [P2: Right + LP], then just mash one of them on knockdown to force the roll.

To force the opponent to jump, I usually bind the Player 2 directionals to the arrow keys, and then jam a penny in hold down the jump button. That's not going to work on all keyboards though.


## 	FightCade

### FightCade 1
- Most popular form of online play
 
### FightCade 2
- Development on Hold
- Currently not used

## Emulation on non-PC Hardware
- SNES mini
- RasPi
- FPGA/Mister
- Vita

--- - --- - --- 

# 	Playing on Consoles

##	PS3/XBOX360/PS4? Darkstalkers Resurrection (DSR)

![Image](http://wiki.mizuumi.net/images/3/35/Vsav_res_training_01.png)
The most accessible console training mode today, and one of the only good ones (along with Vampire, Darkstalkers Collection). 

It's a feature heavy training mode with a lot of good sides. For one, changing training settings is a bit more snappy than the other versions, as you don't have to restart the round every time you change a setting. There is a decent Record/Replay function. It allows for in-match save states, so you can reload any specific point you want. There is an ''extremely'' detailed command list. You can also hold "Select" to control both Player 1 and Player 2 at the same time.

As far as downsides go, is the Attack Data display is bugged, and does not properly show damage. If you need to check damage values, use Vampire Darkstalkers Collection. Also, depending on who you ask, the release has a ''slight'' bit of input lag, but most players would not notice it unless they are playing "link combo" heavy characters. Playing on a CRT may mitigate that problem though. It's also missing the valuable "random roll direction" on wakeup that was featured in Vampire Darkstalkers Collection.

## How the ATTACK DATA Display is Bugged
- ??? Anyone have the explanation?


## DSR on PS4 Streaming Service
- ??? Has anyone tried this?

## DSR Training Mode Functions

### How the SAVE STATE function works:
1. Press "Start" + "Select" to create a new "Save State".
2. Press "Start" + "Select" to load the "Save State".
3. Hold down "Start" + "Select" for a few seconds to erase the "Save State" you just made.
4. Press "Start" + "Select" to create a new "Save State".

Consider using up all of your "taunts" (There are 16 available for both characters per match) before using the Save State function as they tend to get in the way, and each time you load up a state you'll end up seeing the later half of a taunt. Also keep in mind that the Save State feels like it takes a couple frames to be created (at least to me) after pressing Start and Select.

### How the RECORD/REPLAY function works:
1. Press "Start" and select "RECORDING MODE".
2. You will gain control of the "training dummy", and can perform as many actions as you'd like for as long as you'd like. Everything done during this time period is essentially a savestate replay.
3. When finished, press "Start" and select "REPLAY". You have control of your original character and the dummy will replay all previous inputs. When it finishes everything recorded, you must press "Start" and once again select "REPLAY" for the dummy. 

It's a little troublesome to go back and select replay over and over, but the menus are quick. Keep in mind that since the replay is a savestate, it also records your original position, so you don't need to re-orient the dummy if they end up out of place... But this also comes with the problem that if you cross the opponent up, their directional inputs will be going the wrong direction. It's a bit different from most Record/Replay functions, and the lack of an auto-replay is annoying, but it does it does its job.

### DUMMY SETTINGS
![Image](http://wiki.mizuumi.net/images/2/27/Vsav_res_training_02.png)
- **DUMMY ACTION**: STANDING • CROUCHING • JUMPING • COM • HUMAN
- **DUMMY GUARD**: NONE • ALL • ALL (STANDING) • ALL (CROUCHING) • AUTO • AUTO (STANDING) • AUTO (CROUCHING)
- **DUMMY GRAB ESCAPE**: NONE • ALL • RANDOM
- **DUMMY TECH ROLL**: NONE • TOWARDS • AWAY
- **DUMMY ADV. GUARD**: NONE • ALL • RANDOM

### TRAINING OPTIONS
![Image](http://wiki.mizuumi.net/images/2/29/Vsav_res_training_03.png)
- **SP GAUGE**: INFINITE • NORMAL
- **DARKSTALKERS 3 TURBO SETTING**: NORMAL • TURBO 1 • TURBO 2 • TURBO 3 • TURBO 4 • TURBO 5 • TURBO 6
- **ATTACK DATA**: ON • OFF
- **KEY INPUT**: A(''Scrolling'') • B(''Light Up'') • Off
- **CPU DIFFICULTY**: 1 • 2 • 3 • 4 • 5 • 6 • 7 • 8 • 9
- **DARK FORCE**: NORMAL • INFINITE
- **GLOOMY PUPPET SHOW**: RANDOM • 1 • 2 • 3 • 4 • 5 • 6

---

## 	DC/PSP: Vampire Chronicle/Darkstalkers Chronicle: Chaos Tower
![Image](http://wiki.mizuumi.net/w/File:Vsav_dreamcast_training_01.png)
WARNING: This game is based off of Vampire Savior 2, and even if you select "SAVIOR" mode for characters many things such as dash links, hops, air dashes will not function the same as they do in Vampire Savior! In addition, damage values are almost completely different! This is not at all arcade perfect!

So, while taking the many gameplay inconsistencies into account, the main use of Vampire Chronicle's training mode is its Record/Playback function. The problem with this though, oddly enough, is the directional inputs do not account for crossing the opponent up, so everything will be coming out backwards. Basically, if you have Lei-Lei throwing Items at you and then cross her up she'll suddenly be doing Gongs. It's a problem, but it is something easily coped with. Vampire Chronicle pretty useless outside of the Record/Playback since its even missing common training mode features like: Roll Direction, Push Block, Throw Escape, Infinite Dark-Force and Input Display.

The good thing about Vampire Chronicle emulates perfectly on nullDC, so for those training on a PC that want a record function it's great; as imperfect as it is.

**TRAINING MENU**
![Image](http://wiki.mizuumi.net/w/File:Vsav_dreamcast_training_02.png)
- **ACTION**: STAND • CROUCH • JUMP • COM • RECORD • PLAY • HUMAN
- **S.S.GAUGE**: NORMAL • INFINITY
- **GUARD**: NORMAL • OFF • ALL
- **SPEED**: NORMAL • TURBO1 • TURBO2 • TURBO3
- **ATTACK DATA**: ON • OFF
- **COCKPIT**(''Heath, Meter, Timer Display''): ON • OFF

**How the Record/Playback function works:**
. Go to training menu, switch "ACTION" to "RECORD" and then select "OK" at the bottom of the menu.
. After a brief alert that recording will start, you will have up to 10 seconds to record inputs.
. When you're done recording the dummy action, press "Start" and go back to the training menu, this time switching "ACTION" to "PLAY" and then once again selecting "OK".
. The match will restart and the dummy will now continously preform the recorded inputs.

**Differences between the Dreamcast and PSP version''':**
- Dreamcast version emulates much better.
- PSP version forces you to "RECORD" for the full 10 seconds. You can't just record for 1 second and then play that back, you must record for a full 10 seconds.

---

## 	PS2: Vampire: Darkstalkers Collection

![Image](http://wiki.mizuumi.net/w/File:Vsav_ps2_training_01.png)
A reliable and great version of the game for training mode. It is extremely feature heavy, having pretty much everything you could want besides a Record/Playback function.

In terms of comparison to Darkstalkers Resurrection training mode, this is what Collection has to offer over it:
- Attack Data display is not bugged like it is in Resurrection, and correctly displays damage.
- "RANDOM ROLL" on knockdown for the dummy is 'extremely' useful for testing high level okizeme and training yourself to properly react to a roll. This is the only version of the game with that function.
- Input lag free. Though this only applies to training mode. In versus matches there is extreme input lag due to an emulation problem(subsequently fixed in Street Fighter Alpha Anthology). Training mode is lag free though.

The are several problems though. The game emulates extremely poorly, so you'll need a PS2 and a way of playing Japanese games. Also, the match must restart every time you change settings. A nice tip though is if you hold "Select" you can control both characters at the same time.

**''Training Settings''**
**COMMAND LIST**
![Image](http://wiki.mizuumi.net/w/File:Vsav_ps2_training_02.png)

**TRAINING MENU**
![Image](http://wiki.mizuumi.net/w/File:Vsav_ps2_training_03.png)
- **SS GAUGE**: INFINITY • NORMAL
- **DARKFORCE**: NORMAL • INFINITY
- **TURBO SPEED**: NORMAL • TURBO1 • TURBO2 • TURBO3 • TURBO4 • TURBO5 • TURBO6
- **ATTACK DATA**: ON • OFF
- **KEY INPUT**(''Input Display''): TYPE A • TYPE B • OFF

**DUMMY SETTINGS**
![Image](http://wiki.mizuumi.net/w/File:Vsav_ps2_training_04.png)
- **ACTION**: STAND • CROUCH • JUMP • COM • HUMAN
- **GUARD**: NONE • ALL • ALL (STAND) • ALL (CROUCH) • AUTO • AUTO (STAND) • AUTO (CROUCH)
- **THROW ESCAPE**: NONE • ALL • RANDOM
- **STANDING**: NONE • FRONT • BACK • RANDOM
- **A. D. GUARD**: NONE • ALL • RANDOM
- **PUPPET SHOW**(''Only shows if Lilith is Player 1''): RANDOM • No. 1 • No. 2 • No. 3 • No. 4 • No. 5 • No. 6

## 	PS1: Darkstalkers 3 / Vampire Savior: EX Edition

![Image](http://wiki.mizuumi.net/w/File:Vsav_ps1_train_01.png)
**WARNING**: This is as far possible as arcade perfect you can get, besides maybe Vampire Chronicle. 

A port with a couple interesting features, but ultimately useless as a training mode.

It has a special "black background" for training mode that is not any other version of Savior. I actually find it to be awful since it makes it incredibly hard to see your characters movement. You can turn on a Grid Overlay ("HEX") in Training Mode as well, though it seems a bit useless if you have access to hitboxes. "SIGNAL" has three options, and most interestingly of them you can set it so on block, your character flashes for the moment that ''Push Block'' and ''Guard Cancel'' are available to them, which perhaps is the most useful feature this games training mode.

Just like Vampire Chronicle, this game is missing a lot of useful options from its training mode. But, unlike that game, this version has no redeeming training value.

**TRAINING MENU > NORMAL MODE'''(''Press Start, and then Select to access the Training Menu'')**
![Image](http://wiki.mizuumi.net/w/File:Vsav_ps1_train_02.png]] [[File:Vsav_ps1_train_03.png)
- **ACTION**: STAND • CROUCH • JUMP • CPU • HUMAN
- **SS GAUGE**: INFINITY • NORMAL
- **SPEED**(''Make sure you set it to Turbo3 in the "OPTION MODE" first''): NORMAL • TURBO
- **CPU GUARD**: OFF • ON(''Auto Guard'')
- **SIGNAL**: OFF • AD GUARD • GUARD CANCEL • CHAIN COMBO
- **ATTACK DATA**: ON • OFF
- **HEX**(''Grid Overlay across the entire screen''): OFF • HEX8 • HEX16 • HEX32
- **COCKPIT**: ON • OFF
- **INPUT CHECK**: ON • OFF
- **PUPPET SHOW**: OFF • NO.1 • NO.2 • NO.3 • NO.4 • NO.5 • NO.6

**TRAINING MENU > RECORDING MODE**
:Despite the name, this is not a dummy Record/Playback function. You simply 'Record' yourself beating up the dummy, and then you can 'Replay' it. The dummy cannot even be set to human control in this mode. Its a very strange and seemingly useless feature.

--- - --- - --- 

# 	Playing on Arcade

- What you need:
	- CPS2 A Board
	- CPS2 B-Board VSAV
    - Supergun
    - JAMMA Harness
    - [CPS2 Kick Harness](https://wiki.arcadeotaku.com/w/HRS_DF1B)
    - UD-USB Adapters
    	- Terminal Block
        - DB15

## 	[CPS2](http://cps2shock.emu-france.info/techinfo.html)

### 	Regions

- **Green**: Japan
- **Blue**: US
- Orange:
- Yellow:
- Black:

Green & Blue A/B boards are compatible with each other. 

### Tournament Standard Configuration
- English screenshots
- Japanese screenshots

### No TRH Glitch Fix
- Tape Fix

### Broken Plastic
- Undamned [reccomends](https://twitter.com/therealundamned/status/1065133321590472704) [this](https://www.amazon.com/GLUE-768-Super-Jet-JETR0768/dp/B0006O1IH4)

### Broken Volume Buttons

### Battery
- Phoenix
- UniKey
- Battery Replacement
	- Battery Holder

### DarkSoft

- Rom Pack
- Color Hack Info
- Donor Boards: MvC1
- 3D Printed Thing

## Superguns

###	[HAS](https://www.arcade-projects.com/forums/index.php?thread/332-home-arcade-system-new-supergun-sets/)

- How to Get: 
- Members who can help:
	- hagure
- Power Supply
	- Mean Well MWP-606 or SUZO 42PP0606,
###	Windy Gaming
###	[Sentinel](https://www.arcade-projects.com/forums/index.php?thread/5942-sentinel-supergun-prototype/)
###	Jasen
###	Retroelectronik
### [Parsec](https://www.tindie.com/products/low_budget/parsec-supergun-v10/)
### UD-CPS2
- [Upcoming DIY Kit](https://www.arcade-projects.com/forums/index.php?thread/3272-diy-ud-cps2-kit/)

---

## Arcade Info
- [Shmups Forum](https://shmups.system11.org/index.php)
- [Arcade Projects Forum](https://www.arcade-projects.com)
	- Home of HAS, Sentinel superguns, Undamned's Projects
- [Mizuumi Training Section](http://wiki.mizuumi.net/w/Vampire_Savior/Training)

---

# 	Streaming

## 	PS3
- HDCP

## 	Arcade Streaming

- OSSC
- gscartsw
- pvm

# Arcade Parts
- Paradise Arcade
- Focus Attack
- Arcade Shock
- RGB Stuff
# The Nico Experience
by Nicoroshi 
V 1.1.4

Overview:

This is the mod list I personally play. I would describe it as a power fantasy list with 
emphasis on visuals, combat, new creatures, new places, and fast paced game play.
I could write a book on this, and still have more to say so I will just put it to you like this.
I am very OCD, and want the best of everything in my Skyrim. 
This mod list is the result of playing and modding this game since the day of it's release
So if you're looking for a visually stunning Skyrim experience that will push the graphical 
limits of what Skyrim can be I invite you to take a trip through
The Nico Experience 

  Recommended Hardware
  
Absolute minimum if using every provided option for optimization is:

Video card with 12GB of VRAM

Processor of 3Gz or better and minumum 4 cores

16GB system ram

Sata SSD with minimum 500 GB of free space and 40GB virtual memory 

                     NOTE: The minimum specs will certainly struggle to maintain 30-50fps

Ideal specs:

Video Card with 24GB of VRAM

Processor of 4.5GHz or better and 16+ cores

32 GB of system Ram

M.2 nVMe drive with minimum 500 GB of free space and 40GB virtual memory

If you fall somewhere between these two you can play it. Optimization is KEY for any specs so read this to the end for recommended configuration.

Installation:
Pre-install:
1. Install a fresh copy of Skyrim AE from Steam version 1.6.1170
2. Install the Creation Kit from Steam
3. Launch the game once from Steam and at the prompt download all CC Content from the full version of AE.
4. Start new game and after hearing  "So you're finally awake" open console (~) and type QQQ then press enter to quit out.

Important Note:
**You will need a Lovers Lab account for some manual downloads in the Wabbajack**

Install (Main)

Run Wabbajack

Navigate to The Nico Experience wabbajack file and choose your game install location (min 500GB) and file download location
**There WILL BE about 22 Files that you WILL NEED to click the green DOWNLOAD button on Lover's Lab to download through Wabbajack after signing into Lover's Lab account**
These armors can be accessed in game via the additem menu
After those are downloaded the rest of the install should be automated.

Post Installation:
VERY IMPORTANT:
1. Make sure you run the mod organizer.exe as admin and have excluded it from your anti-virus. Also disable Steam Overlay completely
2. Navigate to (Drive letter):\Where\you\installed\the Wabbajack\ModOrganizer.ini
3. Check this line near the top
   
gamePath=@ByteArray(C:\\Wabbajack<\\The Nico Experience\\Mod Organizer 2\\Stock Game
 
This example is where I installed it

Yours might look different but the idea is to point it to where your Stock Game folder is located in the new install

It may already be pointed in the correct location but good to check.

4. in MO2 left pane go to #93 LOD Generation_Output Tab

Choose either:

VRAMr_Output for 16GB cards (On by default)
or 
VRAMr_Output for 12GB cards

Depending on your graphics card VRAM amount.

CHOOSE ONLY ONE TO ACTIVATE

Default game resolution is 1920x1080 but Profile for 21:9 resolution is included. 

Base resolution for 21:9 profile is 3440x1440

Don't forget to change your resoltion in Bethini to match your screen resolution.

Included tools:
Bethini Pie
SSEedit and QuickAutoClean
LOOT
Cathedral Assets Optimizer
Nemesis
Bodyslide and Outfit Studio
NifSkope


All the tools you choose to install need to link in the top right executable bar in MO2 so these programs can start from within the virtual file structure of MO2.
This Wabbajack uses a file structure that contains a folder called 'Stock Folder' in the MO2 directory.
This is where the game will run from. It will NOT run from Skyrim Special Editions Folder so ALL links to executables NEED to point to the Stock Folder in Arguements to work correctly.
 

Find this in MO2 executable bar under <EDIT....> then on the binary click the 3 dots and navigate to your file path for that exe to change this file paths to lead to your specific file install paths OR IT WILL NOT WORK. They are currently set for my file paths. Use those as a reference on how to set them up.
Good tutorial on how to set these up is here >>>>
https://github.com/LivelyDismay/Learn-To-Mod/blob/main/lessons/Setting%20up%20Stock%20Game%20for%20Skyrim%20SE.md#tool-setup

Mods that are NOT hosted on Nexus I personally use. 
They are NOT hard requirements but highly recommended

Voice Files for DBVO on Discord by FearTCB (Requires log in to Discord)
Ciri
https://discord.com/channels/1083738069225709588/1110554398364536885

There are other vioce files on FearTCB's discord you may like as well so look around while there and add the ones you want.
Voice files I put in the Dialog tab of MO2

Kirax BDOR Complete Collection

https://kiraxskyrim.com/public-work/bdor-complete-collection

Be sure and grab this to go with it

https://www.nexusmods.com/skyrimspecialedition/mods/103046?tab=files

There are some other armors available on this site as well worthy of looking at. 

Decide what you would like.


Some notes on basic system set up
This mod list IS graphically taxing on the hardware but systems can run it if they have the room to breathe.
I'm not going to hold your hand on this, and assume you know Google-fu for anything you don't understand here.

1. Turn off any start up programs or background programs that do not need to be on while running the game. 
https://www.blackviper.com/ is a wonderful resource on trimming the fat out of the Windows System Services.

3. strip that graphics driver down of any AA, AO, AF settings (Turn off) as those effects will be handled by the game engine or the ENB. 
DO NOT DOUBLE UP ON EFFECTS!  It will kill your framerate and will not look any better than only one doing that specific effect.
Run Gsync if avialable and for Heavens sake DO NOT use the in game vsync. Use driver vsync instead.
Run latency at ultra and any settings you can at high performance in the driver.

5. Run resizable bar if your hardware is capable of it. It widens the bandwidth for better file transfer speeds (i.e. smoother gameplay)
Panjano has a good video on how to set this up here >>>
 https://www.youtube.com/watch?v=5DqcgHtkm9I

7. Run either Skyrim Priority (a mod on the Nexus) or Process Lasso (there is a free version) to set priority for Skyrim to HIGH as well as set affinity for the processor core count you have.

These are not included as they need to be tuned to fit the specific hardware. See instructiuons on the mod page
https://www.nexusmods.com/skyrimspecialedition/mods/50129

9. Go to system settings and set virtual memory on the drive the mod organizer is on at 40GB min and 40GB Max. Save and restart.
This will be your swap file and supplement the VRAM if needed.

Some Paywalled mods worthy of mention (Not required but you'll have a much better experience with them than without IMHO):

Puredark's Upscaler for ENB ($5)
https://www.patreon.com/posts/skyrimupscaler-85674764
Using this gained me a solid 5-10 FPS as well as superior Anti Aliasing

Some free options would be to upscale using Display tweaks (included in list) or nVidia gForce Experience

Can get the better antialising in the free version of Puredark's upscaler on the nexus if want free.
https://www.nexusmods.com/skyrimspecialedition/mods/80343

Lossless Scaling ($7)
https://store.steampowered.com/app/993090/Lossless_Scaling/
This can do upscaling but I use it for the frame generation feature as the upscaling isn't as nice as the one from PureDark.

NOTE:   Using this frame generator with pureDark's upscaler DLSS Performance I can run this list at 3440x1440 output resolution, and 120-144fps on my 3090 i9 10850 32GB Ram system.
without these two my system runs this list at 30-50 fps.
Decide for yourself what is right for you.

The MCM Menu
Alright.....There is a LOT here. I do have some profiles I set up that should be a part of this Wabbajack that are set up the way I like it. 
I recommend running the MCM Recorder Profile for Ryn if playing a female character. 
There is also one character preset included for a red headed Nord (Ryn) you can use if you'd like.

You can run these using MCM Recorder in the MCM Menu to get you started or simply go through the MCM menu one at a time, and set how you like it.

It is IMPORTANT to leave Minatours and Spiders turned OFF for OBIS, ore guardians OFF in Immersive creatures, and shadows OFF for Strange Runes as they are KNOWN to crash the game. 

Magical jumping is non-lore friendly in the recorder (means you have it by default)

Important things to know regarding paraglider and magical jumping:

Sometimes Paraglider will get stuck and not work. 
Loading from desktop will require a load from within game to reset paraglider.

Not working?  -> Quicksave -> quickload = profit

This was tracked to go to bed\ campfire\ use those blankets conflict.

How to avoid this:

Set up tent in campfire. 
Use activate key and choose 'lay down'.
USE ONLY THE JUMP KEY 'E' TO CHOOSE SLEEP.
Get up after sleeping using directional keys ONLY (NOT MENU).

If you use the activate key to sleep or get up you will need to quicksave and quick load to regain use of the paraglider.

Good Rule of Thumb for this list....Do a little jump and activate the glide crow to make sure it's working BEFORE jumping off any mountains.

Magical Jumping: this can be kind of glitchy with other mods in the list.

What I did:

Set lore friendly mode to 'OFF'. In the SKSE folder DTry Ultilities find magical jumping and comment OUT using ; everything that is not already commented out.

This disables the dash, and bash parts but keeps NO fall damage on and allows for triple jumping magical jumps by default

Some important default keys to know

Caps Lock + Enter = ENB Menu

Backspace = Immersive Equipment Displays

Shift + O = Open Animation Replacer

Ins = Blink Spell Hotkey (Can be modified in it's ini file)

X = Toggle HUD and swan dive jump

C = Short Dive jump and quicklight

Scroll wheel = walk\run speed adjustment on the fly

K (Hold) + Scroll Wheel = Zoom

Dodges= Direction + Left Shift (can be changed in ini file for TK Dodge RE)

G = walk/Run Toggle

While falling

Paraglider pull or put away = activate key

Falling arts/ skydiving =
  Adding additional control mechanics: Activating the Gale spell without equip spell :
  
-While in glider state ,pressing  Space key (Gamepad use Y) .

-While in a Falling state, pressingLeft ctrl key (Gamepad : LEFT_THUMB)
 allows for adjusting the Link-style skydiving posture.
 
-press Left Alt key (Gamepad : LEFT_SHOULDER) into accelerate state when in skydiving state
  and press sneak button Left ctrl key(Gamepad : LEFT_THUMB) again back to skydiving.
  
-press Left Shift key(Gamepad : RIGHT_THUMB) to use Air Dodge.
Some key binds like TK Dodge are in SKSE ini files so if you can't find it then it's probably in an ini file in SKSE folder of that mod.


How I set some Keys in the MCM Recorder
Page Down = Proteus Wheel

Page Up = SMP reset

; : = quicksave (but set to make these regular saves in Engine fixes)

' " = quickload

9 ( = toggle EVG traversal markers on/off

= + = PC head tracking Hello

- _ = PC head Tracking Goodbye
- 
0 ) = PC head Tracking Random Saying
  
C = Quicklight toggle
                     

Word of Warning 
Some creatures will be deleveled so you might come across a level 30 ogre at level 1 and have to run to survive. Ye have been warned!
You will learn....stick and move, stick and dodge, run and heal or just plain run away to survive at lower levels.
Recommend difficulty levels:

Level 0-10 Apprentice

Level 11-18 Adept

Level 19-25 Expert

Level 26-32 Master

Level 32 and up Legendry (if you have the stones for it)

The game also has survival built in using Sunhelm but can toggle this on or off along with Cold survival in the MCM.

Some quality of life / fun mods are also included.

Paraglider, magical jumping, bow rapid combo v3, mist flight, and others you can have fun discovering and exploring.

There are added worldspaces to explore as well.

Wyrmstooth and Beyond Reach will start at a certain level but some you will just find in your exploring like Chanterelle, The Shire, Moonpath to Elswyer, Darkend, Skyrim Sewers, and Skyrim Underground.

Shout out to some awesome people

Halgari for creation of this wonderful tool

For play testing and feedback>>

Iyreshot

Pixelnate

BiggieBoss

You people Rock!

Final words before I let you go
I designed this mod list to be tougher than anything vanilla with FAR more creatures that are tougher than stock ones.
As such I have included a mod called skyrim skill uncapper. It has an ini file you can tweak to your liking increasing (or decreasing) the amount of perk points per level as well as amount things like health, magica, and stamina go up per level. Default it is set up with an ini designed for use with Ordinator which is the main perk mod in this list.
I have also included a mod called Unlimited Rings and Amulets to offset the difficulty.
If you open the files for RLE (rogue like encounters) in MO2 left pane (explore) there are esps in there that can be added or removed from the list that can increase spawns or reduce them.
CC Survival mode will conflict with SunHelm survivial. I recommend using ONLY Sunhelm as it covers cold, eat, drink, and sleep needs.

Basically the tools are there to make it as hard or easy as you want. 
Now go forth brave adventurer, and get lost admiring the parallax mud puddles, and ice cube glaciers......But Beware as the world is full of dangers and rewards.
Have fun :)
Nico






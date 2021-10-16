![image](images/Banner.png)

# Wabbajack

## About Wabbajack and the add-on

Wabbajack allows you to install my modpack to your PC by duplicating my setup directly to your PC, including each mod, setting, output etc. If you want to learn more about Wabbajack in general, refer to Phoenix's article, [_About Wabbajack_](https://thephoenixflavour.com/wj/about-wabbajack/).

If you would like to learn more about the add-on, be sure to visit its home page [here](https://www.nexusmods.com/skyrimspecialedition/mods/51973).

---

## Game Setup

Phoenix also wrote a very detailed instructions on [how to set up your Skyrim Special Edition correctly for any Wabbajack list](https://thephoenixflavour.com/wj/wj-sse/game-setup/) and also for [installing those lists through Wabbajack](https://thephoenixflavour.com/wj/wj-sse/list-installation/). Follow those instructions carefully until you reach the _Choosing a list_ section of the list installation instructions. Then follow the instructions written below.

---

## Installation

For now The Phoenix Flavour - Dragon's Edition isn't listed in the Wabbajack Gallery and needs to be installed manually. Download `The Phoenix Flavour - Dragon's Edition.wabbajack` file from [Google Drive](https://drive.google.com/drive/folders/1cfY3C4EzMxlPaIDT3-hPlRZY4ni6lOcG?usp=sharing) and then continue following the list installation instructions, but instead of choosing _Browse Modlists_, click _Install from Disk_ and select The Phoenix Flavour - Dragon's Edition.wabbajack from a place, where you have saved it. Then continue following the Phoenix's instructions until finishing going through _Troubleshooting_ section.

---

## Configurations

By default your game is capped at 75 FPS, as the bigger number can lead to different oddities in Skyrim's physics, and so I don't recommend to change that. Also it will be borderless, so you don't need to change that either.

I have chosen _Silent Horizons ENB_ as the main ENB for the add-on. You will be able to learn why a little bit later if you want. If the ENB isn't for you and you want to change it, disable _Silent Horizons ENB Addon - Solar Cleaner_ in the _Exteriors_ section of the add-on (by clicking on a rectangle with a check-mark right next to the name of the mod on the left side of MO2).  

Now open the folder, where you have saved the add-on, and double-click on _ModOrganizer.exe_ file. You don't need to paste anything into your game's root folder anymore like it always was before thanks to the new [Game Stock folder system](https://github.com/wabbajack-tools/wabbajack/wiki/Keeping-The-Game-Folder-Clean-(via-local-game-installs)), which allows us to leave our root folder completely clean and this way more compatible with other modpacks. Now you can see the full setup - the mod order is on the left, sorted below separators that may be collapsed by default, and the load order with all plugins on the right. 

You will have 2 available profiles in your installation:
  - _The Phoenix Flavour - Dragon's Edition_;
  - _The Phoenix Flavour - Dragon's Edition (Performance)_, which uses TPF's performance tweaks (regenerated INIs, performance friendly grass mods and DynDOLOD output) to make better experience for users with low-end PCs.

Change profiles by clicking on an already active profile and choosing another profile.
![image](https://user-images.githubusercontent.com/37147270/133923965-f2164646-3bfd-4aa6-bad3-2275d1501212.png)

While following the main documentation of the add-on, users have a choice to use or not to use two sections' mods, which are [_Interface_](DOCUMENTATION.md#interface-optional) section and [_Music & Sound FX_](DOCUMENTATION.md#music--sound-fx-optional) section. For Wabbajack users two of those sections are enabled by default, but if you don't like a mod or two from there, you are free to disable them according to provided instructions in the documentation.

Some mods of TPF are disabled in both of my add-on's profiles. Those are:
  - _Adamant - Shrines and Amulets_ in TPF's _Gameplay Overhauls_ section and _Miscellaneous Tweaks Collection - Shrines Don't Cure Diseases_ in the TPF's _Miscellaneous_ section, because they both conflict with a mod in our _Gameplay Overhauls_ section called _Pilgrim - A Religion Overhaul_. Don't worry about the last disabled mod, shrines still don't cure diseases with Pilgrim.
  - _Blade and Bunt - Vanilla Difficulty Modifiers_ in TPF's _Combat & Encounters_ section, because it makes the game easier and less interesting. If you find the combat of the game too difficult even after tweaking the game's difficulty, you are free to enable the mod by clicking on a rectangle right next to its name on the left side of MO2, but then you will also need to put its plugin right next after Blade and Blunt's plugin _BladeandBlunt.esp_ on the right side of MO2 by simply dragging it.
  - _Argonian Weight Slider Affected Tails_ and _FVAR - Weight Slider Affected Tails Patch_ in TPF's _Appearance_ section, because they both conflict with a mod in our _Appearance_ section called _Equipable Beast Tails - HDT SMP (Physics)_.
  - _Classic Sprinting Redone_ in TPF's _Controls & Camera_ section, because I hate the old times function of holding down the button for sprinting. Special Edition's way of making sprinting toggable is much better (but if you somehow don't like it, feel free to enable the mod).

Finally we are ready to open and finish configuring the game. Above the load order (in the right pane), you can see the executables drop-down. Very likely _The Phoenix Flavour - Dragon's Edition_ was already selected here, so you can start the game by clicking _Run_. Now you should continue with the [_Configurations_](DOCUMENTATION.md#configurations) section of the documentation.

I hope everything was easy to understand at this point! :)

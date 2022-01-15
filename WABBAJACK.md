![image](images/Banner.png)

# Wabbajack

## About Wabbajack and the add-on

Wabbajack allows you to install my modpack to your PC by duplicating my setup directly to your PC, including each mod, setting, output etc. If you want to learn more about Wabbajack in general, refer to Phoenix's article, [_About Wabbajack_](https://thephoenixflavour.com/wj/about-wabbajack/).

If you would like to learn more general information about the add-on, be sure to visit its home page again [here](https://www.nexusmods.com/skyrimspecialedition/mods/51973). I would very strongly recommend to check Questions & Answers for the most popular questions asked by users of the add-on.

**Add-on installation's size** - ~ 140 GB (your installation folder must be unique)

**Add-on mod's size** - ~ 81 GB (your downloads folder should be the same as TPF's one to make the installation process faster and not to make you download TPF's mods once again)

---

## Requirements
  
  - [The Microsoft Visual C++ Redistributable - Visual Studio 2015, 2017, 2019, and 2022 X64](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-160#visual-studio-2015-2017-2019-and-2022);
  - [Microsoft .NET 5.0 - desktop app X64 and console app X64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime);
  - The latest version of Skyrim Anniversary Edition - 1.6.353 (free or full version).

---

## Game Setup

Phoenix also wrote a very detailed instructions on [how to set up your Skyrim Special Edition correctly for any Wabbajack list](https://thephoenixflavour.com/wj/wj-sse/game-setup/) and also for [installing those lists through Wabbajack](https://thephoenixflavour.com/wj/wj-sse/list-installation/). Follow those instructions carefully until you reach the _Choosing a list_ section of the list installation instructions. Then follow the instructions written below.

---

## Installation

For now The Phoenix Flavour - Dragon's Edition isn't listed in the Wabbajack Gallery and needs to be installed manually. Download `The Phoenix Flavour - Dragon's Edition.wabbajack` file from [Google Drive](https://drive.google.com/drive/folders/1cfY3C4EzMxlPaIDT3-hPlRZY4ni6lOcG?usp=sharing) and then continue following the list installation instructions, but instead of choosing _Browse Modlists_, click _Install from Disk_ and select _The Phoenix Flavour - Dragon's Edition.wabbajack_ from a place, where you have saved it. Then continue following the Phoenix's instructions until finishing going through _Troubleshooting_ section.

---

## Configurations

### Preparations

By default your game is capped at 75 FPS, as the bigger number can lead to different oddities in Skyrim's physics, and so I don't recommend to change that. Also it will be borderless, so you don't need to change that either.

Now open the folder, where you have saved the add-on, and double-click on _ModOrganizer.exe_ file. The new [Game Stock folder system](https://github.com/wabbajack-tools/wabbajack/wiki/Keeping-The-Game-Folder-Clean-(via-local-game-installs)) allows us to leave our Skyrim's root folder completely clean and this way more compatible with other modpacks. Now you can see the full setup - the mod order is on the left, sorted below separators that may be collapsed by default, and the load order with all plugins on the right. 

---

While following the main documentation, users have a choice to use or not to use the [_Interface_](DOCUMENTATION.md#interface-optional) section of the add-on. For Wabbajack users this section is enabled by default, but if you don't like a mod or two, you are free to disable them according to provided instructions in the documentation.

---

Some of the mods inside Mod Organizer are disabled by default in the add-on. Some of these are:
  - _Blade and Bunt - Vanilla Difficulty Modifiers_ in TPF's _Combat & Encounters_ section, because it makes the game easier and less interesting. If you find the combat of the game too difficult even after tweaking the game's difficulty, you are free to enable the mod by clicking on a rectangle right next to its name on the left side of MO2, but then you will also need to put its plugin right next after Blade and Blunt's plugin _BladeandBlunt.esp_ on the right side of MO2 by simply dragging it.
  - _Classic Sprinting Redone_ in TPF's _Controls & Camera_ section, because I hate the old times function of holding down the button for sprinting. Special Edition's way of making sprinting toggable is much better (but if you somehow don't like it, feel free to enable the mod).
  - All the mods in _WIDESCREEN SUPPORT_ section, because obviosuly only a few have those huge monitors. If you are actually one of them, enable all the mods under this section and you are done.

> Do not touch any other disabled mods.

Finally we are ready to open and finish configuring the game. Above the load order (in the right pane), you can see the executables drop-down. Very likely _The Phoenix Flavour - Dragon's Edition_ was already selected here, so you can start the game by clicking _Run_.

---

### In-Game Adjustments

Customize your character to your heart's content (while being reasonable). 
If you want to use hair with physics for men, you will find instructions on how to obtain them a bit later.

---

When Ralof or Hadvar frees you, don’t go anywhere right away.
Wait a bit for everything to load (wait after all messages on the top
left side of the screen disappear).

---

Now you can turn on the following mods to decide if you would want to use them. They affect just the visual side of the game. 
If you aren't a fan, just press the same button once again to turn them off. 

* **Look What You See** - Press your *V* key.
* **Animated Shouts** - Press your right *Alt* key.
> You will be able to see this mod in action only after getting your first shout. Have left a tip on this one in my gameplay guide too.

Also we have toggable HUD, so feel free to press *X* key to turn it on and off when you need that.

---

Some quick tips before the end:

* **About the option to remove your tail** - It is weird, but you will actually need to equip another tail to get rid from... "them both". To get the tail, open your inventory and in misc item section find an item called _AddItemMenu_ and click on it. Another menu with 4 items will pop up. Grab an item with a search option. Then open your inventory and use the item with the search option. Type `tail` in AddItemMenu's searcher. Choose the mod's plugin and grab your tail. Then equip it like gear and your tail will be gone.
* **About hair with physics for men** - You will need to use AddItemMenu again, but this time type the word `hair`.
* **TK Dodge RE** - _Mouse 3_ button is chosen by default for dodging (in other games _Mouse 4_ button - Skyrim's oddities). Feel free to change that by using instructions [here](DOCUMENTATION.md#tk-dodge-re).
* **About fast travelling (if you are using the *Interface* section)** - By default fast travel is disabled, because it becomes much more interesting that way (you travel and discover much more) and there are plenty of ways to travel around - as in vanilla (horses, ferry, boats), paragliding, spells, another mean, which is tied to a quest (don't want to spoil that) etc. If you still aren't sold, feel free to reenable it by disabling _Disable Fast Travel SKSE - No Janky Map UI_ mod under the _Interface_ separator.

---

**And some important info.** _Helgen Reborn_ note in The Bannered Mare can be taken and read **only** after 5 in-game days after you have finished the main quest _Unbound_. Be sure to remember.

---

## Farewells

And that's it! You are ready for the action.

If you have any questions following these instructions, something doesn't allow you to finish the setup (but before that you have actually checked you have all the requirements for the add-on) or if you find a typo or any other mistake in the documentation, 
feel free to report in [TPF Discord server](https://discord.gg/tpf)'s _#tpf-de-wabbajack-support_ channel. If you have experienced a bug during your walkthrough, jump in [*Bugs*](DOCUMENTATION.md#bugs) section first.

If you want to learn more about what the add-on offers and what actually many of the mods do, check [Gameplay Guide](DOCUMENTATION.md#gameplay-guide). 

If you would like to make any recommendations after looking into what the add-on has to offer or to give me an advice, 
please use _Posts_ feature on Nexus or use _#tpf-de-feedback_. Suggestions on how to improve the documentation are also welcome on GitHub.
Before asking additional questions be sure to check the gameplay guide mentioned before and the _Questions & Answers_ section on the Nexus.

If you want to learn more about the ENB we are using, drop [here](DOCUMENTATION.md#enb).

> If the ENB isn't for you and you want to change it, disable _Silent Horizons ENB Addon - Solar Cleaner_ in the _Exteriors_ section of the add-on (by clicking on a rectangle with a check-mark right next to the name of the mod on the left side of MO2).  

If you want to help me, don't forget to endorse the add-on’s page on Nexus and write something positive for me to read (I am happy to hear from people in Discord too). 
If you want to help even more, you can donate to me (via PayPal) by pressing [here](https://www.paypal.com/donate?hosted_button_id=9K4MGQC23DRYL).

I will post about updates for the add-on in _#updates_ channel.

If you just want to chat, share your beautiful screenshots, builds or performance parameters, I am still happy to see you both on Nexus and in Discord. :)

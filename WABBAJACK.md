![image](images/Banner.webp)

# Wabbajack

## About Wabbajack and the fork

Wabbajack allows you to install my modpack to your PC by duplicating my setup directly to your PC, including each mod, setting, output etc. 
If you want to better understand the general idea of Wabbajack, refer to a Reddit article 
[_What Wabbajack is and Why You Should Care_](https://www.reddit.com/r/skyrimmods/comments/mbfk5f/what_wabbajack_is_and_why_you_should_care/).

If you would like to learn more general information about the fork, be sure to visit its home page again [here](https://www.nexusmods.com/skyrimspecialedition/mods/51973). I would very strongly recommend to check _Questions & Answers_ section for the most popular questions asked by users of the add-on.

---

## Requirements

  - Fork's installation size - ~ 153 GB (~ 13GB is copied from your Skyrim SE install, your installation folder must be unique)
  - Fork mod's size - ~ 84 GB (your downloads folder should be the same as TPF's one to make the installation process faster and not to make you download TPF's mods once again)
  
  
  - [The Microsoft Visual C++ Redistributable - Visual Studio 2015, 2017, 2019, and 2022 X64](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-160#visual-studio-2015-2017-2019-and-2022);
  - [Microsoft .NET 5.0 - desktop app X64 and console app X64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime);
  - The latest version of Skyrim Anniversary Edition - 1.6.353 (free or full version).

---

## Steam Setup

### Steam Library Should Be Outside Windows Related Folders

The best location would be _C:\Steam_. Such location is also called _the root of the drive_.

If you have your Steam library inside Windows related folder such as _Desktop, Program Files, Downloads, Documents_ or _OneDrive_ etc., 
use a guide from [here](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it outside of one of these folders.

### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in _Documents/My Games/_ by deleting the contents in it.

### Set The Game's Language To English

Right click on your `The Elder Scrolls IV: Skyrim Special Edition` game, select `Properties`, navigate to the `LANGUAGE` tab and select `English` from the dropdown menu.

### Change Game's Update Behaviour

Head over to the `Properties` again, navigate to the `UPDATES` tab and change _AUTOMATIC UPDATES_ parameter to `Only update this game when I launch it`. 

### Start Skyrim At Least Once

Start the game from Steam and and let it do the initial graphics check. Do not worry about this part as the installation will replace this graphics settings. Start the game and exit once you're in the main menu.

---

## Installation

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases), make a folder inside the root of the drive like _C:\Wabbajack_ and place the `Wabbajack.exe` file inside it. Again this folder must not be in the Windows related folders.

The downloading and installation process can take a very long time, it depends on your system's specifications and on your internet's speed.
> It will be way faster if you have saved 

1. Open `Wabbajack.exe`.
2. Click on `Browse Modlists` and download The Phoenix Flavour - Dragon's Edition from the gallery.
3. Once the download is done, set the installation location again somewhere outside Windows related folders like `C:/Modlists/The Phoenix Flavour - Dragon's Edition` or `C:/The Phoenix Flavour - Dragon's Edition`. The downloads path should automatically fill in the installation path.
4. Click the Go/Begin button
5. Wait for Wabbajack to finish
6. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

Phoenix also wrote a very detailed instructions on [how to set up your Skyrim Special Edition correctly for any Wabbajack list](https://thephoenixflavour.com/wj/wj-sse/game-setup/) and also for [installing those lists through Wabbajack](https://thephoenixflavour.com/wj/wj-sse/list-installation/). 
Follow those instructions carefully (while obviously choosing _The Phoenix Flavour - Dragon's Edition_ as the list you want to install) until you reach the _Troubleshooting_ section of the list installation instructions.

---

## Configurations

By default your game is capped at 75 FPS (to avoid any issues related to Skyrim's physics) and is borderless.

Now open the folder, where you have saved the add-on, and double-click on _ModOrganizer.exe_ file. The new [Game Stock folder system](https://github.com/wabbajack-tools/wabbajack/wiki/Keeping-The-Game-Folder-Clean-(via-local-game-installs)) allows us to leave our Skyrim's root folder completely clean and this way more compatible with other modpacks. Now you can see the full setup - the mod order is on the left, sorted below separators that may be collapsed by default, and the load order with all plugins on the right. 

---

While following the main documentation, users have a choice to use or not to use the [_Interface_](DOCUMENTATION.md#interface-optional) section of the add-on. For Wabbajack users this section is enabled by default, but if you don't like a mod or two, you are free to disable them according to provided instructions in the documentation.

---

Some of the mods inside Mod Organizer are disabled by default in the add-on. Some of these are:
  - _Blade and Bunt - Vanilla Difficulty Modifiers_ in TPF's _Combat & Encounters_ section, because it makes the game easier and less interesting. If you find the combat of the game too difficult even after tweaking the game's difficulty, you are free to enable the mod by clicking on a rectangle right next to its name on the left side of MO2, but then you will also need to put its plugin right next after Blade and Blunt's plugin _BladeandBlunt.esp_ on the right side of MO2 by simply dragging it.
  - _Classic Sprinting Redone_ in TPF's _Controls & Camera_ section, because I hate the old times function of holding down the button for sprinting. Special Edition's way of making sprinting toggable is much better, but if you somehow don't like it, feel free to enable the mod.
  - All the mods in _WIDESCREEN SUPPORT_ section, because obviosuly only a few have those huge monitors. If you are actually one of them, enable all the mods under this section and you are done.
> Do not touch any other disabled mods for now.

Finally we are ready to open and finish configuring the game. Above the load order (in the right pane), you can see the executables drop-down. Very likely _The Phoenix Flavour - Dragon's Edition_ was already selected here, so you can start the game by clicking _Run_.

---

## In-Game Adjustments

And now we are ready to jump into the game.

At the beginning, we need to activate our character's high poly head (much more detailed head than the vanilla one, which you can also shape in much more ways) 
in character creation menu and then our hair, brows (and/or scars, beard) will look excellent on us.

<p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/37147270/151776057-aaa74ddf-396d-4bc4-9c83-18be28950be6.png" /> 
</p>

Then customize your character to your heart's content (while being reasonable). Hair with physics for women are obtainable by choosing hair with _KSHairdosSMP.esp_ near their name.
<p align="center">
    <img width="75%" src="https://user-images.githubusercontent.com/37147270/151706652-f8f91309-203f-4b10-a975-8be565db54fd.png" /> 
</p>
If you want to use hair with physics for men, you will find instructions on how to get them a bit later.

---

After Ralof or Hadvar frees you, don’t go anywhere right away. Wait a bit for everything to load 
(it will be awesome if you let all messages on the top left side of the screen disappear).

Now you can turn on the following mods to decide if you would want to use them. They affect just the visual side of the game. 
If you aren't a fan, just press the same button once again to turn them off. 

* **Look What You See** - Press your *V* key.
* **Animated Shouts** - Press your right *Alt* key.
> You will be able to see this mod in action only after getting your first shout. Have left a tip on this one in my gameplay guide for the add-on too if you forget about it.

Also we have toggable HUD, so feel free to press *X* key to turn it on and off when you need that.

Some quick tips before the end:

* **About the option to remove your tail** - It is weird, but you will actually need to equip another tail to get rid from... "them both". To get the tail, open your inventory and in misc item section find an item called _AddItemMenu_ and click on it. Another menu with 4 items will pop up. Grab an item with a search option. Then open your inventory and use the item with the search option. Type `tail` in AddItemMenu's searcher. Choose the mod's plugin and grab your tail. Then equip it like gear and your tail will be gone.
* **About hair with physics for men** - You will need to use AddItemMenu again, but this time type the word `hair`.
* **About ENB** - `F10` button toggles the ENB effect, `F11` opens the ENB GUI, `F7` toggles an FPS counter. Feel free to make screenshots with Steam by using `F12`. 
* **About fast travelling (if you are using the *Interface* section)** - By default fast travel is disabled, because it becomes much more interesting that way (you travel and discover much more) and there are plenty of ways to travel around - as in vanilla (horses, carriages, boats), paragliding, spells, another mean, which is tied to a quest (don't want to spoil that) etc. If you still aren't sold, feel free to reenable it by disabling _Disable Fast Travel SKSE - No Janky Map UI_ mod under the _Interface_ separator.

---

**And some important info.** _Helgen Reborn_ note in The Bannered Mare can be taken and read **only** after 5 in-game days after you have finished the main quest _Unbound_.

Also a reminder that the modlist uses a mod called _End Times_, which will **end the game** if don't finish the main quest line by default in one in-game year (approximately **18 real life days, that means 432 real life hours**). Go into the mod's mod configuration menu and lock the slider not to be tempted to change the final date all time. 
That should be enough (and even feels right somehow) to do many other things in between saving the world for the first time. 
And don't worry - **the game won't end if you finish the main quest**. You can always enter into MCM again to see how much time you have left. Be sure to remember.

---

## Thank You

And that's it! You are ready for the action.

If you have any questions following these instructions, something doesn't allow you to finish the setup (but before that you have actually checked you have all the requirements for the add-on) or if you find a typo or any other mistake in the documentation, 
feel free to report in [TPF Discord server](https://discord.gg/tpf)'s _#tpf-de-wabbajack-support_ channel or [Wabbajack Discord server](https://discord.gg/wabbajack)'s 
#tpf-dragons-edition-support channel. 
If you have experienced a bug during your walkthrough, jump in [*Bugs*](DOCUMENTATION.md#bugs) section first.

If you want to learn more about what the add-on offers and what actually many of the mods do, check [Gameplay Guide](DOCUMENTATION.md#gameplay-guide). 

If you would like to make any recommendations after looking into what the add-on has to offer or to give me an advice, 
please use _Posts_ feature on Nexus or use _#tpf-de-feedback_  on TPF's Discord server. Suggestions on how to improve the documentation are also welcome on GitHub.
Before asking additional questions be sure to check the gameplay guide mentioned before and the _Questions & Answers_ section on Nexus.

If you want to learn more about the ENB we are using, drop [here](DOCUMENTATION.md#enb).
> If the ENB isn't for you and you want to change it, disable _Silent Horizons ENB Addon - Solar Cleaner_ in the _Exteriors_ section of the add-on (by clicking on a rectangle with a check-mark right next to the name of the mod on the left side of MO2). Then delete add-on's _enbseries_ folder, _enblocal.ini_ and _enbseries.ini_ files from the add-ons' _Stock Game_ folder and replace with the ones from your desired ENB. Also just want to warn you that your key bindings are going to be different that the ones, which 
were in the add-on at the beginning. Feel free to use the instructions mentioned before to change them back. 

If you want to help me, don't forget to endorse the add-on’s page on Nexus and write something positive for me to read (I am happy to hear from people in Discord too). 
If you want to help even more, you can donate by pressing the button right below. 

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H6ABHYO)

I will post about updates for the add-on in both TPF's and Wabbajack's Discord servers.

If you just want to chat, share your beautiful screenshots, builds or performance parameters, I am still happy to see you around on Nexus and in Discord. :)

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

### Preparations

By default your game is capped at 75 FPS, as the bigger number can lead to different oddities in Skyrim's physics, and so I don't recommend to change that. Also it will be borderless, so you don't need to change that either.

I have chosen _Silent Horizons ENB_ as the main ENB for the add-on. You will be able to learn why a little bit later if you want. If the ENB isn't for you and you want to change it, disable _Silent Horizons ENB Addon - Solar Cleaner_ in the _Exteriors_ section of the add-on (by clicking on a rectangle with a check-mark right next to the name of the mod on the left side of MO2).  

Now open the folder, where you have saved the add-on, and double-click on _ModOrganizer.exe_ file. You don't need to paste anything into your game's root folder anymore like it always was before thanks to the new [Game Stock folder system](https://github.com/wabbajack-tools/wabbajack/wiki/Keeping-The-Game-Folder-Clean-(via-local-game-installs)), which allows us to leave our root folder completely clean and this way more compatible with other modpacks. Now you can see the full setup - the mod order is on the left, sorted below separators that may be collapsed by default, and the load order with all plugins on the right. 

---

While following the main documentation, users have a choice to use or not to use the [_Interface_](DOCUMENTATION.md#interface-optional) section of the add-on. For Wabbajack users this section is enabled by default, but if you don't like a mod or two, you are free to disable them according to provided instructions in the documentation.

---

Some mods of TPF are disabled in both of my add-on's profiles. Those are:
  - _Adamant - Shrines and Amulets_ in TPF's _Gameplay Overhauls_ section and _Miscellaneous Tweaks Collection - Shrines Don't Cure Diseases_ in the TPF's _Miscellaneous_ section, because they both conflict with a mod in our _Gameplay Overhauls_ section called _Pilgrim - A Religion Overhaul_. Don't worry about the last disabled mod, shrines still don't cure diseases with Pilgrim.
  - _Blade and Bunt - Vanilla Difficulty Modifiers_ in TPF's _Combat & Encounters_ section, because it makes the game easier and less interesting. If you find the combat of the game too difficult even after tweaking the game's difficulty, you are free to enable the mod by clicking on a rectangle right next to its name on the left side of MO2, but then you will also need to put its plugin right next after Blade and Blunt's plugin _BladeandBlunt.esp_ on the right side of MO2 by simply dragging it.
  - _Argonian Weight Slider Affected Tails_ and _FVAR - Weight Slider Affected Tails Patch_ in TPF's _Appearance_ section, because they both conflict with a mod in our _Appearance_ section called _Equipable Beast Tails - HDT SMP (Physics)_.
  - _Classic Sprinting Redone_ in TPF's _Controls & Camera_ section, because I hate the old times function of holding down the button for sprinting. Special Edition's way of making sprinting toggable is much better (but if you somehow don't like it, feel free to enable the mod).

Finally we are ready to open and finish configuring the game. Above the load order (in the right pane), you can see the executables drop-down. Very likely _The Phoenix Flavour - Dragon's Edition_ was already selected here, so you can start the game by clicking _Run_.

### In-Game Adjustments

At the beginning, don’t be scared when you see that your character’s hair and/or beard isn't right. we need to actually activate our high poly head in Racemenu and then our hair will look fine. Also choose a beard from High Poly Head and it will look good if that is needed.

<p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/37147270/130331927-051552a4-64d6-420b-8fa4-e18fd232ee4e.png" /> 
</p>

Then find the *Weapons* category and change settings to the same ones
you see below.

<p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/37147270/130331938-43bb6a6b-dee2-439c-8fae-f3780a734c8a.png" /> 
</p>

After that customize your character to your heart's content. If you want to use hair with physics for men, you will find instructions on how to obtain them a bit later.

---

When Ralof or Hadvar frees you, don’t go anywhere right away.
Wait a bit for everything to load (wait after all messages on the top
left side of the screen disappear).

---

Then remember to turn the _Depth of Field_ slider all the way down in the in-game settings _Display_ section. Then you can continue with MCM configurations below. 
They are **optional, but higly recommended** (especially the one for potions and for ending the world). Blame yourself (not dragon) if you didn't and
don't like something later. :P 

* **Cond. Expressions** - Disable out of stamina, in pain,
headache/diseased expressions. It will look odd if our character is constantly sad and in pain.
* **Diziet’s Auto Outfits** - In configuration settings, check the option
to unset all hotkeys for this mod. The mod's main functionality doesn't even need them and it allows us to use them for different mods.
* **End Times** - This mod makes us not decline the main quest of Skyrim for all time. Especially considering the fact that is it tied to some of the added quest mods and 
that is not immersive to catch butterflies instead of saving the world, I think it is a very good addition. 
Lock the slider to not be tempted to change the final date all time. 
One in-game year (approximately **18 real life days**) is good enough (and even feels right somehow) as a default setting to 
do many other things in between saving the world for the first time. And don't worry - **the game won't end if you kill Alduin**. Also disable the spell and 
countdown as those are pretty annoying. You can always enter into MCM again to see how much time you have left. 
**Be warned that this is active even if you don't change things anyhow.**
* **Hide Your Quests** - I recommend to hide right away all quests you get
right at the beginning except the main one (Unbound), because you mustn't
start Helgen Reborn quest right at the beginning (read Gameplay Guide
for more information) and because The Sinister Seven quest isn’t the one
where you go to objective, just hide it, quest givers will look for you
when a time comes and then you can unhide it. Tried to understand how to make the quest with
Thalmor involved appear after you finish Diplomatic Immunity quest for
immersiveness, but couldn't, will look at that later, so let it be this
way - you heard about what is happening from elves when you were trying
to cross Skyrim’s border. You can do it as fast as you want, but enemies
won’t be the easiest ones to beat. I would recommend getting at least
level 15. Don't forget to unhide the quests, when you actually would want and would be able to start them.
* **Smart NPC Potions** - Standard potion drops aren’t affected, so set an
option to drop this mod’s potions to 0%. Change the chance of NPCs
having potions to 20% (we don’t want everyone to have those, right?) and
the number of potions to 3.
* **SmoothCam (if you are using the mod from the *Interface* section)** - Activate the preset in *Presets* by pressing on *Slot 1:
DocOct* in *Load Preset*. If you want, you can also enable
shoulder swapping in *Following* by choosing your shoulder swap key. I
recommend one of your mouse’s buttons if you have many buttons on it.
Then in *Crosshair*, enable *3D Magic Crosshair,* enable size manipulation, set minimum and
maximum crosshair size to 40, then set stealth meter's Y offset to 200.
* **Werewolf Widget Control (if you are using the mod from the *Interface* section)** - Change opacity to 60 and
text colour to white. The timer won’t work during your first
transformation, after transforming at least once, save your game. When
you transform again, it will be at the top of the screen near your
compass.

---

Now we need to activate some of the mods to actually make them work. Close the MCM menu and the system page and do this:

* **Animated Shouts** - Press your right *Alt* key.
* **Look What You See** - Press your *V* key.

---

If you don't care about points below, feel free to skip. I **definitely recommend** you to check the one about Helgen Reborn book and being neutral during the war. 
So about these things for you to know about:

* **About the option to remove your tail** - It is weird, but you will actually need to equip another tail to get rid from... "them both". To get the tail, open your inventory and in misc item section find an item called _AddItemMenu_ and click on it. Another menu with 4 items will pop up. Grab an item with a search option. Then open your inventory and use the item with the search option. Type `tail` in AddItemMenu's searcher. Choose the mod's plugin and grab your tail. Then equip it like gear and your tail will be gone.
* **About hair with physics for men** - You will need to use AddItemMenu again, but this time type the word `hair`.
* **About fast travelling (if you are using the *Interface* section)** - By default fast travel is disabled. Feel free to reenable it by disabling _Disable Fast Travel SKSE - No Janky Map UI_ mod under the _Interface_ separator.
* **TK Dodge RE** - _Mouse 3_ button is chosen by default for dodging. Feel free to change that by using instructions [here](DOCUMENTATION.md#tk-dodge-re).
* **About Helgen Reborn book in your inventory** - Can be read **only** after 5 in-game days after you have finished the main quest *Unbound*. If you want to learn more, go [here](DOCUMENTATION.md#gameplay-guide). Also remember to unhide the quest through _Hide Your Quests_ MCM if you have decided to hide it.
* **About being neutral during the war** - There will be a note in Dragonseach about neutrality in war. Pick it up only if you want to be neutral during the war. Like before, more information about that can be found [here](DOCUMENTATION.md#gameplay-guide).

---

And that's it! You are ready for the action.

If you have any questions following the add-on's instructions or if you find a typo or any other mistake in the documentation, feel free to report in 
TPF Discord server's [#tpf-addons-support](https://discord.gg/jE5UrSDz) channel. If you would like to make any recommendations after looking into what the add-on has to offer or to give me an advice, please use Posts feature on Nexus or use [#tpf-addons-feedback](https://discord.gg/g9NB7Eqv). Suggestions on how to improve the documentation are also welcome on GitHub. I will post about updates for the add-on in [#the-addons-updates](https://discord.gg/tpf) channel.
If you have experienced a bug during your walkthrough, jump in [*Bugs*](DOCUMENTATION.md#bugs) section first.

If you want to learn more about what the add-on offers, check [Gameplay Guide](DOCUMENTATION.md#gameplay-guide). 
If you want to learn more about the ENB we are using, drop [here](DOCUMENTATION.md#enb).
If you want to help me, don't forget to endorse the add-on’s page on Nexus and write something positive for me to read (I am happy to hear from people in [Discord](https://discord.gg/tpf) too). 
If you want to help even more, you can donate to me (via PayPal) by pressing [here](https://www.paypal.com/donate?hosted_button_id=9K4MGQC23DRYL).

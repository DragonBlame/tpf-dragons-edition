![image](images/Banner.png)

# Documentation

## Table of Contents

[Getting Started](#getting-started)

[Interface (optional)](#interface-optional)  
[New Content](#new-content)  
[Exteriors](#exteriors)  
[Interiors](#interiors)  
[Apparel & Weapons](#apparel--weapons)  
[Appearance](#appearance)  
[Gameplay Overhauls](#gameplay-overhauls)  
[Miscellaneous](#miscellaneous)  
[Skeleton & Animations](#skeleton--animations)  
[NPC Overhauls](#npc-overhauls)  
[Salt & Wind Hair Retextures](#salt--wind-hair-retextures)  
[Literally Unplayable](#literally-unplayable)  
[Final Patches](#final-patches)  
[Alternate Start](#alternate-start)  
[Patcher Output](#patcher-output)

[Preparations](#preparations)  
[Configurations](#configurations)  
[Thank You](#thank-you)

[ENB](#enb)  
[Gameplay Guide](#gameplay-guide)  
[Bugs](#bugs)  

---

## Getting Started

Select _Profiles_ option from the Mod Organizer 2 (MO2) menu, select your TPF profile, which you use for playing (basic or performance version), 
and select _Copy_ on the right side and then name the copied profile `The Phoenix Flavour - Dragon’s Edition` 
(and add `(Performance)` to the name if you have copied the performance version of TPF).

---

## Interface (optional)

Create a separator and name it `INTERFACE EXTENDED` and place it directly below the *INTERFACE* separator (and its mods). 
Change its colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this separator in the same order.

This category's mods are optional - you can just skip it or install the mods you like. There will be instructions on files, which are needed, 
if you have decided to use one or more mods. Other sections mods are all obligatory and can't be skipped.

### [ReCleaned Menu](https://www.nexusmods.com/skyrimspecialedition/mods/26680)

**Main files** - ReCleanedMenus

*I prefer the vanilla-style main menu. It also doesn’t mess up so much with the beautiful background.*

### [Font Overhaul - Natural Typefaces for Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/2880)

**Main files** - Font Overhaul - All In One Installer

**FOMOD** - Whichever options you like. I recommend all the default options.

*Sovngarde font looks a little bit cartoonish to me, while Fertigo Pro font from this fonts' pack is looking good within Skyrim's theme and is more usual, 
but not too ordinary. The mod even changes fonts for notes and journals, which I always wanted to change before too.*

### [12th Century Book Font](https://www.nexusmods.com/skyrim/mods/72159)

**Main files** - Font

*Replaces font in Skyrim's books to look not as modern, more sophisticated.*

### [Consolas Font - Font Overhaul - 12th Century Book Font Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51973)

**Needed if you use both Font Overhaul - Natural Typefaces for Skyrim and 12th Century Book Font.**

**Optional files** - Consolas Font - Font Overhaul - 12th Century Book Font Patch

### [Consolas Font - Sovngarde Font - 12th Century Book Font Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51973)

**Needed if you use TPF's default Sovngarde font and 12th Century Book Font.**

**Optional files** - Consolas Font - Sovngarde Font - 12th Century Book Font Patch

### [SmoothCam](https://www.nexusmods.com/skyrimspecialedition/mods/41252)

**Main files** - SmoothCam

**FOMOD** - `SmoothCam SSE, ESL`.

**Instructions** - rename the mod’s plugin to *SmoothCam.esp*.

*Have you ever been in a situation, 
when you were playing in third person mode and fighting your enemy and you thought that you would land your arrow or a spell on the enemy, 
because your crosshair was right on them, but Skyrim has decided otherwise... Then this is a mod for you.*

### [iHUD - SmoothCam Automated Compatibility Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51918)

**Not needed without SmoothCam. Recommended with it.**

**Main files** - iHUD - SmoothCam Automated Compatibility Patch

*SmoothCam has its own crosshair, which appears right, when you aim. We need this patch to disable our basic crosshair not to confuse us, 
while we are trying to shoot, roast, electrocute, freeze etc. things.*

### [SmoothCam - DocOct Preset](https://www.nexusmods.com/skyrimspecialedition/mods/45557)

**Not needed without SmoothCam. Recommended with it.**

**Main files** - SmoothCam - DocOct Preset

*I have tried many presets and this one feels great for playing the game, especially for our cause - aiming in third person mode.*

### [Simple Activate](https://www.nexusmods.com/skyrimspecialedition/mods/56767)

**Main files** - Simple Activate SKSE - SE

**INI** - **Only** in line 86, remove everything after _Custom Locked Tag =_, so you can see levels of locks on things.

*Buttons' image, which we use to interact with objects in Skyrim, is disabled in TPF, so let's do that with the text of these buttons too.*

### [Quick Loot RE](https://www.nexusmods.com/skyrimspecialedition/mods/21085)

**Old files (v. 2.8.6.)** - QuickLootRE

*One of the best additions to Fallout 4 (FO4) was the looting menu,
which appears right when you move your cursor over lootable item without need to open game's full menu. This mod allows us to use this addition,
but in Skyrim.*

### [No Lockpick Activate](https://www.nexusmods.com/skyrimspecialedition/mods/26790)

**Needed if you want to use Quick Loot RE.**

**Main files** - No Lockpick Activate

*Fixes game's and looting menu mod's interaction, where you would be forced into the full menu upon unlocking container. 
It also affects every other locked object, so, for example, you have to interact with doors after unlocking them to open them.*

### [Minimalist Quick Loot](https://www.nexusmods.com/skyrimspecialedition/mods/45581)

**Not needed without Quick Loot RE. Recommended with it.**

**Main files** - Minimalist Quick Loot

**FOMOD** - Whichever options you like. I recommend `With Container Title, Original Position Modified Size`.

*Useful to make Quick Loot's interface smaller and less bulky by making it transparent.*

### [Better SkyUI Config](https://www.nexusmods.com/skyrimspecialedition/mods/49095)

**Main files** - Better SkyUI Config

*Changes default SkyUI's sorting to be more user friedly by sorting all items by their type, 
active effects by their expiration time and by making equipped items grouped right at the top.*

### [moreHUD Inventory Edition](https://www.nexusmods.com/skyrimspecialedition/mods/18619)

**Old files** - moreHUD Inventory Edition Loose Version - Pre AE

*It makes you aware of known weapon and armor enchantments, 
books you have read and it tells you about which kind of skill you can level by reading book.*

### [Detailed Mine Markers](https://www.nexusmods.com/skyrimspecialedition/mods/3172)

**Main files** - Detailed Mine Markers v1.4

**FOMOD** - Whichever options you like, except the one you need to use - `Install USSEP Compatibility`. 
I recommend lore friendly markers with an additions of new markers for mines.

*Finally I won't need to ask Google about where can I get specific kind of ore. It is enough to use the search functionality in our map.*

### [Disable Fast Travel SKSE - No Janky Map UI](https://www.nexusmods.com/skyrimspecialedition/mods/54217)

**Old files (v. 1.0.)** - Disable Fast Travel

**Instructions** - go to _powerofthree's Tweaks_'s INI (TPF's mod in the _Fixes_ section), in line 7, change _Map Marker Placement Fix_ to `false`, so your game won't CTD if you want just to place a marker on one of the locations marked on your map.

*There are many ways of how can we travel around Skyirim even without considering the additions from the add-on, 
so let us immersively travel around Skyrim without the temptation of fast tavelling with a chance to discover even more secrets lying around. 
Probably it is a mod, which you love or hate, and considering the fact that it touches the map, I have decided to put it here.*

### [Werewolf Transformation Timer](https://www.nexusmods.com/skyrimspecialedition/mods/45326)

**Main files** - Werewolf Transformation Timer

*Informs us about how much time you have left before you need to find another body to feed and 
not to think about it every single time you transform into werewolf.*

### [Oxygen Meter](https://www.nexusmods.com/skyrimspecialedition/mods/57452)

**Main files** - Oxygen Meter - SSE

*Finally I can stop being scared of drowning, while just wanting to loot that chest underwater.*

---

## New Content

The beast of this add-on comes too early (well, for me it came as the
last one, but you got the idea). The point of this section is to add
content to our beloved Skyrim to make the game even more interesting. I
won’t write any descriptions of mods (if you don’t count the gameplay
guide at the end) as I don’t want to spoil the fun (and because I am too
lazy at this point and just want to play a bit). And why should I? These
mods talk for themselves. They will be great adjustments to already
existing content and some of these are the most popular and loved quest
mods in Nexus Skyrim Special Edition’s page, so I hope you are hyped the
same way as I was (and still am).

Create a separator and name it `NEW CONTENT` and place it directly below
the *GRAPHICS BASELINE* separator (and its mods). Change its colour, so that it
won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

### [Nilheim - Misc Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/53792?tab=files)

**Main files** - Nilheim - Quest Expansion

### [House of Horrors - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/57285?tab=files)

**Main files** - House of Horrors - Quest Expansion

### [The Only Cure - Quest Expansion](https://www.nexusmods.com/skyrimspecialedition/mods/57683?tab=files)

**Main files** - The Only Cure - Quest Expansion

### [Winterhold Deep Sea Ruins](https://www.nexusmods.com/skyrimspecialedition/mods/53707?tab=files)

**Main files** - winterholddeepsearuins

### [Obscure's College of Winterhold](https://www.nexusmods.com/skyrimspecialedition/mods/20514?tab=files)

**Main files** - Obscure's College of Winterhold

**FOMOD** - `Immersive College NPCs Integration, Recommended Interiors,
New Music Plus Vanilla Music, Relighting Skyrim, Book Covers Skyrim,
Quests are in Skyrim, Audio Overhaul, Artifacts - The Tournament of the
Ten Bloods, Interesting NPCs, Mysticism - A Magic Overhaul, The Tools of
Kagrenac, Viewable Faction Ranks, WACCF - Armor and Clothing Extension,
Weapons Armor Clothing and Clutter Fixes 2.0+, The Great Cities - Minor Cities and Towns`.

### [Forsworn Gravesingers](https://www.nexusmods.com/skyrimspecialedition/mods/40143?tab=files)

**Main files** - Gravesingers

### [Forsworn Skinchangers](https://www.nexusmods.com/skyrimspecialedition/mods/34900?tab=files)

**Main files** - Skinchangers v1

### [Civil War Deserters](https://www.nexusmods.com/skyrimspecialedition/mods/44497?tab=files)

**Main files** - Civil War Deserters

### [Improved Follower Dialogue - Lydia](https://www.nexusmods.com/skyrimspecialedition/mods/38473?tab=files)

**Main files** - Improved Follower Dialogue - Lydia

**FOMOD** - `Unofficial Skyrim SE Patch`.

### [Boethiah for Good Guys](https://www.nexusmods.com/skyrimspecialedition/mods/329?tab=files)

**Main files** - Main File

Wanted to leave some comments here and there for the future, when you
will learn what mods do.

*You can make debates about this mod being immersive or
not. But at the same time you can kick Boethiah out of their cloud of thinking that
everyone is just going to murder for them alone and at the same time not
kill our improved followers. Win-win situation for me.*

### [Thieves Guild For Good Guys](https://www.nexusmods.com/skyrimspecialedition/mods/10745?tab=files)

**Main files** - Thieves Guild For Good Guys - Taking Care of Business
Redux 4.0

*Finally you can put Maven in her place too - that is good enough for
me. Not even talking about Thieves Guild becoming something more than
just a bunch of ordinary thieves united.*

### [Opulent Thieves Guild](https://www.nexusmods.com/skyrimspecialedition/mods/931?tab=files)

**Main files** - Opulent Thieves Guild

**Update files** - Update ESL Patch - Created by Erstam

**Merge** - Merge both files.

### [Opulent Thieves Guild - FPS Fix](https://www.nexusmods.com/skyrimspecialedition/mods/41309?tab=files)

**Main files** - Opulent Thieves Guild - FPS Fix

**FOMOD** - `SMIM Barrels`.

### [Opulent Thieves Guild Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/35261?tab=files)

**Main files** - Opulent Thieves Guild Patch Collection

**FOMOD** - `USSEP`.

### [Adoption Without Murder](https://www.nexusmods.com/skyrimspecialedition/mods/46741?tab=files)

**Main files** - Adoption without Murder

### [Dark Brotherhood Reborn - Dawnstar Sanctuary](https://www.nexusmods.com/skyrimspecialedition/mods/22070?tab=files)

**Main files** - Dark Brotherhood Reborn - Dawnstar Sanctuary

### [Dark Brotherhood Reborn - Patches, Tweaks and Enhancements](https://www.nexusmods.com/skyrimspecialedition/mods/34909?tab=files)

**Main files** - Dark Brotherhood Reborn - Patch Collection FOMOD

**FOMOD** - `USSEP, Save The Dark Brotherhood (SSE), The Dark Brotherhood
of Old, general Tweaks`.

### [Save The Dark Brotherhood](https://www.nexusmods.com/skyrimspecialedition/mods/33461?tab=files)

**Main files** - Save the Dark Brotherhood 1.1

*Unfortunately, it won’t be canon, but let’s be honest - without at
least a bunch of the members, The Dark Brotherhood feels like The Dark
Dragonborn, so give me a chance to save more of the members especially
considering the previous mod we have added.*

### [The Brotherhood of Old](https://www.nexusmods.com/skyrimspecialedition/mods/15322?tab=files)

**Main files** - The Brotherhood of Old - Version 1.1.1

### [Castle Volkihar Rebuilt](https://www.nexusmods.com/skyrimspecialedition/mods/324?tab=files)

**Main files** - SSE - Castle Volkihar Rebuilt

### [Immersive Fort Dawnguard](https://www.nexusmods.com/skyrimspecialedition/mods/40436?tab=files)

**Main files** - Immersive Fort Dawnguard

### [Serana Dialogue Edit](https://www.nexusmods.com/skyrimspecialedition/mods/16222?tab=files)

**Main files** - SeranaDialogEdit v 102

### [Serana Dialogue Add-On](https://www.nexusmods.com/skyrimspecialedition/mods/32161?tab=files)

**Main files** - Serana Dialogue Add-On SE

**Optional files** - SDA Serana Dialogue Edit Patch

### [Cannibal Draugr on Solstheim](https://www.nexusmods.com/skyrimspecialedition/mods/21238?tab=files)

**Main files** - Cannibal Draugr on Solstheim

### [Briraka's Draugr Overhaul - Cannibal Draugr Patch](https://www.nexusmods.com/skyrimspecialedition/mods/26188?tab=files)

**Optional files** - BriDO - Cannibal Draugr Patch

### [Blood Horker](https://www.nexusmods.com/skyrimspecialedition/mods/13938?tab=files)

**Main files** - Blood Horker

### [Grahl - The Ice Troll](https://www.nexusmods.com/skyrimspecialedition/mods/9311?tab=files)

**Main files** - Grahl - The Ice Troll - 4K

### [Solstheim Lighthouse](https://www.nexusmods.com/skyrimspecialedition/mods/14329?tab=files)

**Main files** - Solstheim Lighthouse v1.2 ESL

**Instructions** - rename the mod’s plugin to `SolstheimLighthouse.esp`.

### [Solstheim - Skaal Fishing Camp](https://www.nexusmods.com/skyrimspecialedition/mods/14450?tab=files)

**Main files** - Solstheim - Skaal Fishing Camp

### [Miraak - Dragonborn Follower](https://www.nexusmods.com/skyrimspecialedition/mods/19829?tab=files)

**Main files** - Miraak - Dragonborn Follower SE

*Just imagine this redemption arc. It would have been a shame if that was left out considering you have a choice to as always kill Miraak.*

### [Miraak Follower Dialogue Plus](https://www.nexusmods.com/skyrimspecialedition/mods/25566?tab=files)

**Main files** - Miraak Dialogue Plus

### [Miraak - Dragonborn Follower Dialogue Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/40330?tab=files)

**Main files** - Miraak - Dragonborn Follower SE (Dialogue Overhaul)

### [Miraak Husbando](https://www.nexusmods.com/skyrimspecialedition/mods/22063?tab=files)

**Main files** - Miraak Husbando SE

**Optional files** - Miraak Husbando SE High Poly Head No Outfit Edits

**Merge** - Merge both files.

*Well, he is one of the main villains of the game (and possibly the
follower), so he, like all others, deserves attention too. What is funny
is that he looks similar to my nord character preset, just
younger.*

### [Helgen Reborn](https://www.nexusmods.com/skyrimspecialedition/mods/5673?tab=files)

**Main files** - Helgen Reborn SSE Version 106 With bsa file

### [Landscape Fixes For Grass Mods - Helgen Reborn Patch](https://www.nexusmods.com/skyrimspecialedition/mods/9005?tab=files)

**Optional files** - Patch for Helgen Reborn

### [Moon and Star](https://www.nexusmods.com/skyrimspecialedition/mods/4301?tab=files)

**Main files** - Moon and Star

**Optional files** -Immersion Patch

### [Moon and Star - Cleaned Plugin Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/28530?tab=files)

**Main files** - MoonAndStar - Cleaned and USSEP Compatible

### [Moon and Star Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/27434?tab=files)

**Main files** - Moon and Star (MAS) Books Fix

**Main files** - Moon and Star (MAS) Landscapes Fixes

### [Landscape Fixes For Grass Mods - Moon and Star Patch](https://www.nexusmods.com/skyrimspecialedition/mods/9005?tab=files)

**Optional files** - Patch for Moon and Star

### [Moonpath to Elsweyr](https://www.nexusmods.com/skyrimspecialedition/mods/4341?tab=files)

**Main files** - Moonpath to Elsweyr SSE

### [Unofficial Moonpath to Elsweyr Patch](https://www.nexusmods.com/skyrimspecialedition/mods/15882?tab=files)

**Main files** - Unofficial Moonpath to Elsweyr Patch v1.5.0

### [Moonpath of Elsweyr - Music - Sky and Lightning Fix](https://www.nexusmods.com/skyrimspecialedition/mods/18683?tab=files)

**Main files** - Moonpath Music - Sky and Light fix - Merged 1.3

### [Beyond Skyrim - Bruma](https://www.nexusmods.com/skyrimspecialedition/mods/10917?tab=files)

**Main files** - Beyond Skyrim - Assets

**Main files** - Beyond Skyrim - Bruma

**Main files** - Beyond Skyrim DLC Integration Patch

### [Beyond Skyrim - Bruma Upscaled Textures](https://www.nexusmods.com/skyrimspecialedition/mods/34413?tab=files)

**Main files** - BSBUT_Armor_4x

**Main files** - BSBUT_Clothes_4x

**Main files** - BSBUT_Weapons_4x

**Merge** - merge all files.

### [Bruma - Better Forestgrassland Textures](https://www.nexusmods.com/skyrimspecialedition/mods/56492?tab=files)

**Main files** - 2048x2048

### [Beyond Skyrim - Bruma Tree LOD Billboards](https://www.nexusmods.com/skyrimspecialedition/mods/29386?tab=files)

**Main files** - Billboards for Beyond Skyrim Bruma

### [CleverCharff's Bruma](https://www.nexusmods.com/skyrimspecialedition/mods/41316?tab=files)

**Main files** - CleverCharff's Bruma 2K

### [Nordic Faces - Beyond Skyrim - Bruma Facegen](https://www.nexusmods.com/skyrimspecialedition/mods/40658?tab=files)

**Miscellaneous files** - FaceGen - Beyond Skyrim Bruma

### [Imperial City LOD for Beyond Skyrim - Bruma](https://www.nexusmods.com/skyrimspecialedition/mods/11010?tab=files)

**Main files** - Whitegoldtowerfix

### [Beyond Skyrim - Bruma Location Styled Crafting](https://www.nexusmods.com/skyrimspecialedition/mods/23089?tab=files)

**Main files** - Beyond Skyrim Bruma Craft Restrictions

### [Beyond Skyrim - Bruma - Enhanced Map Terrain for Quality World Map](https://www.nexusmods.com/skyrimspecialedition/mods/57176?tab=files)

**Main files** - Bruma LOD

### [Majestic Mountains - Bruma Patch](https://www.nexusmods.com/skyrimspecialedition/mods/59265?tab=files)

**Main files** - Bruma - MM Patch

### [Realistic Water Two - Bruma Patch](https://www.nexusmods.com/skyrimspecialedition/mods/35744?tab=files)

**Miscellaneous files** - Beyond Skyrim Bruma Patch v1.0

### [Bruma Signs - SMIM Patch](https://www.nexusmods.com/skyrimspecialedition/mods/10924?tab=files)

**Main files** - Bruma SE Signs SMIMed

### [Apothecary - Bruma Patch](https://www.nexusmods.com/skyrimspecialedition/mods/52130?tab=files)

**Miscellaneous files** - Apothecary - Bruma Patch

### [IDDP - Beyond Skyrim - Bruma Patch](https://www.nexusmods.com/skyrimspecialedition/mods/4126?tab=files)

**Optional files** - IDDP - Beyond Skyrim - Bruma Patch

**Delete** - remove `AHZBetterDGEntranceSE - BSHeartland
Patch.modgroups`.

### [Beyond Skyrim - Bruma - Gemling Queen Jewelry Patch](https://www.nexusmods.com/skyrimspecialedition/mods/35876?tab=files)

**Main files** - Beyond Skyrim - Bruma with Gemling Queen Jewelry

### [Beyond Skyrim - Bruma - Moonpath to Elsweyr Synergy Patch](https://www.nexusmods.com/skyrimspecialedition/mods/11069?tab=files)

**Main files** - Beyond Skyrim - Bruma Moonpath to Elsweyr Synergy Patch
v2.4.0

### [The Forgotten City](https://www.nexusmods.com/skyrimspecialedition/mods/1179?tab=files)

**Main files** - The Forgotten City

### [The Forgotten City Entrance](https://www.nexusmods.com/skyrimspecialedition/mods/25730?tab=files)

**Main files** - The Forgotten City Entrance

### [Bruma and Forgotten City Patch](https://www.nexusmods.com/skyrimspecialedition/mods/27573?tab=files)

**Main files** - Bruma and Forgotten City Patch

### [Darkend](https://www.nexusmods.com/skyrimspecialedition/mods/10423?tab=files)

**Main files** - DarkenD 1.4 SSE

**Update files** - FaceGenData 1.4 Meshes and Textures.

**Update files** - Missing walls hotfix.

**Merge** - merge all files.

**Hide** - hide `shinyglass_e2.dds` by right-clicking
the mod, then choosing the _Conflicts_ tab, selecting the file on the
_Winning file conflicts_ section, right-clicking on it and choosing
_Hide_.

### [Darkend Balance Patch](https://www.nexusmods.com/skyrimspecialedition/mods/29213?tab=files)

**Main files** - Darkend Balance Patch

### [Darkend - Enemy Rebalance](https://www.nexusmods.com/skyrimspecialedition/mods/57463?tab=files)

**Main files** - Darkend - Enemy Rebalance 1.6

### [Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/4155?tab=files)

**Main files** - Clockwork_SSE_v1-0

**Delete** - remove `Clockwork - Textures.bsa`.

### [Clockwork - Cleaned Textures](https://www.nexusmods.com/skyrimspecialedition/mods/55677?tab=files)

**Optional files** - Clockwork BSA

### [Skeleton Replacer HD - Clockwork Patch](https://www.nexusmods.com/skyrimspecialedition/mods/52845?tab=files)

**Miscellaneous files** - SkeletonReplacer - ClockworkPatch

### [Additional Clockwork](https://www.nexusmods.com/skyrimspecialedition/mods/47087?tab=files)

**Update files** - Additional Clockwork

**FOMOD** - `Second Person, Never Used on This Playthrough, Enable SKSE Modules, Bug Fixes, Superior Sorting, Extra Coal Mesh Fix`.

### [Clockwork Plantable Add-On](https://www.nexusmods.com/skyrimspecialedition/mods/40875?tab=files)

**Main files** - Clockwork Plantable Addon

### [Project AHO](https://www.nexusmods.com/skyrimspecialedition/mods/15996?tab=files)

**Main files** - Project AHO (EN)

**Optional files** - Project AHO ESM Flag Edition

**Merge** - Merge both files.

### [Unofficial Project AHO Bugfix and Improvement Patch](https://www.nexusmods.com/skyrimspecialedition/mods/41751?tab=files)

**Main files** - Project AHO Bugfix and Improvement Patch

**Update files** - Table Mesh Fix

**Merge** - Merge both files.

### [Project AHO - Start When You Want](https://www.nexusmods.com/skyrimspecialedition/mods/21386?tab=files)

**Optional files** - Project AHOPatch SE - ESL Flagged File

### [Project AHO - ENB Patch](https://www.nexusmods.com/skyrimspecialedition/mods/36199?tab=files)

**Main files** - Project AHO ENB Patch v0.1

### [Project AHO - Mysticism - A Magic Overhaul Spell Crafting Patch](https://www.nexusmods.com/skyrimspecialedition/mods/16564?tab=files)

**Optional files** - Project AHO - Mysticism - A Magic Overhaul Spell
Crafting Patch

### [The Gray Cowl of Nocturnal](https://www.nexusmods.com/skyrimspecialedition/mods/4509?tab=files)

**Main files** - The Gray Cowl of Nocturnal

### [The Gray Cowl of Nocturnal - HD Pack](https://www.nexusmods.com/skyrimspecialedition/mods/7644?tab=files)

**Main files** - The Grey Cowl of Nocturnal SE - HD Texture pack

### [The Gray Cowl of Nocturnal - Alikr Flora Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/10141?tab=files)

**Main files** - Gray Cowl of Nocturnal - Alikr Flora Overhaul

**Optional files** - Gray Fox Flora Overhaul Tree Billboard LODGEN Kit

**Instructions** - Download the optional file manually and drop it into
your *MO2 Downloads* folder, the file will appear in your *Downloads*
tab in MO2, right click on it and select *Query Info*, then merge the
file with the main one.

### [The Gray Cowl of Nocturnal - Add-Ons and Patches](https://www.nexusmods.com/skyrimspecialedition/mods/19724?tab=files)

**Main files** - The Gray Cowl of Nocturnal SE - Addons and Patches 1.3

**FOMOD** - `Unofficial Skyrim Special Edition Patch, Delayed Start
Patch, Weapons Armor Clothing and Clutter Fixes Patch`.

### [The Gray Cowl of Nocturnal Combo](https://www.nexusmods.com/skyrimspecialedition/mods/17831?tab=files)

**Main files** - Gray Cowl of Nocturnal Combo Mod

### [The Tools of Kagrenac](https://www.nexusmods.com/skyrimspecialedition/mods/14168?tab=files)

**Main files** - The Tools of Kagrenac V1.59 SSE

### [Carved Brink](https://www.nexusmods.com/skyrimspecialedition/mods/24351?tab=files)

**Main files** - Carved Brink (EN)

**Optional files** - Carved Brink ESM Flag Edition

**Merge** - Merge both files.

### [Unofficial Carved Brink Patch](https://www.nexusmods.com/skyrimspecialedition/mods/36916?tab=files)

**Main files** - Unofficial Carved Brink Patch

### [Carved Brink Generic Assets Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/25791?tab=files)

**Main files** - Carved Brink Generic Assets Replacer (Stranger Mask and
Corrupted Shade) ESL

### [Wyrmstooth](https://www.nexusmods.com/skyrimspecialedition/mods/45565?tab=files)

**Main files** - Wyrmstooth

### [Wyrmstooth - Settings Loader](https://www.nexusmods.com/skyrimspecialedition/mods/56504?tab=files)

**Main files** - Wyrmstooth - Settings Loader

### [Wyrmstooth Upscaled Textures](https://www.nexusmods.com/skyrimspecialedition/mods/39992?tab=files)

**Main files** - Wyrmstooth_2x

### [Better Wyrmstooth Map With Roads](https://www.nexusmods.com/skyrimspecialedition/mods/39501?tab=files)

**Optional files** - Only Wyrmstooth Map

### [Lanterns Of Wyrmstooth](https://www.nexusmods.com/skyrimspecialedition/mods/47782?tab=files)

**Main files** - Lanterns Of Wyrmstooth

**Instructions** - Install the mod, double click on *Lanterns of
Wyrmstooth 1.00*, then right-click *Data* folder and select *Set as data
directory*, click *OK*.

### [Realistic Water Two - Wyrmstooth Patch](https://www.nexusmods.com/skyrimspecialedition/mods/35744)

**Miscellaneous files** - Wyrmstooth Patch v1.0

### [Forceful Tongue - Wyrmstooth Patch](https://www.nexusmods.com/skyrimspecialedition/mods/36276?tab=files)

**Miscellaneous files** - Forceful Tongue - Wyrmstooth Patch

### [Apothecary - Wyrmstooth Patch](https://www.nexusmods.com/skyrimspecialedition/mods/52130?tab=files)

**Miscellaneous files** - Apothecary - Wyrmstooth Patch

### [Dragon War - Wyrmstooth Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51310?tab=files)

**Miscellaneous files** - Dragon War - Wyrmstooth Patch

### [The Grand Paladin - 2021](https://www.nexusmods.com/skyrimspecialedition/mods/46867?tab=files)

**Main files** - The Grand Paladin - 2021

### [The Final Cataclysm - 2020](https://www.nexusmods.com/skyrimspecialedition/mods/33167?tab=files)

**Main files** - The Final Cataclysm - MMXX

**Optional files** - The Final Cataclysm - MMXX (Update)

**Merge** - Merge both files.

### [Artifacts - The Tournament of the Ten Bloods](https://www.nexusmods.com/skyrimspecialedition/mods/15264?tab=files)

**Main files** - Tournament of the Ten Bloods 2.1

**FOMOD** - `2K Resolution, No Flame Effect`.

**Update files** - HOTFIX - Sounds

**Merge** - Merge both files.

### [Artifacts - The Ice Blade of the Monarch](https://www.nexusmods.com/skyrimspecialedition/mods/13972?tab=files)

**Main files** - Ice Blade of the Monarch 2.6

**FOMOD** - `2K Resolution, No trail Mist`.

### [FaceGen Output for Different Mods](https://www.nexusmods.com/skyrimspecialedition/mods/24174?tab=files)

**Optional files** - FaceGen Output for Random Mods

### [The Wheels of Lull](https://www.nexusmods.com/skyrimspecialedition/mods/748?tab=files)

**Main files** - The Wheels of Lull SE

**FOMOD** - `High Poly NPCs`.

### [INIGO](https://www.nexusmods.com/skyrimspecialedition/mods/1461?tab=files)

**Main files** - INIGO_V2.4C SE

### [Inigo Whistle Key](https://www.nexusmods.com/skyrimspecialedition/mods/29406?tab=files)

**Main files** - InigoWhistleKeyV12

### [Mr. Dragonfly ENB Particle Light](https://www.nexusmods.com/skyrimspecialedition/mods/45664?tab=files)

**Main files** - Mr. Dragonfly ENB Particle Lights

**FOMOD** - `Teal (My preference)`.

### [The Phoenix Flavour - Inigo Patch](https://www.nexusmods.com/skyrimspecialedition/mods/14223?tab=files)

**Optional files** - The Phoenix Flavour - Inigo Patch

### [High-Poly Inigo Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/38860?tab=files)

**Main files** - High-Poly Inigo Replacer - FOMOD installer

**FOMOD** - `Custom Saeri Hair - Blue`.

### [Lucien - Immersive Fully Voiced Male Follower](https://www.nexusmods.com/skyrimspecialedition/mods/20035?tab=files)

**Main files** - Lucien

**Optional files** - Lucien - Moon and Star Patch

**Optional files** - Lucien - Moonpath to Elsweyr Patch

### [Lucien Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/38116?tab=files)

**Main files** - ---Lucien Replacer SE Younger Face version

### [Kaidan 2](https://www.nexusmods.com/skyrimspecialedition/mods/19075?tab=files)

**Main files** - Kaidan 2.1.1

### [Kaidan 2 Follower Voice Fixes and Additional Dialogue](https://www.nexusmods.com/skyrimspecialedition/mods/59349?tab=files)

**Main files** - Kaidan 2 Voice Fixes and Additional Dialogue 1.3

### [Pandorable's Kaidan](https://www.nexusmods.com/skyrimspecialedition/mods/23738?tab=files)

**Main files** - Pandorable's Kaidan SE

### [Gladys the Corgi - A Custom Dog Follower Mod](https://www.nexusmods.com/skyrimspecialedition/mods/50164?tab=files)

**Main files** - Gladys the Corgi

### [Merlin the Corgi - A Magical Dog Follower Mod](https://www.nexusmods.com/skyrimspecialedition/mods/56433?tab=files)

**Main files** - Merlin the Corgi

### [Shirley - A Skyrim Follower Mod](https://www.nexusmods.com/skyrimspecialedition/mods/45956?tab=files)

**Main files** - Shirley - A Skyrim Follower Mod

### [Older Shirley](https://www.nexusmods.com/skyrimspecialedition/mods/49348?tab=files)

**Main files** - Older Shirley - Default Hair

### [Song of the Green](https://www.nexusmods.com/skyrimspecialedition/mods/11278?tab=files)

**Main files** - Song of the Green 1.3

### [Refined Auri - Song of the Green](https://www.nexusmods.com/skyrimspecialedition/mods/36444?tab=files)

**Main files** - Refined Auri SSE - Pointy Teeth Update

**FOMOD** - `Vanilla or UNP, Sharp Teeth, Freckles (default)`.

### [The Sinister Seven](https://www.nexusmods.com/skyrimspecialedition/mods/19178?tab=files)

**Main files** - The Sinister Seven SSE 1.2

**Hide** - hide `quickskydark_e.dds`.

### [Apachii Divine Elegance Store](https://www.nexusmods.com/skyrimspecialedition/mods/9213?tab=files)

**Main files** - Apachii_Divine_Elegance_SSE_v\_1_9

**Optional files** - ApachiiDivineEleganceStore_USSEP_Patch_new

**Optional files** -
ApachiiDivineElegance_SSE\_\_Fix_AlphaRougeMale_v\_1_9

**Optional files** - Apachii_DE_SSE_Khajiit_Fix

**Optional files** - Apachii_DE_SSE_MaleOutfit_Meshes_Fixes

**Miscellaneous files** - Apachii_Divine_Elegance_SSE_UNP_meshes_Full_v_3

*I have added this to serve a resource for making different screenshots. Of
course, you can also use all those outfits etc. to make your character
just prettier. There are things for everyone to play with, even
warriors.*

### [Rayek's End](https://www.nexusmods.com/skyrimspecialedition/mods/8285?tab=files)

**Main files** - Rayek's End - SSE Expanded Edition 1.7 - Original (Dark)

**Optional files** - Barenziah's Glory SE - Patch (Removes floating
gems)

### [Rayek's End - Hearthfire Multiple Adoptions Support](https://www.nexusmods.com/skyrimspecialedition/mods/36877?tab=files)

**Main files** - Rayek's End Multiple Hearhfire Adoptions Support

### [The Scrivener's Croft](https://www.nexusmods.com/skyrimspecialedition/mods/44701?tab=files)

**Main files** - The Scrivener's Croft

### [Ruska - Riften Player Home](https://www.nexusmods.com/skyrimspecialedition/mods/16177?tab=files)

**Main files** - Ruska SE

### [Knight's Rest](https://www.nexusmods.com/skyrimspecialedition/mods/19793?tab=files)

**Main files** - Knight's Rest

### [Hermit Mountain Cottage](https://www.nexusmods.com/skyrimspecialedition/mods/4093?tab=files)

**Main files** - Hermit Mountain Cottage SE V6.0a

### [Wind Path](https://www.nexusmods.com/skyrimspecialedition/mods/15192?tab=files)

**Main files** - Wind Path SSE 1.3.1

### [Morskom Estate](https://www.nexusmods.com/skyrimspecialedition/mods/33408?tab=files)

**Main files** - Morskom Estate 1.2

### [Red Rose Mill](https://www.nexusmods.com/skyrimspecialedition/mods/47117?tab=files)

**Optional files** - Red Rose Mill

### [Wuth Rein](https://www.nexusmods.com/skyrimspecialedition/mods/52995?tab=files)

**Main files** - Wuth Rein

### [Frostwood Cabin](https://www.nexusmods.com/skyrimspecialedition/mods/52183?tab=files)

**Optional files** - Frostwood Cabin ESL version

### [Viking's Longhouse](https://www.nexusmods.com/skyrimspecialedition/mods/10860?tab=files)

**Main files** - Viking's Longhouse SSE

### [Interesting NPCs (3DNPC)](https://www.nexusmods.com/skyrimspecialedition/mods/29194?tab=files)

**Main files** - Interesting NPCs SE - BSAs

**Update files** - Interesting NPCs SE - 4.3.6 to 4.4 Hotfix

**Miscellaneous files** - Interesting NPCs SE - AI Overhaul SSE Patch

### [Interesting Follower Requirements for Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/45646?tab=files)

**Optional files** - Interesting Follower Requirements for 3DNPC (Soft Requirements)

### [Nordic Faces - Interesting NPCs Facegen](https://www.nexusmods.com/skyrimspecialedition/mods/40658?tab=files)

**Miscellaneous files** - FaceGen - Interesting NPCs

### [3DNPC - Art and Sacrifice Aggression Bug Fix](https://www.nexusmods.com/skyrimspecialedition/mods/45496?tab=files)

**Main files** - 3DNPC Art and Sacrifice Script Fix

### [Interesting NPCs and WACCF Outfits Patch](https://www.nexusmods.com/skyrimspecialedition/mods/31858?tab=files)

**Main files** - Interesting NPCs and WACCF Outfits Patch

### [Interesting NPCs - Zora Fair-Child Voice Enhanced](https://www.nexusmods.com/skyrimspecialedition/mods/27448?tab=files)

**Main files** - Zora VO

### [Cuyima Interesting NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/27330?tab=files)

**Main files** - Cuyima Interesting NPCs SE - Custom Hair

### [Interesting NPCs Visual Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/40046?tab=files)

**Main files** - Interesting NPCs Visual Overhaul

### [Undeath Remastered](https://www.nexusmods.com/skyrimspecialedition/mods/6180?tab=files)

**Main files** - Skyrim - Undeath SSE 1.7

### [Undeath - Classical Lichdom](https://www.nexusmods.com/skyrimspecialedition/mods/40802?tab=files)

**Main files** - Undeath Classical Lichdom

**Optional files** - Hishy's Undeath Cleaner Script Improved

**Instructions** - Unfortunately, *Undeath Remastered* should be cleaned
in xEdit to make it run correctly with other mods. Extract contents of
the optional file into your xEdit’s *Edit Scripts* folder. Open xEdit
using MO2, find *Undeath.esp*, right click on it and choose *Apply
Script…* In category *Script* find *Hishy_UndeathCleaner* and choose it.
Press *OK*. After xEdit finishes cleaning, don’t forget to make sure that
changes are saved.

### [Skeleton Replacer HD - Undeath Patch](https://www.nexusmods.com/skyrimspecialedition/mods/52845?tab=files)

**Miscellaneous files** - SkeletonReplacer - UndeathPatch

**FOMOD** - `Undeath, Version2EnbLight, 2K`.

### [Moon and Star - Undeath Remastered Patch](https://www.nexusmods.com/skyrimspecialedition/mods/19068?tab=files)

**Main files** - Moon and Star - Undeath Remastered Patch

### [Hammet's Dungeon Packs](https://www.nexusmods.com/skyrimspecialedition/mods/12186?tab=files)

**Main Files** - Hammet Dungeon Packs - ESM version

### [Hammet's Dungeons - Misc Patches](https://www.nexusmods.com/skyrimspecialedition/mods/54453/?tab=files)

**Main files** - Vuldur ESM - Skybox Patch

**Main files** - Vuldur ESM - ToK Patch

### [EasierRider's Dungeon Pack](https://www.nexusmods.com/skyrimspecialedition/mods/2218?tab=files)

**Main files** - EasierRider's Dunegon Pack SSE v1.5

### [Janquel's Arguably Needed Quixotically Unifying ESP Library](https://www.nexusmods.com/skyrimspecialedition/mods/57365/?tab=files)

**Main files** - Janquel's Arguably Needed Quixotically Unifying ESP Library

**FOMOD** - `3DNPC - Moon and Star, Kaidan 2 Wedding, Hammet's - 3DNPC, Hammet's - Lucien, Obscure's College - 3DNPC, Project AHO - 3DNPC, Project AHO - EasierRider's`.

---

## Exteriors

Phoenix is definitely the master at choosing and mixing different landscape elements to make it as beautiful as we can experience in TPF, 
but a few gems added in this will definitely make our surroundings even more breath-taking.  

Create a separator and name it `EXTERIORS` and place it
directly below the *TREES & PLANTS* separator (and its mods). Change its
colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

### [Lanterns of Skyrim II - Insects Patch](https://www.nexusmods.com/skyrimspecialedition/mods/50670)

**Main files** - Lanterns of Skyrim II Insects Patch (v1.1 esm)

_I understand that bugs like light, but that means they should sometimes get away from all the lanterns to fly to different source of light._

### [Happy Little Trees](https://www.nexusmods.com/skyrimspecialedition/mods/50961)

**Main files** - Happy Little Trees

**FOMOD** - `All Trees`.

_These ones make me happy too._

### [Happy Little Trees Add-On - DynDOLOD](https://www.nexusmods.com/skyrimspecialedition/mods/56907)

**Main files** - Happy Little Trees 3D LOD - Quality

### [Happy Little Trees - Better Dynamic Ash Patch](https://www.nexusmods.com/skyrimspecialedition/mods/58700)

**Main files** - Happy Little Trees - Better Dynamic Ash Patch

### [Official Unique Flowers and Plants](https://www.nexusmods.com/skyrimspecialedition/mods/29154)

**Optional files** - Unique Flowers and Plants for Skyrim SE DLC
Compatible ESM Version

*Adds different beautiful hand-placed flowers and plants around Skyrim
to make it more interesting and picturesque. ESM plugin allows us not to
worry about the mod overwriting anything we don't want to.*

### [Cathedral - 3D Mountain Flowers](https://www.nexusmods.com/skyrimspecialedition/mods/41312)

**Main files** - Cathedral - 3D Mountain Flowers

*Who would even like to look at vanilla mountain flowers, if we have
these.*

### [A Patch for Skyrim Landscape and Water Fixes and Cathedral Mountain Flowers](https://www.nexusmods.com/skyrimspecialedition/mods/50265)

**Main files** - A Patch for Skyrim Landscape and Water Fixes and
Cathedral Mountain Flowers

**Optional files** - A Patch for Lanterns of Skyrim II and Cathedral
Mountain Flowers

### [Butterflies Land True](https://www.nexusmods.com/skyrimspecialedition/mods/29434)

**Optional files** - Butterflies Land True - ESPFE Alternate Version

*At first, I didn't want to waste any resources (even if there is nothing too much needed) on anything like this and the next mod, but after seeing a butterfly somehow sitting in the air, while it was supposed to be sitting on a cabbage, I have changed by mind.*

### [Butterflies Unchained](https://www.nexusmods.com/skyrimspecialedition/mods/29538)

**Main files** - Butterflies Unchained (ESL Version)

### [The Great Cities - Minor Cities and Towns](https://www.nexusmods.com/skyrimspecialedition/mods/20272)

**Main files** - The Great Cities - Resources

**Main files** - The Great Cities 2.01

**Old files** - The Great Cities - CFTO Patch

_I have always felt that all minor cities and towns look pretty much the same. Considering all these places have their own stories and tales to tell, that isn't right at all, so we just have to change that._

### [Landscape Fixes For Grass Mods - The Great Cities - Minor Cities and Towns Patch](https://www.nexusmods.com/skyrimspecialedition/mods/9005)

**Optional files** - Patches for The Great Cities and Towns

**FOMOD** - `The Great Cities All In One`.

### [Cities of the North - Morthal](https://www.nexusmods.com/skyrimspecialedition/mods/34168)

**Main files** - Cities of the North - Morthal

**Optional files** - Skyrim 3D Signs Patch

### [Cities of the North - Morthal Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/34228)

**Main files** - COTN Morthal Patch Collection

**FOMOD** - `The Great Cities, Finding Helgi and Laelette, Interesting NPCs, AI Overhaul, Book Covers Skyrim, Clockwork, Immersive Patrols II, Kaidan 2, Landscape and Water Fixes,
Lanterns of Skyrim II`.

### [Cities of the North - Dawnstar](https://www.nexusmods.com/skyrimspecialedition/mods/28952)

**Main files** - Cities of the North - Dawnstar

**Update files** - UPDATE 1.2.1

**Merge** - Merge both files.

### [Cities of the North - Dawnstar Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/30885)

**Main files** - COTN Dawnstar Patch Collection

**FOMOD** - `The Great Cities - Minor Cities and Towns, AI Overhaul, Cathedral 3D Flowers, Clockwork, Helgen Reborn, Interesting NPCs, Morskom Estate, Lanterns of Skyrim II`.

### [Cities of the North - Winterhold](https://www.nexusmods.com/skyrimspecialedition/mods/40088)

**Main files** - Cities of the North - Winterhold

**Optional files** - Skyrim 3D Signs Patch

### [Cities of the North - Winterhold Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/40181)

**Main files** - COTN Winterhold Patch Collection

**FOMOD** - `3DNPC - Interesting NPCs, AI Overhaul, Cathedral 3D Flowers, Embers HD, The Great Cities - Minor Cities and Towns`, for Landscape and Water Fixes and Lanterns of Skyrim II - `Non-JK`.

### [Winterhold Keep Tweaks for COTN](https://www.nexusmods.com/skyrimspecialedition/mods/52371)

**Main files** - Winterhold Keep Tweaks for COTN

### [Cities of the North - Falkreath](https://www.nexusmods.com/skyrimspecialedition/mods/56731)

**Main files** - Cities of the North - Falkreath

### [Cities of the North - Falkreath Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/56734)

**Main files** - Cities of the North - Falkreath Patch Collection

**FOMOD** - `The Great Cities - Minor Cities and Towns, TGC - Helgen Reborn, TGC - Clockwork, Lanterns of Skyrim II, TGC - LAWF, 3DNPC, AI Overhaul, Bring Meeko to Lod, Immersive Patrols II, Lucien, Skyrim 3D Signs`, **untick** `Janquel's Addons, Landscape and Grass Fixes`.

### [The Great Town of Karthwasten](https://www.nexusmods.com/skyrimspecialedition/mods/33032)

**Main files** - The Great Town of Karthwasten 1.2

### [The Great Town of Karthwasten Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/37471)

**Main files** - The Great Town of Karthwasten Patch Collection

**FOMOD** - `3DNPC, AI Overhaul SSE, Landscape and Water Fixes, Lanterns of Skyrim II, USSEP`.

### [The Great Village of Old Hroldan](https://www.nexusmods.com/skyrimspecialedition/mods/33189)

**Main files** - The Great Village of Old Hroldan 1.03

### [The Great Village of Old Hroldan Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/37650)

**Main files** - The Great Village of Old Hroldan Patch Collection

**FOMOD** - `3DNPC, AI Overhaul, Landscape and Water Fixes, Lanterns of Skyrim II, USSEP`.

### [The Great Town of Ivarstead](https://www.nexusmods.com/skyrimspecialedition/mods/34505)

**Main files** - The Great Town of Ivarstead SSE 1.2

### [The Great Town of Ivarstead Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/36380)

**Main files** - Great Town of Ivastead Patch Collection

**FOMOD** - `3DNPC, AI Overhaul, Embers HD, Landscape and Water Fixes, Landscape Grass Fix, Realistic Water Two, USSEP, Lanterns of Skyrim II`, Kaidan 2 - `Non-JK`.

### [The Great Town of Shor's Stone](https://www.nexusmods.com/skyrimspecialedition/mods/35977)

**Main files** - The Great Town of Shor's Stone 1.04

### [The Great Town of Shor's Stone Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/36462)

**Main files** - Great Town of Shor's Stone Patch Collection

**FOMOD** - `AI Overhaul, Embers HD, Lanterns of Skyrim II, USSEP`.

### [The Great Village of Mixwater Mill](https://www.nexusmods.com/skyrimspecialedition/mods/36350)

**Main files** - The Great Village of Mixwater Mill 1.1

**Optional files** - 3DNPC-TGCoMM Patch by WiZkiD

### [The Great Village of Mixwater Mill Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/37414)

**Main files** - The Great Village of Mixwater Mill Patch Collection

**FOMOD** - `Landscape and Water Fixes, Lanterns of Skyrim II, USSEP`.

### [The Great Village of Kynesgrove](https://www.nexusmods.com/skyrimspecialedition/mods/42639)

**Main files** - The Great Village of Kynesgrove 1.1

### [The Great Village of Kynesgrove Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/42957)

**Main files** - The Great Village of Kynesgrove Patch Collection

**FOMOD** - `Interesting NPCs - 3DNPC, AI Overhaul, Inigo, Landscape and Water Fixes, Lanterns of Skyrim II, USSEP`.

### [Bent Pines](https://www.nexusmods.com/skyrimspecialedition/mods/8306)

**Main files** - Bent Pines II

**Optional files** - Navmesh .esp by CakeofHonor

**Merge** - merge both files.

*Even though all this mod does is just adding some trees, you won't just go away from them without looking closer and maybe taking some screenshots on the way.*

### [Rorikstead Basalt Cliffs](https://www.nexusmods.com/skyrimspecialedition/mods/25718)

**Main files** - Rorikstead Basalt Cliffs

*By adding some unique things to regions of Skyrim like this one, we can definitely achieve our goal of making Skyrim a majestic land it is supposed to be.*

### [Little Touches - A tree Placement for Whiterun City](https://www.nexusmods.com/skyrimspecialedition/mods/54411)

**Optional files** - AIO-LT- A Tree Placement for Whiterun City

*Without Whiterun, Skyrim woudn't have been the same game, so let's give Whiterun some love it deserves.*

### [Little Touches - Stairway to The Wind District](https://www.nexusmods.com/skyrimspecialedition/mods/54936)

**Main files** - LT-Stairway_to_The_Wind_District_Fixed

---

## Interiors

Just our grand continuation of overhauling, but for interiors. This is meant more for major cities, which are already unique by themselves, to make their inns and shops feel even more like the cities these places are in. For that we will mainly use JK's interior mods as they blend pretty well and don't feel too much for the corresponding place (with some exceptions, which aren't used by the add-on).  

Create a separator and name it `INTERIORS EXTENDED` and place it
directly below the *INTERIORS* separator (and its mods). Change its
colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

### [JK's Arcadia's Cauldron](https://www.nexusmods.com/skyrimspecialedition/mods/33565)

**Main files** - JK's Arcadia's Cauldron

### [JK's Belethor's General Goods](https://www.nexusmods.com/skyrimspecialedition/mods/33636)

**Main files** - JK's Belethor's General Goods

### [JK's The Bannered Mare](https://www.nexusmods.com/skyrimspecialedition/mods/33845)

**Main files** - JK's The Bannered Mare

### [JK's Dragonsreach](https://www.nexusmods.com/skyrimspecialedition/mods/34000)

**Main files** - JK's Dragonsreach

### [JK's Sleeping Giant Inn](https://www.nexusmods.com/skyrimspecialedition/mods/35806)

**Main files** - JK's Sleeping Giant Inn

### [JK's The Winking Skeever](https://www.nexusmods.com/skyrimspecialedition/mods/43991)

**Main files** - JK's The Winking Skeever

### [JK's Bits and Pieces](https://www.nexusmods.com/skyrimspecialedition/mods/44642)

**Main files** - JK's Bits and Pieces

### [JK's Radiant Raiment](https://www.nexusmods.com/skyrimspecialedition/mods/44858)

**Main files** - JK's Radiant Raiment

### [JK's Blue Palace](https://www.nexusmods.com/skyrimspecialedition/mods/45324)

**Main files** - JK's Blue Palace

### [JK's Candlehearth Hall](https://www.nexusmods.com/skyrimspecialedition/mods/45617)

**Main files** - JK's Candlehearth Hall

### [JK's White Phial](https://www.nexusmods.com/skyrimspecialedition/mods/47713)

**Main files** - JK's White Phial

### [JK's Sadris Used Wares](https://www.nexusmods.com/skyrimspecialedition/mods/47942)

**Main files** - JK's Sadris Used Wares

### [JK's New Gnisis Cornerclub](https://www.nexusmods.com/skyrimspecialedition/mods/48293)

**Main files** - JK's New Gnisis Cornerclub

### [JK's Palace of the Kings](https://www.nexusmods.com/skyrimspecialedition/mods/48902)

**Main files** - JK's Palace of the Kings

### [JK's The Bee and Barb](https://www.nexusmods.com/skyrimspecialedition/mods/49516)

**Main files** - JK's The Bee and Barb

### [JK's Elgrims Elixirs](https://www.nexusmods.com/skyrimspecialedition/mods/49934)

**Main files** - JK's Elgrims Elixirs

### [JK's The Pawned Prawn](https://www.nexusmods.com/skyrimspecialedition/mods/50135)

**Main files** - JK's The Pawned Prawn

### [JK's The Ragged Flagon](https://www.nexusmods.com/skyrimspecialedition/mods/50765?tab=files)

**Main files** - JK's The Ragged Flagon

### [JK's Mistveil Keep](https://www.nexusmods.com/skyrimspecialedition/mods/52462)

**Main files** - JK's Mistveil Keep

### [JK's The Temple of Mara](https://www.nexusmods.com/skyrimspecialedition/mods/52724)

**Main files** - JK's The Temple of Mara

### [JK's Silver-Blood Inn](https://www.nexusmods.com/skyrimspecialedition/mods/53554)

**Main files** - JK's Silver-Blood Inn

### [JK's Arnleif and Sons Trading Company](https://www.nexusmods.com/skyrimspecialedition/mods/54166)

**Main files** - JK's Arnleif and Sons Trading Company

### [JK's Understone Keep](https://www.nexusmods.com/skyrimspecialedition/mods/55571)

**Main files** - JK's Understone Keep

### [JK's Riverwood Trader](https://www.nexusmods.com/skyrimspecialedition/mods/55959)

**Main files** - JK's Riverwood Trader

### [JK's Temple of Dibella](https://www.nexusmods.com/skyrimspecialedition/mods/56371)

**Main files** - JK's Temple of Dibella

### [JK's Temple of Kynareth](https://www.nexusmods.com/skyrimspecialedition/mods/56737)

**Main files** - JK's Temple of Kynareth

### [JK's Temple of the Divines](https://www.nexusmods.com/skyrimspecialedition/mods/57304)

**Main files** - JK's Temple of the Divines

### [JK's Temple of Talos](https://www.nexusmods.com/skyrimspecialedition/mods/56971)

**Main files** - JK's Temple of Talos

### [JK's Interiors Patch Collection](https://www.nexusmods.com/skyrimspecialedition/mods/35910)

**Old files (v. 3.24.1.)** - JKs Interiors Patch Collection

**FOMOD** - In 1st page - `I'VE READ AND UNDERSTAND`, in the 2nd page check everything except _JK's Angeline's Aromatics, JK's The Drunken Huntsman, JK's The Hag's Cure, JK's Warmaiden's_, in JK's Arcadia's Cauldron's page - `AI Overhaul, EasierRider's Dungeon Pack, USSEP`, JK's Arnleif and Sons Trading Company - `AI Overhaul`, JK's Bee and Barb - `3DNPC, AI Overhaul, Helgen Reborn, Elgrim's Elixirs - The Brotherhood of Old`, JK's Belethor's General Goods - `AI Overhaul`, JK's Bits and Pieces - `AI Overhaul, USSEP`, JK's Blue Palace - `AI Overhaul, Lanterns of Skyrim II, USSEP`, **untick** only `Royal Armory` patch, `USSEP, 3DNPC`, JK's Candlehearth Hall - `AI Overhaul, Helgen Reborn, 3DNPC`, JK's Dragonsreach - `AI Overhaul`, JK's Elgrims Elixirs - `Bee and Barb - Brotherhood of Old`, JK's Mistveil Keep - `3DNPC, AI Overhaul`, JK's New Gnisis Cornerclub - `3DNPC`, JK's Palace of the Kings - `EasierRider's Dungeon Packs, USSEP`, `None` for armor replacer for guards, JK's Radiant Raiment - `3DNPC, USSEP`, JK's Ragged Flagon - `AI Overhaul, Opulent Thieves Guild, USSEP`, JK's Sadri's Used Wares - `3DNPC, ACE`, JK's Silver-Blood Inn - `3DNPC, AI Overhaul, The Brotherhood of Old`, JK's Sleeping Giant Inn - `3DNPC, AI Overhaul`, JK's Temple of Dibella - `ACE, Relightning Skyrim, AI Overhaul`, JK's Temple of the Divines - `3DNPC, USSEP`, JK's Temple of Mara - `3DNPC, AI Overhaul, The Brotherhood of Old`, JK's Temple of Kynareth - `3DNPC, Easierrider's Dungeon Pack`, JK's Temple of Talos - `3DNPC, AI Ovehraul, ACE, USSEP`, JK's Understone Keep - `3DNPC, AI Overhaul, USSEP`, JK's Winking Skeever - `AI Overhaul, The Brotherhood of Old, USSEP, 3DNPC, Undeath`.

---

## Apparel & Weapons

Nothing much as you will get plenty of goodies from new and old quests -
just some new weapons to our favourite NPCs to show their status and
power and different looking variants of gear for player character.

Create a separator and name it `APPAREL & WEAPONS EXTENDED` and place it
directly below the *APPAREL & WEAPONS* separator (and its mods). Change
its colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

You will need to make an account on another modding website (yes, there
isn’t just *Nexus*, but not many other services are as reliable) called
[VectorPlexus](https://vectorplexus.com/), because three mods,
which we need for completion of the add-on, are available only from
there. Be warned that much content there is NSFW related, so if you
don’t want to see that, just make an account and follow my instructions.

While you are logged in and when you will open a link to the website
from here, there will be a button *Download this file*. If mod has
different versions, there will be instructions on which one to get like
always.

### [Royal Armory - New Artifacts](https://www.nexusmods.com/skyrimspecialedition/mods/6994)

**Main files** - Royal Armory V2.2

### [PrivateEye’s Royal Armory - Reforged](https://www.nexusmods.com/skyrimspecialedition/mods/28006)

**Main files** - Royal Armory - Reforged - Main Replacer 1.2

**Optional files** - Dragonfang - Penitus Logo

**Optional files** - Hafyllbrand - Custom Textures

**Optional files** - Sword of Dragonsreach - Custom Textures

**Merge** - Merge all files.

### [Royal Armory - New Artifacts Plugin Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/44392)

**Main files** - Royal Armory - Replacer

**FOMOD** - `Obscure’s College of Winterhold - Cell Setting Patch`.

### [Elemental Staffs](https://www.nexusmods.com/skyrimspecialedition/mods/5319)

**Main files** - Elemental Staffs SE

**Optional files** - Elemental Staffs SE Basic

**Merge** - Merge both files.

*Alters the appearance of almost all staffs to appear more like they are
imbued with the power of magic we are actually using them for.*

### [Heavy Armored Pants](https://vectorplexus.com/files/file/404-heavy-armored-pants/)

*You will be able to get these in exchange for their counterparts (heavy
armors) in Skyrim. Just use any forge for that. Tempered the same way as
any other armor, pants have the same stats as their counterparts.*

<p align="center">
    <img width="60%" src="https://user-images.githubusercontent.com/37147270/142895597-906da9b3-1ae2-4d42-9845-9276b6e08122.png" /> 
</p>

_(ft. 1.11. v. of TPF - Dragon's Edition's new content, exteriors, appearance and animation mods, ENB)_

--- 

## Appearance

Overall, I am happy with TPF’s appearance section, but the humanoid
player character’s skin texture choice is not as good as it doesn’t give
you many choices for experimenting (or maybe I just prefer other ones,
no idea), so I am changing that with different textures, by using which
everyone is probably going to find his or her favourite combinations to
play with. Other changes are there to diversify different races of
Skyrim’s population and make character creation a little bit more
interesting and even more time-consuming.

Create a separator and name it `APPEARANCE EXTENDED` and place it
directly below the *APPEARANCE* separator (and its mods).
Change its colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

### [Racial Body Morphs](https://www.nexusmods.com/skyrimspecialedition/mods/20684)

**Main files** - Racial Body Morphs 2.1

*Now you will find out why we needed that First
Person Camera Height Fix. All races from this point will have their own
unique height and form, so wish some luck to Wood Elves at getting any
attention from HIGH Elves. And now you will think twice before touching
that big orc. Really lore-immersive mod.*

### [Tempered Skins for Males](https://www.nexusmods.com/skyrimspecialedition/mods/7902)

**Main files** - Tempered Skins for Males - Dressed Version

**FOMOD** - `A2 and F none`, for other things you can choose whichever
options you like. `My recommendations - B3 (people are living in Skyrim,
not Elsweyr), C3, D2, E1 (with this combination they don’t look too old
and at the same time not as teenagers)`.

*I guess Tempered Skins is my favourite mod series, when it comes to
appearance, as each of the skins for both males and females is so
customizable you won’t need any other mod. And that’s why I also give
you a choice to make in FOMOD.*

### [Masculine Khajiit Textures](https://www.nexusmods.com/skyrimspecialedition/mods/186)

**Main files** - Masculine Grey Cat and Leopard (Vanilla) 4K

**FOMOD** - `Grey Cat, Abs`.

Yes, you have read it right. For one other mod to work correctly, we
will need to choose a different version of Masculine Khajiit Textures.

**Rename** - Rename it to `Masculine Khajiit Textures - TPF Dragon’s Edition` to install it as a separate mod.

### [Masculine Argonian Textures](https://www.nexusmods.com/skyrimspecialedition/mods/185)

**Main files** - Masculine Chameleon and Lizard (Vanilla) 4K

**FOMOD** - `Lizard, Heavy Scales`.

**Update files** - Masculine Argonian EXTRA (Vanilla) 4K

**FOMOD** - `Lizard, Heavy Scales - Abs` 3 times.

**Merge** - Merge both files.

*Flawn's Vanilla Argonians Redux mod looks very good, but there are another great looking textures for argonians, which work with the mod we want to use and
which are done by the same author, which textures we use for Khajiits.*

### [Tempered Skins for Females](https://www.nexusmods.com/skyrimspecialedition/mods/8505)

**Main files** - Tempered Skins for Females UNP and Vanilla

**FOMOD** - `A7 and F none`, for other things you can choose whichever
options you like. `My recommendations - B01, C2, D1, E2`.

### [Feminine Khajiit Textures](https://www.nexusmods.com/skyrimspecialedition/mods/183)

**Main files** - Feminine Grey Cat and Leopard (UNP) 4K

**FOMOD** - `Grey Cat, Abs`.

**Rename** - Rename it to `Feminine Khajiit Textures - TPF Dragon’s Edition` to install it as a separate mod.

### [Feminine Argonian Textures](https://www.nexusmods.com/skyrimspecialedition/mods/184)

**Main files** - Feminine Chameleon and Lizard (UNP) 4K

**FOMOD** - `Lizard, Abs`.

### [Sandow Plus Plus - Ripped Bodies](https://www.nexusmods.com/skyrimspecialedition/mods/34632)

**Main files** - Sandow Plus Plus - Ripped Bodies

**Main files** - Sandow Plus Plus - Ripped Bodies - Males

**Main files** - Sandow Plus Plus - Ripped Bodies - UNP

**FOMOD** - `Choose every option in all these 3 mods (exception is in one
place in the file for males, where you need to choose vanilla type of
body, then again every race)`.

*The weight slider in Racemenu will also make us more ripped, not just
bigger.*

### [Equipable Beast Tails - HDT SMP](https://www.nexusmods.com/skyrimspecialedition/mods/31745)

**Main files** - Equipable Tails - HDT SMP v1.2 ESL NoCraftables

**Disable** - disable _Argonian Weight Slider Affected Tails_ and _FVAR - Weight Slider Affected Tails Patch_ mods in the _APPEARANCE_ separator of TPF.

*Finally tails, which are actually moving. Maybe even a bit too much. With this I have actually killed two hares - they have an option to be removed in-game, which I will explain about later, and did I mention that they are moving.*

### [Grimoas Plantigrade Feet For Beast Races](https://www.nexusmods.com/skyrim/mods/16976)

**Main files** - Grimoas Plantigrade Feet For Beast Races v 1_4

**Delete** - remove `Gri_BeastFeet.esp`.

*A resource from Skyrim LE to make our next mod work (thank you very
much).*

### [Barefoot Beast Project (Greaves and Legwraps for Plantigrade Feet)](https://www.nexusmods.com/skyrimspecialedition/mods/45672)

**Main files** - Barefoot Beast Project

*Now we won’t need to imagine anymore how our poor Argonian puts those
little boots on.*

### [BeastHHBB](https://www.nexusmods.com/skyrimspecialedition/mods/38480)

**Main files** - BeastHHBB - Player Character only

*Many appearance mods have one thing in common - they almost always forget about poor beast races. 
But not this one as it adds many options exlusively for them to make their look more unique.*

### [High Poly Head](https://vectorplexus.com/files/file/283-high-poly-head/)

High_Poly_Head_v1.4\_(SE).zip

**FOMOD** - `BSA Only, Special Edition, Expressive Facegen Morphs,
Expressive Facial Animation (both), High Poly Vanilla Hair, Vampire Head
Fix, Symmetrical Eyes (Female)`.

*With this your dreams of making an even more perfect face for your
character shouldn't wait for long anymore.*

### [KS Hairdos](https://www.nexusmods.com/skyrimspecialedition/mods/6817)

**Main files** - KS Hairdos

*Fancy hair mod for us.*

### [KS Hairdos - HDT SMP](https://www.nexusmods.com/skyrimspecialedition/mods/31300)

**Main files** - KS Hairdos SMP

*New level of fanciness. People love hair with physics, so let them be.*

### [Another KS Hairdos Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/59427)

**Main files** - Another KS Hairdos Replacer

**Main files** KS Hairdos HDT SMP Replacer

*Plugin replacers to remove too anime, clipping etc. KS Hairdos hairstyles from Racemenu.*

### [KS Hairdos with Physics for Men](https://www.nexusmods.com/skyrimspecialedition/mods/55986)

**Main files** - KS Hairdos SMP for Men

_You will be able to get hair with physics for men by using AddItemMenu mod, which will be covered later._

### [Kyoe's Bang'n Brows](https://www.nexusmods.com/skyrimspecialedition/mods/13630)

**Main files** - Kyoe's Bang'n Brows - Standalone - Vanillamatch

_For people, who would like to use a bit brighter brows than the vanilla ones._

### [Kyoe's Bang'n Brows for KouLeifoh's High Poly Head](https://www.nexusmods.com/skyrimspecialedition/mods/50424)

**Optional files** - 'Kyoe's Bang'n Brows - Standalone - Vanillamatch' for High Poly Head

---

## Gameplay Overhauls

This section is intended to compliment TPF's gameplay and combat overhauls with a touch of immersiveness by adding new, not intrusive mechanics or by changing already existing ones.

Create a separator and name it `GAMEPLAY OVERHAULS EXTENDED` and place it
directly below the *GAMEPLAY OVERHAULS* separator (and its mods). Change its
colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

### [No Lock Picking](https://www.nexusmods.com/skyrimspecialedition/mods/32218)

**Main files** - NoLockPicking v2

*Removes the lock picking mini-game (annoying) from the game and now
actually uses your lockpicking skill to open doors and chests. Each picked lock and tries to pick it put points in your lockpicking skill like always. 
Your lockpicks' breaking rate is also being affected by your skills.*

### [Reading is Good](https://www.nexusmods.com/skyrimspecialedition/mods/42026)

**Old files (v. 1.1.0.)** - Reading Is Good SE

*Makes us smarter in an immersive way by giving us a permanent boost to a leveling speed in a skill, which we have read about.*

### [C.O.I.N. - Coins of Interesting Natures](https://www.nexusmods.com/skyrimspecialedition/mods/51439)

**Main files** - C.O.I.N.

**FOMOD** - `Author's Choice`, Auto Conversion - `Enabled`, `Beyond Skyrim - Bruma, The Tools of Kagrenac, WACCF, Wyrmstooth, USSEP`.

*Draugr will stop stealing any septims around Skyrim and bringing them to crypts. Only fruits and vegetables from time to time as an offering for ... themselves? Maybe someone else.*

### [Smart NPC Potions - Enemies Use Potions and Poisons](https://www.nexusmods.com/skyrimspecialedition/mods/40102)

**Main files** - Smart NPC Potions

*Finally bandits, mages and assassins will also have an option to have
and use some potions. And not just healing potions, which they already
use, to make our lives a little bit harder. Everything, for instance, a
chance of them having a potion, is configurable by MCM.*

### [Sensible Bribes](https://www.nexusmods.com/skyrimspecialedition/mods/55450)

**Main files** - Sensible Bribes

*Makes bribe option in dialogues actually depend on your speech skill, so you will have to pay a fortune if you aren't skilled with your words enough.*

### [Pilgrim - A Religion Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/54099)

**Main files** - Pilgrim

**FOMOD** - `Beyond Skyrim - Bruma`.

**Disable** - Disable *Adamant - Shrines and Amulets* in the _Gameplay Overhauls_ section and _Miscellaneous Tweaks Collection - Shrines Don't Cure Diseases_.

*In the Elder Scrolls universe everything is connected to different kinds of deities, so it isn't a surprise that Skyrim's people are ardent believers. Let's make religion more important for our player character too.*

### [Dragonborn - Shouts Perk Tree](https://www.nexusmods.com/skyrimspecialedition/mods/41950)

**Main files** - Dragonborn - Shouts Perk Tree

*Being Dragonborn and being able to shout should make us more unique
than other characters, and this mod does that by giving us experience
and perk points for shouting and killing dragons and a unique skill tree
for spending these. It will be available after finishing The Way of the Voice quest.*

### [More Werewolves](https://www.nexusmods.com/skyrimspecialedition/mods/7259)

**Main files** - More Werewolves

*Yes, more werewolves will be in Skyrim, so be attentive especially when
traversing the areas around Morthal and Falkreath.*

**FOMOD** - `Standalone version, RFYL Patch`.

### [Canis Hysteria - The Werewolf Disease](https://www.nexusmods.com/skyrimspecialedition/mods/52397)

**Main files** - Canis Hysteria

**FOMOD** - `Improved Companions - Questline Tweaks`.

*You can finally become a werewolf without joining the Companions if you aren’t their type in the immersive way.*

### [Werewolf Aela](https://www.nexusmods.com/skyrimspecialedition/mods/29155)

**Main files** - Werewolf Companions v1.3 FOMOD

**FOMOD** - `No Facial Edits, Aela’s Transformation Only for 3 Minutes
and 45 Minutes`.

*Has it always bothered you that Companions can’t turn into werewolves
or do that only during Companions quests? Well, me too. This mod makes
Aela transform into werewolf, if she is badly hurt. Aela will always
want to stay as werewolf, not like Farkas and Vilkas, who can be cured,
so I have decided that it will be enough just with her.*

### [Scion - Vampiric Sunscreen Plugin](https://www.nexusmods.com/skyrimspecialedition/mods/42212)

**Main files** - Scion - Vampiric Sunscreen Plugin

*If you wear any type of headgear, while being outdoors, like our
vampire friend Serana does, you won’t be destroyed by sun damage.*

### [Catir’s College Creatures](https://www.nexusmods.com/skyrimspecialedition/mods/44557)

**Main files** - Catir's College Creatures

*Now you will actually need to use magic to beat the College of
Winterhold quest line. You have been warned, don’t sneak peek at the
description of the mod.*

### [Angi's Camp Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/44914)

**Main files** - Angi's Camp Tweaks

*Quality of life changes for Agni’s training session.*

---

## Miscellaneous

This category's mods are focused on adding some quality of life tools
and changes to the game. In many situations, these mods won't even
bother you in any way if you aren't actually using them, so I decided
not to make this section optional as it isn't intrusive as *INTERFACE*,
which changes things you will always see (and I don't want to make
separate patches for this bulky section).

Create a separator and name it `MISCELLANEOUS EXTENDED` and place it
directly below the *MISCELLANEOUS* separator (and its mods). Change its
colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

### [Storm Lightning - Settings Loader](https://www.nexusmods.com/skyrimspecialedition/mods/57477)

**Main files** - Copy and Paste in Console v1.0.1 for Skyrim SE

*A great tool for making you spend less time in the TPF mod's MCM the second time you decide to play.*

### [UIExtensions](https://www.nexusmods.com/skyrimspecialedition/mods/17561)

**Main files** - UIExtensions v1-2-0

*Resource for modders to use to make custom menus for their mods. We
will need it for AddItemMenu mod.*

### [Custom Skills Framework](https://www.nexusmods.com/skyrimspecialedition/mods/41780)

**Main files** - Custom Skills Framework v1

*.NET Script Framework’s plugin for making custom skill trees for our
character, will be used for Dragonborn - Shouts Perk Tree, which will greatly enhance gameplay
with shouts together with Forceful Tongue - Shouts Overhaul.*

### [Face Discoloration Fix](https://www.nexusmods.com/skyrimspecialedition/mods/42441)

**Main files (v. 1.0.1.)** - Face Discoloration Fix

*Helps us to avoid relegenerating facegen for NPCs affected by Vanilla Head Replacer mod, because apparently Bethesda is unhappy even if you just change hair of NPCs without any issues.*

### [HDT-SMP (Skinned Mesh Physics)](https://www.nexusmods.com/skyrimspecialedition/mods/30872)

**Main files** - HDT-SMP for SSE 1.5.97 v2.11

*SKSE plugin, which will allow us to use physics for our PC, like in our
scenario, with moving hair. Bonk people, who thought about something
else.*

### [Copy and Paste in Console](https://www.nexusmods.com/skyrimspecialedition/mods/30928)

**Main files** - Copy and Paste in Console v1.0.1 for Skyrim SE

**INI** - In line 2, change _PasteKeyCode_ to `47`, so you will need
standard _Ctrl+V_ command to paste something to your console.

*A neat functionality in one mod (very weird that Bethesda haven't
thought about adding it, well, like always), which you will probably use
from time to time.*

### [AddItemMenu - Ultimate Mod Explorer](https://www.nexusmods.com/skyrimspecialedition/mods/17563)

**Main files** - AddItemMenuSE_114_SKSE2019

*A mod, which makes it possible to test all items other mods have to
offer inside their plugins. I hope you won’t use it for cheating.*

### [Dragonborn Presence](https://www.nexusmods.com/skyrimspecialedition/mods/25287)

**Main files** - Dragonborn Presence

**Instructions** - Install the mod, right-click *Data* folder and select
*Set as data directory*, click *OK*. Right-click the mod in your
*Downloads* tab and select *Open File*, move *discord-rpc.dll* file to
the game's stock folder.

*Allows your friends in Discord to see that you are actually really busy
looting Nazeem's house.*

### [Navigator - Navmesh Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/52641)

**Main files** - Navigator - Navmesh Fixes

**FOMOD** - `ESP-FE`.

*Navmesh tweaks for some dungeons.*

### [Mfg Fix](https://www.nexusmods.com/skyrimspecialedition/mods/11669)

**Main files** - MfgFix

*Just a couple of fixes for Skyrim’s facial animation scripts, which
will be needed by Conditional Expressions.*

### [First Person Camera Height Fix](https://www.nexusmods.com/skyrimspecialedition/mods/28091)

**Main files** - First Person Camera Height Fix

*Who would have thought that High Elves are actually high. I thought
they just named themselves like that. One other mod, which we will
install later, will greatly help us in using this mod’s capabilities.*

### [High Gate Ruins Puzzle Reset Fix](https://www.nexusmods.com/skyrimspecialedition/mods/53643)

**Main files** - High Gate Ruins Puzzle Reset Fix

*For you to be able to clean High Gate Ruins again and get that loot if you will want to go through that again.*

### [End Times](https://www.nexusmods.com/skyrimspecialedition/mods/39201)

**Main files** - End Times SE

*Now try to do everything else, but not the main quest. I dare you. If
you don’t listen then your game will be over. It was a joke by the way. More about this later.*

### [BlockSteal](https://www.nexusmods.com/skyrimspecialedition/mods/18732)

**Main files** - Blocksteal_010_SKSE2017

*Prevents you from stealing, when you aren’t in stealth mode, so you
won’t get punished by just wanting to take another item, which that
annoying, but expensive cup was near. There is also an option to press
on items multiple times, which is configurable through MCM.*

### [Don't Stay in The Water](https://www.nexusmods.com/skyrimspecialedition/mods/52164)

**Main files** - Don't Stay in The Water

*Now you won’t be able to “outsmart” your enemies by going into water (except animals like sabercats, which don't like water).*

### [Simply Knock](https://www.nexusmods.com/skyrimspecialedition/mods/14098)

**Main files** - Simply Knock SE 1.0.3 Release

*I find it immersive that we can get to our good friend to say that we
saved his family friend during the night, not to wait for 8 hours, when
she will wake up. Or to check if people are home for sneaky shenanigans.
This mod allows us to do that.*

### [Simply Knock SKSE64 DLL](https://www.nexusmods.com/skyrimspecialedition/mods/24297)

**Old files** - SimplyKnockSE SKSE64 2.0.19 DLL

*An updated .dll file for the mod to work.*

### [A Guiding Light - Clairvoyance Reimagined](https://www.nexusmods.com/skyrimspecialedition/mods/35464)

**Main files** - Guiding Wisp

**Delete** - remove `GuidingLight.modgroups`.

*Finally makes Clairvoyance spell useful by making it summon a wisp that
leads you to your quest objective.*

### [Use Telekinesis on Traps](https://www.nexusmods.com/skyrimspecialedition/mods/59350)

**Main files** - Use Telekinesis on Traps - po3's Papyrus Extender Version

_Sometimes I just can't believe that some of mods like this one appered only recently._

### [Civil War Neutrality](https://www.nexusmods.com/skyrimspecialedition/mods/21176)

**Main files** - CWN - Civil War Neutrality SSE

*Let Stormcloaks and the Empire play their own games, while being
neutral, but getting your deserved rewards.*

### [Sleeping Expanded](https://www.nexusmods.com/skyrimspecialedition/mods/59250)

**Main files** - Sleeping Expanded

*I understand that sometimes it is very hard to get out of bed, but come on, NPCs, you are getting attacked. I will even help you with this. Also adds breathing for NPCs, while they are sleeping and makes NPCs angry if you wake them up at 3 AM. Very immersive.*

### [Serio's Cycle Hotkeys](https://www.nexusmods.com/skyrimspecialedition/mods/27184)

**Main files** - Serio's Cycle Hotkeys

*Makes it possible to adjust one hotkey to equip not just one spell or
option, but different sets of things. For instance, if I am a mage, I
can use my first hotkey to equip Ice Storm spell in both hands and Ice
Form shout to battle with melee enemies, then press my second hotkey to
get my ward spell and Thunderbolt to deal with that pesky bandit mage.
You can set whatever buttons you want as these hotkeys. Pretty detailed
instructions on how to use the mod can be found in the mod's page.*

### [Hide Your Quests](https://www.nexusmods.com/skyrimspecialedition/mods/50125)

**Main files** - Hide Your Quests 1.0.1

*Successor of the mod Hide Those Futile Quests, which gives you an
option to hide a quest you will do later from your journal by using
MCM.*

### [Forget Spell](https://www.nexusmods.com/skyrimspecialedition/mods/51125)

**Old files (v. 1.2.2.)** - Forget Spell

**FOMOD** - `Skyrim Special Edition, SkyUI`.

*Another neat addition - allows us to forget spells we won't use
anymore. Why would I need to clutter my menu with Flames, while I am
level 80 mage. You will see an option to forget spells in your spells
menu.*

### [Diziet's Auto Outfits](https://www.nexusmods.com/skyrimspecialedition/mods/40801)

**Main files** - Diziet's Auto Outfits

**FOMOD** - don’t change anything.

*The mod makes you automatically change your outfit according to
different conditions, which can be configured inside the mod's MCM. For
example, I use it to change my default gear to ordinary clothing with
speech etc. enchantments for traders, when I am inside big cities.
Otherwise I will probably forget to do that.*

### [More Growable Plants](https://www.nexusmods.com/skyrimspecialedition/mods/3880)

**Optional files** - More Growable Plants Simple 1.5

*Still no idea where citizens of Skyrim get their apples, tomatoes,
garlic and many other things from, but at least we know where we can get
them from. And don’t worry, I have patched it, so you will be able to
grow only things I consider to be immersive to be grown by player character.*

### [Hearthfire Multiple Adoptions and Custom Home Support](https://www.nexusmods.com/skyrimspecialedition/mods/3862)

**Main files** - Hearthfire Multiple Adoptions and Custom Home Support SE

*Not only allows you to adopt more children, but also to bring your
spouse and kids to the new houses we have added.*

### [Sweeping Organizes Stuff - Use Broom to Clean Mess](https://www.nexusmods.com/skyrimspecialedition/mods/51645)

**Main files** - Sweeping Organizes Stuff - Use Broom to Clean Mess

*Let's say you accidentally pressed your shout button in your home or
just wanted to make some chaos, now you can clean the mess by using a
broom from your inventory.*

### [Dragon Claws Auto-Unlock](https://www.nexusmods.com/skyrimspecialedition/mods/47329)

**Main files** - Dragon Claws Auto-Unlock (Simultaneous)

*I don’t want to check these claw combinations again and again. It was
fun, when Skyrim was a new game for me.*

### [Look What You See](https://www.nexusmods.com/skyrimspecialedition/mods/19189)

**Main files** - Look what you see

**FOMOD** - `ESL`.

**Instructions** - rename the mod’s plugin to `TissHeadTrack.esp`.

**Alternate Conversation Camera Plus tweaks** - go to _Alternate
Conversation Camera Plus_ INI (you can find the mod under TPF's _CONTROLS & CAMERA_ separator) , in line 47, change _bConversationHT_ to `0` (for compatibility between those two mods).

*Head tracking mod, which makes our player character (PC) observe
things, which we move our cursor on.*

### [DIVERSE SKYRIM](https://www.nexusmods.com/skyrimspecialedition/mods/7707)

**Main files** - DIVERSE SKYRIM SSE

*Skyrim isn’t just for Nords, it is for everyone. Groups like bandits,
mages etc. will also include some Khajiits, Argonians from time to time
etc.*

### [DIVERSE SKYRIM - Cathedral NPCs Facegen Patch](https://www.nexusmods.com/skyrimspecialedition/mods/43514)

**Main files** - DIVERSE SKYRIM - Cathedral NPCs Facegen Patch

*And let’s also fix them and make them better to look at.*

### [Diverse Skyrim - Battle of Whiterun Fix](https://www.nexusmods.com/skyrimspecialedition/mods/47939)

**Main files** - Diverse Skyrim Battle of Whiterun Fix

### [Starlit Lakes Loading Screens](https://www.nexusmods.com/skyrimspecialedition/mods/57579)

**Main files** - Starlit Lakes Loading Screens - SSE

*Replaces stale, not eye-catching loading screens with new ones with
lore-friendly artwork of Skyrim and what it has to offer. At least
people, who have to wait longer on them, will be pleased and maybe will actually learn something new from these.*

### [Less Boring Loading Screen](https://www.nexusmods.com/skyrimspecialedition/mods/55062)

**Main files** - Less boring loading screen main

### [Interesting Loading Screens](https://www.nexusmods.com/skyrimspecialedition/mods/26282)

**Main files** - Interesting Loading Screens

### [Strange Runes](https://www.nexusmods.com/skyrimspecialedition/mods/19456)

**Main files** - Strange Runes 3.7.2

*Great for screenshots and makes magic feel even more unique. MCM (Mod
Configuration Menu) available, so you can make them appear only for some
specific spell group etc. You need it! Just look at my
character.*

![image](https://user-images.githubusercontent.com/37147270/132093585-9427e5c8-9e41-46d8-af97-2aac9627547a.png)
_(ft. 1.6. v. of TPF - Dragon's Edition's appearance, apparel & weapons mods)_
![image](https://user-images.githubusercontent.com/37147270/130328931-2f92e74c-1a43-4696-8404-0f2cf1a8c222.png)
_(ft. TPF - Dragon's Edition in its development days)_

### [BA Bard Songs](https://www.nexusmods.com/skyrimspecialedition/mods/47202)

**Main files** - BA_BardSongs_FOMOD

**FOMOD** - `AIO`.

*I am sick of hearing the same compositions from bards over and over again.*

### [Talkative Dragons](https://www.nexusmods.com/skyrimspecialedition/mods/26955)

**Main files** - Talkative Dragons

*For species, which can actually speak the way that humans understand,
dragons in the game don’t like to speak at all. Let’s change that.*

### [Talkative Dragons - Audio Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/27269)

**Main files** - TDReplacer

*Just a little replacer for some voice lines in the original mods, which
sounded a little bit too silly.*

### [Gildergreen Regrown](https://www.nexusmods.com/skyrimspecialedition/mods/348)

**Main files** - Gildergreen Regrown

*That’s a little bit stupid than in vanilla you don’t get to see the new
Gildergreen growing from the sapling. Let’s change that.*

### [Animated Forge Water](https://www.nexusmods.com/skyrimspecialedition/mods/52322)

**Main files** - Animated Forge Water

**FOMOD** - `Slower Embers HD`.

*Just look at that monstrous vanilla forge water and you won't have any questions.*

### [Character Light](https://www.nexusmods.com/skyrimspecialedition/mods/58955)

**Main files** - Chracter Light SE AE v1

*Purely cosmetic mod, which allows you to take better screenshots with your character by adjusting character's brightness. Can be use in an ordinary walkthrough too as 
it doesn't use scripts. Obtainable by using AddItemMenu.*

### [RaceMenu Undress](https://www.nexusmods.com/skyrimspecialedition/mods/56437)

**Main files** - RaceMenu Undress

*Makes undressing slider available for you in RaceMenu to change not only your character face's appearance more easily.*

### [3D Mountain Flowers Hearthfire Planters Fix](https://www.nexusmods.com/skyrimspecialedition/mods/49113)

**Main files** - More Growable Plants_3D Mountain Flowers patch

### [ENB Lava Particle Light Patch](https://www.nexusmods.com/skyrimspecialedition/mods/54657)

**Main files** - ENB Lava Particle Light Patch

---

## SKELETON & ANIMATIONS

At first, you will need to change Simple Dual Sheath INI to make OUR
shield appear on the back, which I believe will look much better and more immersive than vanilla placement.

Like you can see in the screenshots, with these placement configurations everything looks much less clunky. 
Bow won't be together with quiver, so they won't clip through each other and
it is much more likely to see soldier carrying his shield on his back than in hands for all day, while the shield isn't being used.

<p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/37147270/132091012-c9491ef7-ddd7-4019-92c6-15116c4e1cb6.png" /> 
</p>

Overall through animations we will add more life and uniqueness into our
player character. NPCs are untouched by these different gear locations,
so we won’t have to worry about manually adjusting each NPC’s look. And,
as the obligatory part, the mods we are going to add will make us use
dual sheath animations.

**INI in Simple Dual Sheath** - In line 23, change *Flags* to
`Player`, then in line 38, change *DisableHideOnSit* to
`Player|MountOnly`.

Create a separator and name it `SKELETON & ANIMATIONS EXTENDED` and place it
directly below the *SKELETON & ANIMATIONS* separator (and its mods).
Change its colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

### [Ice Skating Fixed](https://www.nexusmods.com/skyrimspecialedition/mods/55417)

**Main files** - EVE - Ice skating fixed for real - No more attack skating movement

_Fixes the vanilla issue, where attacking, while moving slowly, will make you slide across the ground giving the impression of an ice-skater._

### [Animation Motion Revolution](https://www.nexusmods.com/skyrimspecialedition/mods/50258)

**Main files** - Animation Motion Revolution 1.4

_A SKSE plugin, which removes the mismatch between displacement and supported animations. It basically fixes ice-skating for new animation mods._

### [Better Power Attack Direction Control](https://www.nexusmods.com/skyrimspecialedition/mods/49648)

**Main files** - Better PowerAttack Control-SSE

_Another plugin, which helps your power attack to be executed by relying only on your input, but not on your character's movement direction and movement speed to be in sync with your other actions to prevent issues with other animations._

### [iFrame Generator](https://www.nexusmods.com/skyrimspecialedition/mods/56965)

**Main files** - IFrame Generator-v0.91

_And another one, which allows us to use a script-free invincibility frames feature for all animation mods, which will use the feature._

### [War Hammer and Battle Axe Movement Fix](https://www.nexusmods.com/skyrimspecialedition/mods/51615)

**Main files** - SSE Version

*A little fix for war hammers and battle axes' movement animations, so they won't get a bit jank after running or starting to run.*

### [Conditional Expressions - Subtle Face Animations](https://www.nexusmods.com/skyrimspecialedition/mods/45148)

**Main files** - Conditional Expressions

**Instructions** - Download the main file manually and drop it into your MO2 Downloads folder, the file will appear in your Downloads tab in MO2, right click on it and select Query Info, then install it as always.

*Gives our character a bit of emotions, to finally make us not look like
a piece of living rock.*

### [Pretty Combat Animations](https://www.nexusmods.com/skyrimspecialedition/mods/3761)
**Main files** - Pretty Combat Animations 1.38

**FOMOD** - `Style 01, Sneak Turn, Vanilla, Crossbow, Ranger, Slayer` two
times, `2hm Block, 2hm Sprint`.

### [Pretty One-Handed Animations Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/3772)

**Main files** - PCA-1hm Overhaul 1.13c SSE

**FOMOD** - `Guardian, choose _Skip_ option 4 times, 1hm Block, 1hm
Sprint, Origin Dw Sprint_Type A`.

### [Leviathan Animations - Two-Handed High Stance](https://www.nexusmods.com/skyrimspecialedition/mods/47092)

**Main files** - Leviathan Animations - Two-Handed High Stance SE

### [Leviathan Animations - Two-Handed Normal Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/48550)

**Main files** - Leviathan Animations - Two-Handed Normal Attacks For High Stance

### [Leviathan Animations - Two-Handed Power Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/50545)

**Main files** - Leviathan Animations - Two-Handed Power Attacks For High Stance

### [Vanargand Animations - One Handed Mid Stance](https://www.nexusmods.com/skyrimspecialedition/mods/57544)

**Main files** - Vanargand Animations - One handed Mid Stance

### [Vanargand Animations - One Handed Normal Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/58326)

**Main files** - Vanargand Animations - One handed Normal Attacks

### [Vanargand Animations - One Handed Power Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/58997)

**Main files** - Vanargand Animations - One Handed Power Attacks

### [Vanargand Animations - Sneak Idle Walk and Run](https://www.nexusmods.com/skyrimspecialedition/mods/54351)

**Main files** - Vanargand Animations - Sneak Idle Walk and Run

### [Vanargand Animations - Sneak Thrust Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/55031)

**Main files** - Vanargand Animations - Sneak Thrust Attacks

### [Vanargand Animations - Sneak Strike Attacks](https://www.nexusmods.com/skyrimspecialedition/mods/55420)

**Main files** - Vanargand Animations - Sneak Strike Attacks

### [Skyrim's Paraglider](https://www.nexusmods.com/skyrimspecialedition/mods/53256)

**Main files** - SkyrimsParaglider

**FOMOD** - `Contrails Off, Dragon Paraglider`.

*Traverse through Skyrim in even more ways than you have thought is possible.*

### [Paraglider Auto - Equip Tarhiel's Gale](https://www.nexusmods.com/skyrimspecialedition/mods/53436)

**Main files** - Paraglider Auto-Equip Tarhiel's Gale

*Paraglider comes with a spell book that allows us to get higher in the air. This mod makes the spell automatically eqipped, when we glide.*

### [Thu'um - Fully Animated Shouts](https://www.nexusmods.com/skyrimspecialedition/mods/50559)

**Main files** - Thu'um - Animated Shouts

*Do you even need to ask me why? This is epic.*

### [Dynamic Swimming](https://www.nexusmods.com/skyrimspecialedition/mods/34853)

**Main files** - DAR - Dynamic Swimming

**Optional files** - DAR - Dynamic Swimming - Argonian Mastery

**Merge** - merge both files.

*Vanilla swimming animation looks shabby, so let it be used just for
people, who like to swim with heavy armour equipped.*

### [Run Sprint and Jump](https://www.nexusmods.com/skyrimspecialedition/mods/15881)

**Main files** - Jog Sprint and Jump

**Hide** - hide any file, which overwrites _Jump Behavior Overhaul_ by right-clicking the mod, then choosing the _Conflicts_ tab, selecting all the files on the _Winning file conflicts section_, where overwritten mod includes _Jump Behavior Overhaul_, right-clicking on them and choosing _Hide_.

### [Magic Casting Animations Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/5215)

**Main files** - Magic Casting Animations Overhaul SSE

*Improvements for Skyrim’s third person animations.*

**FOMOD** - `Cast damage, cast self` and `staff cast`.

### [New Animation for Magic Casting](https://www.nexusmods.com/skyrimspecialedition/mods/31989)

**Optional files** - New Animation for magic cast v0.8

**Hide** - hide `staffright_idle.hkx` and `staff_idle.hkx`.

### [First Person Magic Animation](https://www.nexusmods.com/skyrimspecialedition/mods/20375)

**Main files** - First Person Magic Animation for SSE

**FOMOD** - `01 Variant 1 FPMA 7.0`.

### [1st Person Parry Animation](https://www.nexusmods.com/skyrimspecialedition/mods/20374)

**Main files** - 1stPerson Parry Animation

**FOMOD** - `01, 02, 03`.

### [Crosshair-aligned Crossbow](https://www.nexusmods.com/skyrimspecialedition/mods/42267)

**Main files** - Crosshair-aligned Crossbow

### [TK Dodge](https://www.nexusmods.com/skyrimspecialedition/mods/15309)

**Main files** - TK Dodge SE

**Main files** - Replace to Step Dodge

**Merge** - merge both files.

**Delete** - remove all files from the mod exluding the _Meshes_ folder with its contents.

*Gives you an ability to sidestep, dodge attacks. Just press the
directional key two times to dodge in that direction. I chose the side
step version, because I don’t see characters with heavy armour rolling
around at all, even in this fantasy world, but sidestep is alright.*

### [TK Dodge RE](https://www.nexusmods.com/skyrimspecialedition/mods/56956)

**Main files** - TK Dodge RE-v0.46

**Optional files** - Weapon Sheathed Firstperson Dodge Animations

**Merge** - merge both files.

**INI** - In line 12, change _StepDodge_ to `true` and, ini line 5, change _DodgeHotkey_ to your prefered one by using instructions [here](https://www.creationkit.com/index.php?title=Input_Script#DXScanCodes).  I recommend one of your mouse’s buttons if you have many buttons on it.

*An update for TK Dodge to make it not use any scripts and to overall improve the mod.*

### [Crouch Sliding](https://www.nexusmods.com/skyrimspecialedition/mods/39157)

**Main files** - Crouch Sliding Main

**Optional files** - Toned Down Slide Dust Effect

**Merge** - merge both files.

*When you are running around and suddenly see enemies or just want to
hide behind cover as soon as you can, just press your sneaking button
while sprinting.*

### [Crouch Sliding - Remove Ragdolling for Good](https://www.nexusmods.com/skyrimspecialedition/mods/46828)

**Main files** - Crouch Sliding - Remove Ragdolling for Good

*Removes one overpowered mechanic from the previous mod, so you won’t
even know that it was there in the first place.*

### [Turn Animation Fix](https://www.nexusmods.com/skyrimspecialedition/mods/54803)

**Main files** - Turning animation won't affect upper body

*Literally what is written - it disables turning animations on upper body, so we won't look add while aiming our bow in the 3rd person etc.*

### [Undeath - XPMSSE - Strange Runes - Skeleton Patch](https://www.nexusmods.com/skyrimspecialedition/mods/50694)

**Main files** - Undeath - XPMSSE - Strange Runes - Skeleton Patch

*If we don’t overwrite one of the XP32MSSE skeleton’s with this one, our
character in some scenarios would have been invisible and their spell
runes would have appeared near their feet, so let’s put it here.*

### [Ultimate Combat and Creature Behaviour's Nemesis Compatibility](https://www.nexusmods.com/skyrimspecialedition/mods/45966)

**Main files** - Ultimate Combat and Creature Behaviour's Nemesis
Compatibility

*Yeah, and some other utilities needed.*

**FOMOD** - Don’t change anything.

### [Dragon Priest Fix - Behaviour Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/51608)

**Main files** - Dragon Priest Fix - Behaviour Overhaul

### [SavrenX Vampire Lord Tank](https://vectorplexus.com/files/file/271-savrenx-vampire-lord-tank/)

*When I saw Harkon for the first time, well, it was a little bit sad
that Vampire Lord looks like a noodle. And with that mass, he probably
looked awkward, when he used melee combat against us. Let’s separate
Vampire Lords even more from senile ordinary vampires.*

### [Vampire Lord - Animation Replacer](https://www.nexusmods.com/skyrimspecialedition/mods/54441)

**Main files** - VL_AR

**Instructions** - Install the mod, double click on _SE_, then right-click _Data_ folder and select _Set as data directory_, click _OK_.

*You can even see wings actually moving, while we are flying. A must have mod.*

### [Undead Summons Emerge from the Ground](https://www.nexusmods.com/skyrimspecialedition/mods/33955)

**Main files** - Undead summons emerge from the ground

*I know that undead work a little bit differently in the Elder Scrolls
universe, but it still doesn’t make sense for soul’s physical form to
appear out of thin air, so here we go.*

---

## NPC OVERHAULS

As you probably understood (I hope), this project definitely goes over
vanilla+ mark (of course, you are using all those mods, what do you even
talk about...) and I understand that too. With this category of mods I
just want Skyrim to look a little bit more classy, modern. It is an
adventure game with magic, dragons, other mythical creatures and so many
things I will have to write millions of words to describe. Do you really
want to spend your money on a game to look at silly faces and then play
while looking at those, when you have an option to change that? And also
I believe that in my game - fantasy, where I decide what will happen -
everyone has the right to look decent and appealing to my eyes (don't
have any experience where someone criticized the _too good_ looks of an
actress for a specific movie or a character in a game). So here we go.

Create a separator and name it `NPC OVERHAULS` and place it directly
below the *FINAL PATCHES* separator (and its mods). Change its colour,
so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

In some scenarios we are going to hide some files from specific
overhauls, because even considering the fact I have sorted overhauls
relying on overall preference there are some exceptions I like more. For
example, I love Evette San’s look from a mod called *The Ordinary
Women*, but a mod called *Kalilies NPCs* is overwriting it with it’s own
looks. So to make Evette from The Ordinary Women appear we are hiding
her facegen files from Kalilies NPCs to make sure that the game loads
needed files and my custom made plugin for our overhauls makes sure that
The Ordinary Women wins the conflict on loads data of the Ordinary Women
correctly.

If you don't understand or want to know what will happen if you do
something incorrectly, here are some examples. You have probably heard about the
issue once or twice - black face bug. CTDs can happen if overhaul uses
unique body parts (like the previous versions of The Ordinary Women) and you enter into the place
where this incorrect NPC is.

<p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/37147270/130331187-55046f91-3255-4c24-98b8-b6a6afbcd183.png" />
    <img width="45%" src="https://user-images.githubusercontent.com/37147270/130334940-83643fa2-edec-442c-a98a-5a7a6ee0d34a.png" />
</p>

### [High Poly Expressive NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/41107)

**Main files** - High Poly Expressive NPCs - Nordic Faces

**Miscellaneous files** - WACCF Patch

**Hide facegen files** - Double click on the mod in your mod order,
switch to *Conflicts* tab, at the right side of *Winning file conflicts*
there will be a filter, write `Simple Children` into it, hide all appeared files.

*Very good base to start our NPC overhauling.*

### [Shield Sisters Re-Imagined](https://www.nexusmods.com/skyrimspecialedition/mods/44243)

**Main files** - Shield Sisters Re-Imagined UNP

**Update files** - Iona Jordis Illia Hotfix

**Merge** - merge both files.

**Hide facegen files** - Double click on the mod in your mod order,
switch to *Conflicts* tab, at the right side of *Winning file conflicts*
there will be a filter, copy `00013478` into it, hide two appeared
files.

*One of the newest additions to NPC overhauls of Skyrim, which spices
things up. Has Bijin series’ mods vibes, but feels more unique.*

### [Pandorable’s NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/19012)

**Main files** - Pandorable's NPCs SE

**Optional files** - PAN_NPCs - AI Overhaul patch

**FOMOD** - `USSEP` (Pandorable has probably forgotten to change name from
LE's Unofficial Patch in her FOMOD), `no warpaint only for Voldsea`.

*Pandorable's overhauls are definitely one of the best ones as they not
only cover the most notable NPCs of Skyrim, but also give each of them a
bit of charisma.*

### [Pandorable's NPCs - Dawnguard](https://www.nexusmods.com/skyrimspecialedition/mods/24135)

**Main files** - Pandorable's NPCs - Dawnguard SE - USSEP

### [Pandorable's NPCs - Dragonborn](https://www.nexusmods.com/skyrimspecialedition/mods/30680)

**Main files** - Pandorable's NPCs - Dragonborn SE

**Optional files** - PAN_NPCs_DB - AI Overhaul patch

**FOMOD** - `Alternative for Fanari-Strong-Voice, Ralis Sedarys, Captain
Veleth, Wulf Wild-Blood, USSEP`.

### [Pandorable's NPCs - Males](https://www.nexusmods.com/skyrimspecialedition/mods/42043)

**Main files** - PAN_NPCs - Males SE

**FOMOD** - `Alternative for Savos, Cicero, Larak, Madanach, USSEP`.

**Optional files** - PAN_NPCs Males - AI Overhaul patch

### [Pandorable's NPCs - Males 2](https://www.nexusmods.com/skyrimspecialedition/mods/50617)

**Main files** - PAN_NPCs - Males 2 SE

**FOMOD** - `Alternative for Borkul the Beast, alternative 2 for Chief
Burguk, alternative for Chief Mauhulakh, alternative 1 for Athis and Skjor, alternative 2 for
Vilkas and Farkas, alternative for Falion, Erik The Slayer, Unmid
Snow-Shod, USSEP`.

**Optional files** - PAN_NPCs Males 2 - AI Overhaul patch

### [Northbourne NPCs of the Rift](https://www.nexusmods.com/skyrimspecialedition/mods/42349)

**Main files** - Northbourne NPCs of The Rift - Full Version

**Hide facegen files** - Hide `000371d7` and `0001541b` files.

*Another newest NPC overhaul series, which I like the most right now,
because it has high poly faces and almost each of those looks diverse.*

### [Northbourne NPCs of Winterhold](https://www.nexusmods.com/skyrimspecialedition/mods/43413)

**Main files** - Northbourne NPCs of Winterhold Full Version

**Hide facegen files** - Hide `0001c19f` files.

### [Northbourne NPCs of Haafingar](https://www.nexusmods.com/skyrimspecialedition/mods/48481)

**Main files** - Northbourne NPCs of Haafingar

**Hide facegen files** - Hide `0001326a` files.

### [The Ordinary Women](https://www.nexusmods.com/skyrimspecialedition/mods/12376)

**Main files** - The Ordinary Women

**FOMOD** - `USSEP`.

**Hide facegen files** - Hide `00014121` files.

*Definitely the most immersive looks for women of Skyrim in all Nexus,
which slightly outshine blocky vanilla faces.*

### [Northbourne NPCs of Falkreath Hold](https://www.nexusmods.com/skyrimspecialedition/mods/37528)

**Main files** - Northbourne NPCs of Falkreath Hold - Full Version

**Hide facegen files** - Hide `0001bdb1` files.

### [Northbourne NPCs of Whiterun Hold](https://www.nexusmods.com/skyrimspecialedition/mods/35404)

**Main files** - Northbourne NPCs of Whiterun Hold - Full Version

**Hide facegen files** - Hide `0001a694, 0001a692, 0001a6d7, 0001a6d5,
000a2c8e, 00013478` files.  

### [Kalilies NPCs](https://www.nexusmods.com/skyrimspecialedition/mods/30247)

**Main files** - Kalilies NPCs

**FOMOD** - `vanilla, no warpaint for Mena and Rhiada`.

**Hide facegen files** - Hide `00013273` files.

*Something of a mix between Pandorable's NPCs and The Ordinary Women,
which covers NPCs that those two mods aren't touching and a little bit
more.* 

### [Pandorable's Black-Briar Ladies](https://www.nexusmods.com/skyrimspecialedition/mods/33731)

**Main files** - Pandorable's Black-Briar Ladies

**Optional files** - Ingun optional eyes

**Merge** - merge both files.

**Optional files** - AI Overhaul patch

### [Refined Volkihars](https://www.nexusmods.com/skyrimspecialedition/mods/35892)

**Main files** - Refined Volkihars SSE - The Fangs Update

**Optional files** - Cured Serana Patch **(don’t enable this, just
install)**

**FOMOD** - `vanilla or UNP, orange eyes for all, fangs`.

*In my opinion, the best Volkihar family overhaul, because they are so
much better than vanilla ones, but they still follow a vanilla
aesthetic.*

You will need to enable the patch only after you cure Serana to make
her look like a human.

### [Hood Plus Hair for Refined Volkihars Serana](https://www.nexusmods.com/skyrimspecialedition/mods/52610)

**Main files** - Hood Plus Hair for Refined Volkihars Serana

*A present for Serana to make her hair visible, when she wears her hood.*

And now there will be many, many patches for our mod overhauls and the
mod *AI Overhaul* (which is dope by the way). I don’t know why, but
someone in Bethesda has thought that it would be a good idea that AI
data and character’s appearance data should be included in one record.
Thank Todd for that.

### [Updated High Poly Expressive NPCs - AI Overhaul Patch](https://www.nexusmods.com/skyrimspecialedition/mods/54830)

**Main files** - AI Overhaul - High Poly Expressive NPCs Patch

### [Shield Sisters Re-Imagined - AI Overhaul Patch](https://www.nexusmods.com/skyrimspecialedition/mods/44263)

**Main files** - Shield Sisters Re-Imagined - AI Overhaul Patch

### [Updated USSEP - Pandorable's NPC Overhauls - AI Overhaul Patches' Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/53197)

**Main files** - USSEP - Pandorable's NPCs - Dawnguard - AI Overhaul
Patch

**Main files** - Pandorable's NPCs - Males - AI Overhaul Patch

**Main files** - Pandorable's NPCs - Males 2 - AI Overhaul Patch

### [USSEP - Northbourne NPCs - AI Overhaul Patches' Compendium](https://www.nexusmods.com/skyrimspecialedition/mods/45620)

**Main files** - USSEP - Northbourne NPCs of the Rift - AI Overhaul
Patch

**Main files** - USSEP - Northbourne NPCs of the Winterhold - AI
Overhaul Patch

**Main files** - USSEP - Northbourne NPCs of Haafingar - AI Overhaul
Patch

**Main files** - USSEP - Northbourne NPCs of Falkreath Hold - AI
Overhaul Patch

**Main files** - USSEP - Northbourne NPCs of Whiterun Hold - AI Overhaul
Patch

### [USSEP - The Ordinary Women - AI Overhaul Patch](https://www.nexusmods.com/skyrimspecialedition/mods/41371)

**Main files** - USSEP - The Ordinary Women - AI Overhaul Patch

### [Updated Kalilies NPCs - AI Overhaul Patch](https://www.nexusmods.com/skyrimspecialedition/mods/53322)

**Main files** - AI Overhaul - Kalilies NPCs Patch

When each patch is downloaded and installed, we should place them after all NPC overhauls in our mod order. Moving on the left side doesn’t matter for patches, 
but it is just common practice to keep everything sorted and organized like it should be.
Use the picture below if you have troubles figuring order on your own.

<p align="center">
    <img width="35%" src="https://user-images.githubusercontent.com/37147270/138613674-78c993d7-3f9a-40b3-8331-66797ce65fdc.png" /> 
</p>

---

## Salt & Wind Hair Retextures

Now we will make our hair mods (and some of our overhauled NPCs’ hairs)
blend a little bit better with vanilla ones.

Create a separator and name it `SALT & WIND HAIR RETEXTURES` and place
it directly below the *NPC OVERHAULS* separator (and its mods). Change
its colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

### [KS Hairdos 1.7 - Salt and Wind](https://www.nexusmods.com/skyrimspecialedition/mods/44975)

**Miscellaneous files** - Cuyima Interesting NPCs - Salt and Wind

**Main files** - KS Hairdos 1.7 - Salt and Wind

**Miscellaneous files** - KS Hairdos SMP - Salt and Wind

**Miscellaneous files** - Pandorable's NPCs - Salt and Wind

**Miscellaneous files** - Pandorable's NPCs DG - Salt and Wind

**Miscellaneous files** - Pandorable's NPCs DB - Salt and Wind

**Miscellaneous files** - The Ordinary Women - Salt and Wind

### [Salt and Wind - Rough Hair for Apachii Sky Hair](https://www.nexusmods.com/skyrimspecialedition/mods/16909)

**Main files** - Salt and Wind - ApachiiSkyHair SE v1.6 Retexture

### [Pandorable's Males - Salt and Wind Retexture](https://www.nexusmods.com/skyrimspecialedition/mods/44336)

**Main files** - Pandorable's Males - Salt and Wind

### [Kalilies NPCs - Salt and Wind Retexture](https://www.nexusmods.com/skyrimspecialedition/mods/44335)

**Main files** - Kalilies NPCs - Salt and Wind

---

## Literally Unplayable

Briefly, mods we are going to install are going to help us mask head parts from mods we have installed before 
not to mess up with our game. How can they mess up the game? For instance, just by cluttering up your Racemenu.
And making your hair dissapear or making even more problems if you have used an appearance asset from the mod you weren't supposed to and then removed it. 
Also do you remember the mod Ordinary Women mod we have talked about and how its head parts could have crashed the game?
So guess what will happen if you equip that head part to your character.

Create a separator and name it `LITERALLY UNPLAYABLE` and place
it directly below the *SALT & WIND HAIR RETEXTURES* separator (and its mods). Change
its colour, so that it won't be the same as TPF's ones.

### [Literally Unplayable - Remove Not Needed Head Parts from Character Creation](https://www.nexusmods.com/skyrimspecialedition/mods/54135)

**Main files** - Literally Unplayable - Bruma Patch

**Main files** - Literally Unplayable - The Forgotten City Patch

**Main files** - Literally Unplayable - Inigo Patch

**Main files** - Literally Unplayable - High Poly Inigo Patch

**Main files** - Literally Unplayable - Kaidan Patch

**Main files** - Literally Unplayable - Shirley Patch

**Main files** - Literally Unplayable - Cuyima's 3DNPC Patch

**Main files** - Literally Unplayable - Shield Sisters Re-Imagined Patch

---

## Final Patches

Create a separator and name it `TPF DRAGON’S EDITION - FINAL PATCHES`
and place it directly below the *SALT & WIND HAIR RETEXTURES* separator
(and its mods). Change its colour, so that it won't be the same as TPF's
ones.

I have decided to make patches modular, so it is faster and easier for
ME to check things inside and make needed changes. As mentioned before, that doesn't mean you can suddenly grab whichever patch you want from here and delete other ones.

### [TPF Dragon’s Edition - Patches](https://www.nexusmods.com/skyrimspecialedition/mods/51973)

**Main files** - TPF Dragon’s Edition - Final Patches

---

## Alternate Start

Create a separator and name it `ALTERNATE START` and place it directly
below the *TPF DRAGON’S EDITION - FINAL PATCHES* separator (and its
mods). Change its colour, so that it won't be the same as TPF's ones.

### [Ralof or Hadvar](https://www.nexusmods.com/skyrimspecialedition/mods/14553)

**Main files** - Ralof or Hadvar (saved in form 44)

*Skips the carriage drive and makes us enter right into Helgen’s Keep
with Ralof or Hadvar. In some way it isn't an alternate start, but at
the same time it is. What matters is this mod’s simplicity, which allows
us to jump right into the action.*

---

## Patcher Output

Create a separator and name it `TPF DRAGON’S EDITION - PATCHER OUTPUT`
and place it directly below the *PATCHER OUTPUT* separator (and its
outputs). Change its colour, so that it won't be the same as TPF's ones.

All of the following mods in this category will be placed under this
separator in the same order.

After enabling these outputs, disable TPF’s outputs.

### [TPF Dragon’s Edition - Outputs](https://www.nexusmods.com/skyrimspecialedition/mods/51973)

**Main files** - TPF Dragon’s Edition - Nemesis Output

**Main files** - TPF Dragon’s Edition - Terrain LOD

**Main files** - TPF Dragon’s Edition - Texgen Output

**Main files** - TPF Dragon’s Edition - DynDOLOD Output

(don’t forget to put Solstheim Ice Piles Fix after my DynDOLOD’s output in both mod (just for clarity) and load order)

**Main files** - TPF Dragon’s Edition - Occlusion

---

## Preparations

And finally it is almost the end of the guide. Only some things to do,
so let’s get it done.

At first, we will need to reinstall some of TPF mods to leave TPF as
clean as we can and to get patches we need.

Open *Fixes* separator of the TPF, find the mod *NARC Remade - No
Animals Report Crimes*, right click on it and press *Reinstall Mod*,
rename the mod to `NARC Remade - No Animals Report Crimes - TPF Dragon’s
Edition`, then in FOMOD choose core file NARC with patches for Bruma,
Darkend, The Forgotten City and The Gray Cowl of Nocturnal, put the mod
right after the mod from TPF and activate it.

The same process must be done with:

-   *Common Marker Add-On Project (CoMAP)* under _INTERFACE_ separator - `CoMAP 1.5.97 (Pre-AE), CoMAP Config Pack, Obscured Undiscovered HUD Markers - Hollow Diamond, Hidden Until Discovered, Jorrvaskr Map Marker, Wyrmstooth Travel Marker Tweaks` - then change the mod's INI to TPF's default ones;

    - bObscuredUndiscovered=1
    - fMarkerScale=0.75
    - bObscuredUndiscovered=1

-   *Fixed Mesh Lightning* in *GRAPHICS BASELINE* separator - TPF's
    patches [(look
    here)](https://thephoenixflavour.com/tpf/mod-installation/graphics-baseline/#fomod-instructions-2)
    and `More Growable Plants, flora for Beyond Skyrim - Bruma, Unique Flowers and
    Plants, 3D Mountain Flowers, flora for Bruma, ice for Bruma, creatures for Bruma, Grahl`;
    
 -   Now hide `JuniperBush.nif` and `SloeBush.nif` in Official Unique Flowers and Plants from the _Exteriors_ section of the add-on by right-clicking
the mod, then choosing the _Conflicts_ tab, selecting two files on the
_Winning file conflicts_ section, right-clicking on them and choosing
_Hide_. Then go to Cathedral - 3D Mountain Flowers (from the same section) and hide any file, which overwrites _Fixed Mesh Lightning_ by
right-clicking the mod, then choosing the *Conflicts* tab, selecting all
the files on the *Winning file conflicts* section, where overwritten mod
includes *Fixed Mesh Lightning*, right-clicking on them and choosing
*Hide*. Do the same for More Growable Plants from the add-on's _Miscellaneous_ section.

-   *Lanterns of Skyrim II* under *LIGHTNING* separator - `SMIM and Bruma`;

-   [*Enhanced Blood Textures*](https://www.nexusmods.com/skyrimspecialedition/mods/2357) under *VISUAL FX* separator;

    > This time you will need to download completely different version of the mod, but after installing it put it also after the mod from TPF.
    - **Miscellaneous files** - 4.0 BETA 4
    - **Rename** - Rename it to `Enhanced Blood Textures - TPF Dragon’s Edition` to install it as a separate mod.
    - **FOMOD** – `SPID Compatible, Reduced Splatter Size, Reduced Wound Size, Reduced Res / Default Color` two times.
    - **Disable** - disable _Enhanced Blood Textures_ mod in the _VISUAL FX_ separator of TPF.
    - *New beta version of the mod is going to help us resolve weird blood sqare effect, which sometimes appear, when blood is on a surface.*

-   _Frozen Electrocuted Combustion_ in _VISUAL FX_ separator;

    - This time you will need just to disable the mod and its settings loader. I don't like the idea of more gore in Skyrim overall. 
    It would fit Fallout franchise, but definitely not Elder Scrolls. In my opinion, Skyrim is more of a fairy tale. If you leave this mod enabled, that is **on you** to check
    for any conflicts and errors associated with it.

-   *Particle Lights For ENB - Undead Creatures* under *CREATURES* -
    `Default undead eyes, weaker lightning for ghosts, a patch for
    Cannibal Draugr, blue skulls, Solstheim version of the patch`;
    
-   *Skeleton Replacer HD - Patches* under *CREATURES* -
    `MajesticMountains, NordicRuinsCandlesEnbLight, UniqueSkullsPotema, ToolsOfKagrenac`;

-   *Simple Children - Patches* under *APPEARANCE* - `Bruma, Helgen Reborn,
    Interesting NPCs, Moon and Star, The Forgotten City, Wyrmstooth,
    Adopt Aventus Aretino + USSEP`;

-   *Misc. College of Winterhold Tweaks* under *IMPROVED VANILLA QUESTS* -
    TPFs patches [(look
    here)](https://thephoenixflavour.com/tpf/mod-installation/improved-vanilla-quests/#fomod-instructions-4)
    except `Scheduled Savos, A Wizard’s Walk, Erratum Etc.`, which
    aren’t chosen by FOMOD too (just for you to be sure that is
    correct), and you should make sure that `Obscure’s College of
    Winterhold Add-on, Interesting NPCs Add-on`, `None` for *The Early
    Elementalist* are chosen. Then disable the original Misc. College
    of Winterhold Tweaks.

Then you will need to redownload one mod and to add another two.

### [Simple Player Homes Improvements](https://www.nexusmods.com/skyrimspecialedition/mods/37236)

**Main files** - Simple Home Improvements AIO (Proudspire 4 Beds)

*Because we want more places for our many children to sleep, duh.*

Rename it to `Simple Player Homes Improvements - TPF Dragon’s Edition`
right when you are installing the mod. Put it after Simple Player Homes
Improvements in the _MISCELLANEOUS_ section.

### [Relighting Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/8586)

**Miscellaneous files** - Relighting Skyrim SSE with Window Shadows v2.0.0WS

*Because I prefer the older TPF's lightning mod at the moment.*

Put it after _Interior Fog Remover_ in the _LIGHTNING_ section. Then disable _Window Shadows RT_ mod in the same section.

After that is done, click anywhere in the load order panel and select
*Enable all*. Then...

### [TPF Dragon’s Edition - Load Order](https://www.nexusmods.com/skyrimspecialedition/mods/51973)

**Main files** - Load Order

I hope you remember what to do with this. If no - open the archive and
extract the _loadorder.txt_ to _Mod Organizer 2\profiles\The Phoenix
Flavour - Dragon’s Edition_.

If you are using Blade and Bunt - Vanilla Difficulty Modifiers, manually move its plugin on the right side of MO2 right after Blade and Blunt - A Combat Overhaul's plugin _BladeAndBlunt.esp_.

---

## Configurations

And now we are ready to jump into the game, but don’t do it right away.

At the beginning, don’t be scared when you see that your character’s
hair and/or beard isn't right. Do you remember us installing High Poly
Head and its hair (and beard) variations, right? Now we need to
actually activate our high poly head in Racemenu and then our hair will
look fine. Also choose a beard from High Poly Head and it will look good
if that is needed. If you want to use hair with physics for men, you will find instructions on how to get them a bit later.

<p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/37147270/142765555-8a1712fb-56a2-4cbd-b3a1-0cccff838d12.png" /> 
</p>

Then find the *Weapons* category and change settings to the same ones
you see below.

<p align="center">
    <img width="50%" src="https://user-images.githubusercontent.com/37147270/142765697-cf283484-96bd-4c45-81b7-ccb88554f523.png" /> 
</p>

After that customize your character to your heart's content.

At first, when Ralof or Hadvar frees you, don’t go anywhere right away.
Wait a bit for everything to load (wait after all messages on the top
left side of the screen disappear).

At second, remember to turn the _Depth of Field_ slider all the way down in the in-game settings _Display_ section if that wasn't done before. Then continue with configurations below.

* **Diziet’s Auto Outfits** - In configuration settings, check the option
to unset all hotkeys for this mod. The mod's main functionality doesn't even need them and it allows us to use them for different mods.
* **End Times** - Lock the slider to not be tempted to change the final
date all time. One in-game year (approximately **18 real life days**) is good enough (and even feels right somehow) as a default setting to 
do many other things in between saving the world for the first time. And don't worry - **the game won't end if you kill Alduin**. Also disable the spell
and countdown as those are pretty annoying. You can always enter into MCM again to see how much time
you have left.
* **Smart NPC Potions** - Standard potion drops aren’t affected, so set an
option to drop this mod’s potions to 0%. Change the chance of NPCs
having potions to 20% (we don’t want everyone to have those, right?) and
the number of potions to 3.
* **Werewolf Widget Control (if you are using the mod from the *Interface* section)** - Change opacity to 60 and
text colour to white. The timer won’t work during your first
transformation, after transforming at least once, save your game. When
you transform again, it will be at the top of the screen near your
compass.
* **Wyrmstooth** - Change starting requirements to be the quest starting after _A Blade in the Dark_ quest is done (otherwise it feels too soon for an organization to give this quest out).

Now we need to activate some of the mods to actually make them work. Close the MCM menu and the system page and do this:

* **Animated Shouts** - Press your right *Alt* key.
* **Look What You See** - Press your *V* key.

If you don't care about points below, feel free to skip. I **definitely recommend** you to check the one about Helgen Reborn book and being neutral during the war. Maybe about fast travelling too, so you won't ask me about that in the support channels. 
So about these things for you to know about:

* **About the option to remove your tail** - It is weird, but you will actually need to equip another tail to get rid from... "them both". To get the tail, open your inventory and in misc item section find an item called _AddItemMenu_ and click on it. Another menu with 4 items will pop up. Grab an item with a search option. Then open your inventory and use the item with the search option. Type `tail` in AddItemMenu's searcher. Choose the mod's plugin and grab your tail. Then equip it like gear and your tail will be gone.
* **About hair with physics for men** - You will need to use AddItemMenu again, but this time type the word `hair`.
* **TK Dodge RE** - _Mouse 3_ button is chosen by default for dodging. Feel free to change that by using instructions [here](#tk-dodge-re).
* **About fast travelling (if you are using the *Interface* section)** - By default fast travel is disabled, because it becomes much more interesting that way (you travel and discover much more) and there are plenty of ways to travel around - as in vanilla (horses, ferry, boats), paragliding, spells and another mean, which is tied to a quest (don't want to spoil that). If you still aren't sold, feel free to reenable it by disabling _Disable Fast Travel SKSE - No Janky Map UI_ mod under the _Interface_ separator.
* **About being neutral during the war** - There will be a note in Dragonseach about neutrality in war. Pick it up only if you want to be neutral during the war. Like before, more information about that can be found [here](#gameplay-guide).

And just wanted to add some info about two important things. Helgen Reborn book in your inventory can be read **only** after 5 in-game days after you have finished the main quest *Unbound*. If you want to learn more, go [here](#gameplay-guide). Also remember to unhide the quest through _Hide Your Quests_ before doing it if you have decided to hide it before.
There will be a note in Dragonseach about neutrality in war. Pick it up only if you want to be neutral during the war. Like before, more information about that can be found [here](#gameplay-guide).

At last, I recommend you to go through [here](CHANGELOG.md) to see if you didn’t miss any important updates.

---

## Thank You

That’s all, folks! You are set to traverse into another modded world of Skyrim.

If you have any questions following the add-on's instructions or if you find a typo or any other mistake in the documentation, 
feel free to report in [TPF Discord server](https://discord.gg/tpf)'s _#tpf-addons-support_ channel. If you have experienced a bug during your walkthrough, jump in [*Bugs*](DOCUMENTATION.md#bugs) section first.

If you want to help me, don't forget to endorse the add-on’s page on Nexus and write something positive for me to read (I am happy to hear from people in Discord too). 
If you want to help even more, you can donate to me (via PayPal) by pressing [here](https://www.paypal.com/donate?hosted_button_id=9K4MGQC23DRYL).

I will post about updates for the add-on in _#the-addons-updates_ channel.

If you are interested in changing TPF’s default ENB to what I use
personally or just to learn about my preference in ENBs, continue with the [ENB](#enb) section.

If you want to learn more about what the add-on offers and just some additional information, check [Gameplay Guide](#gameplay-guide). 

If you would like to make any recommendations after looking into what the add-on has to offer or to give me an advice, 
please use Posts feature on Nexus or use _#tpf-addons-feedback_. Suggestions on how to improve the documentation are also welcome on GitHub. 

---

## ENB

I love colours and to actually see where I am going, when playing the
game.

Some time ago TPF by default used _Rudy ENB_, which details were great,
but lightning left much to be desired. Like you can see in the
screenshot, if there is no light source near, we are in some kind of a
void of darkness, which troubles us pretty much everywhere. In my
opinion, that isn’t right at all. Do you sit at home with one little
light on and don’t see anything else around you? No, so this isn’t the
right ENB for us.

<p align="center">
    <img src="https://user-images.githubusercontent.com/37147270/130332396-e3a03b41-10cb-4075-93a3-13ec316b3301.png" /> 
</p>

Now as default TPF uses Serio’s ENB, which allows users with low end PCs
to use much needed features of ENB and make lightning to be a bit
better, but at the cost of removing more consuming features and
sometimes making things look too yellow for my taste.

At the moment I am using Silent Horizons ENB, which actually helps very
much with the lightning issue, and makes things look crisp and full with
colours. Another positive moment is that it almost doesn’t need any kind
of adjustments for TPF weather or any other mods, so we just need to
change ENB files and add a good addition for it.

![image](https://user-images.githubusercontent.com/37147270/142897329-c4888549-e5ee-49d8-a909-306e3e83a03a.png)

![image](https://user-images.githubusercontent.com/37147270/143310015-d12a706e-b3a4-4e3f-9de8-9eccd7bebade.png)

![image](https://user-images.githubusercontent.com/37147270/142898398-4b2151b2-205a-4c16-a9a3-403839df8a68.png)

![image](https://user-images.githubusercontent.com/37147270/142898656-c631922a-ebca-4c40-becc-3d8c4451e3af.png)

![image](https://user-images.githubusercontent.com/37147270/142898876-87a17ba5-6749-4563-8b76-1a6b60be3de2.png)

![image](https://user-images.githubusercontent.com/37147270/142899023-3f94c86a-6b34-4601-913b-a4d896b8f5cd.png)

![image](https://user-images.githubusercontent.com/37147270/142899173-7060a0c3-aa65-446a-a1ef-0481502ed688.png)
_(1.11. v. of The Phoenix Flavour - Dragon's Edition)_

---

> Wabbajack users have their ENB set up already, so you can skip the next part of this section and go right to the Gameplay Guide if you wish. 

### [Silent Horizons ENB](https://www.nexusmods.com/skyrimspecialedition/mods/21543)

**Main files** - D) Silent Horizons ENB for Cathedral Weathers

**Optional files** - Silent Horizons - Solar Cleaner

Put *Silent Horizons ENB Addon - Solar Cleaner* right at the start of
the add-on’s _Exteriors_ section in your mod order and put it right under
*Reasonable Quest Rewards - Dark Brotherhood.esp* in your plugins’ load order. Then
extract the main file. Open the optional folder, then depth of field
configuration folder. Choose your favourite depth of field settings with
the help of the photos you can find in the folder. I prefer the extra
light one. Open the folder of your choice, copy the folder, which is
inside, go back to the beginning and open *Silent Horizon 7.1 Cathedral
Weathers* folder, paste your chosen folder here and confirm the
override.

### [Viven Rain for ENB](https://www.nexusmods.com/skyrimspecialedition/mods/42629)

**Main files** - Viven Rain for ENB

The mod, which changes rain for TPF can be used for all ENBs. Manually download the main file, drop the _HD_ folder's content inside Silent Horizons _enbseries_ folder and 
confirm overwrite.
Then open `enbseries.ini` file and change the following lines under [RAIN] separator:

- IgnoreWeatherSystem=true
- Enable=true
- EnableSupersampling=true
- UseOriginalTexture=false
- MotionStretch=0.52
- MotionTransparency=0.25
- RefractionFactor=0.27
- MotionBluriness=0.32
- BrightnessDawn=1.5
- BrightnessSunrise=1.5
- BrightnessDay=1.5
- BrightnessSunset=1.5
- BrightnessDusk=1.5
- BrightnessNight=1.5
- BrightnessInteriorDay=1.0
- BrightnessInteriorNight=1.0

Save changes to the file.

Now open `enblocal.ini` file in the folder, change input commands to be as
the some ones as in TPF:

-   KeyCombination=0
-   KeyUseEffect=121
-   KeyFPSLimit=0
-   KeyShowFPS=118
-   KeyScreenshot=0
-   KeyEditor=122
-   KeyDof=0

Save changes to the file.

> Some users maybe have installed TPF's modpack and now want to follow my add-on manually. In that scenario, you don't have a tool called ENB Man, which is used in the next paragraph. Just skip it. Do the following - remove _enbseries_, _enbcache_ folders, _enbseries.ini_ and _enblocal.ini_ from your stock game folder, then drop the same files from our ENB folder inside.

Open *ENB Man*, click the arrow under *Presets* and select *Blank
preset*, enter a name for the new preset – `Silent Horizons ENB for
Cathedral Weathers 7.1.` Click the green checkmark to confirm.
Drag-and-drop all files from the *Silent Horizon 7.1 Cathedral Weathers*
folder into ENB Man, always choose *No* if you are asked to add palettes
to ENB Man. Then click the gears icon under *Global Settings*, disable
the checkmark near *enblocal.ini*. Then click the green checkmark button
(if you want to go back to TPF’s default ENB, you will need to enable
*enblocal.ini* again). Then click on another green checkmark at the
bottom of the ENB Man window to install the preset.

In the game you should also adjust the brightness settings of ENB for you to see more things at night while exploring outside and 
to make interiors a bit more darker for imersiveness. If you don't want to do that, you are free to skip the next paragraph.

Right at the menu of the game press _F11_ on your keyboard to open the ENB settings. In _Shader Parameters_ open _ENBEFFECT.FX_ section and 
find _HDR COLOR GRADING_ settings. Change _Night - Exposure (F-Stops)_ to `-0.3` and _Interior - Exposure (F-Stops)_ to `-2.5` and then press _SAVE CONFIGURATION_ and _APPLY CHANGES_ at the top left side of the ENB settings menu.

That’s all, enjoy your fancy ENB now. Of course, you can also continue
with the *GAMEPLAY GUIDE* section if you are interested in
how to start some newly added quests.

---

## Gameplay Guide

This section is mainly used to inform people about what they can expect from the add-on overall. Of course, some of you just went through the good, old manual way through all the documentation, but maybe you have forgotten about something, or some of you set up the add-on by using Wabbajack and now have no idea what possibilities await you. I consider this section as **one big spoiler** for some of the content added and so you have been warned.

At first, some juicy tips for peeps, who went right here after mingling with the add-on:

* Be sure to do at least half of the main quest series as some added quests are tied to it (more information later).
* For people, who would want to adopt children and live with them (and/or with your spouse) not in vanilla homes, 
there will be a neat spell book waiting for you somewhere around Riverwood.
* And another one - be sure to travel around Falkreath. Something interesting might happen.

At second, later into the game, if you are planning to use shields or two-handed weapons, I recommend you to go into the console with ~ key, 
type `showracemenu`, press *Enter* and make corrections to your gear's position using settings you can again see below. 
Don’t overdo these or animations will look funky. And for all our sakes - don't change your race, gender or name mid-game - that won't make the game happy. 
After setting up the settings, press *R* and *Enter* and you are done.

![image](https://user-images.githubusercontent.com/37147270/142766494-24c367a7-2600-4b53-aa67-f65408dfd2dd.png)

At third, look at some of these additional MCM configurations if you wish:

* **Cathedral Weather** - Feel free to enable _Seasonal Perpective_ option. It makes summers appear more warm, while making winters look more cold.
* **Cond. Expressions** - Disable out of stamina, in pain,
headache/diseased expressions. It will look odd if our character is constantly sad and in pain.
* **Hide Your Quests** - I recommend to hide right away all quests you get
right at the beginning except the main one (Unbound), because you mustn't
start Helgen Reborn quest right at the beginning (read further to learn why) and because The Sinister Seven quest isn’t the one
where you go to objective, just hide it, quest givers will look for you
when a time comes and then you can unhide it. Tried to understand how to make the quest with
Thalmor involved appear after you finish Diplomatic Immunity quest for
immersiveness, but couldn't, will look at that later, so let it be this
way - you heard about what is happening from elves when you were trying
to cross Skyrim’s border. You can do it as fast as you want, but enemies
won’t be the easiest ones to beat. I would recommend getting at least
level 15. Don't forget to unhide the quests, when you actually would want and would be able to start them.
* **MoreHUD** - No idea why, but Phoenix has disabled the appearance of information about potions, spell books etc. in her MoreHUD preset, when you move your cursor over those items. That is optional, but I would like to actually see this useful information, so let's enable it back by ticking _Show Ingredient Effects_ and _Show Other Effects_ in _Target's Data_ options.

Soon enough (or maybe not) you will get some kind of special powers. Here is a reminder on how to use them:

* **Praying** - After you pray at the shrine, you will get a power to pray everywhere, not only near shrines. Like always, when you do so, you get unique power from the deity
you were praying to, but a more unique one than those you get in vanilla. You can even take those powers further by obtaining two new perks in your Restoration or Conjuration tree. If you want to learn more, click [here](https://www.nexusmods.com/skyrimspecialedition/mods/54099). 
* **Inigo's Whistle Key** - You can issue commands to Inigo by whistling to him. This ability is introduced during his quests and will be explained in-game. 
You will need to press `,` button to use the whistle in the game.
**Dragonborn's Powers** - After finishing _The Way of the Voice_, you will unlock an interesting power, which gives you access to a completely new perk tree. 
You will be able to upgrade this power by shouting and killing dragons.
* **Skyrim's Paraglider** - If you have used one of my tips from before, you should know what this is about. Toggle paraglider by pressing your activation key (_E_ by default), while in the air. Use your shout key (_Z_ by default) to fly higher. Paraglider can be used only in the third person (mod's limitations).

About just some of interesting mods I have added:

* **About AddItemMenu item in your inventory** - If you recall, we have added a mod, which makes it possible to test all items other mods have to
offer inside their plugins. I have added it for people to know that there is an option like that and for your own testing purposes (can't decide, which armour I would like to get more, let me see and then I will reload my earlier save). I hope you won’t use it for cheating.
**About binding items** - Now you can bind not just one item to one button, but much more. If you want to learn more, click [here](https://www.nexusmods.com/skyrimspecialedition/mods/27184).
* **About forgetting your older spells** - Now you can forget spells you don't use anymore by going into the spells menu and pressing _R_ button.
* **About automatically changing outfits according to different scenarios** - _Diziet' Auto Outfits_ makes you automatically change your outfit according to different conditions, which can be configured inside the mod's MCM. For example, I use it to change my default gear to ordinary clothing with speech etc. enchantments for traders, when I am inside big cities.
* **About lockpicking** - Now you don't need to do the annoying lockpicking game anymore. Now your actual lockpicking skill is used to pick a lock, which make the skill much more useful too. Locks will break according to your skill too.
* **About reading** - Now you will get experience boost to your leveling speed in a skill, which you have read about. 
* **About different coins** - Now there are much more different coins around Skyrim, which will then be converted to their value in septims, when you pick them up.
* **About bribing** - Now it depends on our speech skill too. Be prepared to actually pay if you aren't talkative enough. 
* **About stealing** - Now you need to be crouched to steal items, which aren't the ones in containers. Finally I won't steal something by accident.
* **About knocking** - Now you can knock on locked doors by activating them. Good for roleplaying and also useful.
* **About Clairvoyance** - Now it is much more useful overall. Just try it out (be sure that you have an active quest in your journal).
* **About being underwater** - Now you cee your oxygen meter while underwater, so you will know how much time you have before comitting to drowning.
* **About being neutral during the Civil War** - Now you can become Thane of Eastmarch without licking Ulfric's boots (that means getting Hjerim, Calder the Housecarl, unblocking Korvanjund and much more). If you want to learn more, click [here](https://www.nexusmods.com/skyrimspecialedition/mods/21176).
* **About Aela** - Now Aela in a way is much more unique than other followers. Pick her on a tough adventure to learn how.
* **About werewolves** - Now there are much more of them than in vanilla Skyrim. And be accurate as now there is another way of becoming a werewolf, which you will maybe discover after fighting with them.
* **About sun and being a vampire** - Now you can be safe from sun the same way as Serana by wearing any kind of head gear on you (circlets don't count).
* **About College of Winterhold** - Now you will actually need magic to beat College of Winterhold. You have been warned. Conjured minions, enhanced weapons, illusion, of course, destruction magic, shouts. Good, old steel isn't as reliable now.
* **About getting armored pants** - You will be able to get these in exchange for their counterparts (heavy armors) in Skyrim. Just use any forge for that.
* **About cleaning up your mess** - Now if you have accidentally Fus Ro Dah'ed the Jarl's palace, find a broom and activate it in your inventory.
* **About Lydia** - If Lydia is too noisy for you, feel free to change her comment frequency in _Improved Follower Dialogue_ MCM.
* **About Cured Serana Patch** - If you cure Serana from her vampirism in the future, remember to save the game, close it and then in MO2 enable the patch, which you will be able to find inside the _NPC Overhauls_ separator. Then you can safely continue the game and you will see that Serana actually looks like human now.
* **About your character's light adjustments** - You will need to use _AddItemMenu_ again, but this time type the word `light`. _Character Light_ allows use to make better screenshots if we want lightning of our character to be a bit different and can also be used in an ordinary gameplay if you wish as the mod doesn't use scripts. It works even on followers, but then you should give them the corresponding NPC lightning item.

And now just a little heads up and how and when and how you should start newly
added quests. They can be split between early
and mid game and late game ones, because their difficulty slightly
differs.

#### Early and Mid Game Quests

* **Winterhold Deep Sea Ruins** - Can be started any time by going northeast
from Winterhold. A journal can be found there in small ruins, which will
point you to the location with a ship marker. Should be done without a
follower.
* **Clockwork** - Automatically after reaching level 5. Without a follower.
* **Beyond Skyrim - Bruma** - Can be started any time in *Pale Pass* (will be
marked as two rocks together) southeast of Helgen.
* **Moonpath to Elsweyr** - Can be started any time in Bruma’s *Greenwood*,
the southernmost point of County Bruma.
* **Moon and Star** - Automatically after finishing the main quest *The* *Way
of the Voice.*
* **Carved Bink** - After reaching level 10 in *Abandoned Grotto* west of Lost
Knife Hideout.
* **Project AHO** - After reaching level 15, head to Braidwood Inn (located at
Kynesgrove) and talk to the innkeeper. Without a follower.
* **The Wheels of Lull** - Automatically after reaching level 20, can be
finished after reaching level 35.
* **Helgen Reborn** - **Must** be started after 5 days after you have finished the
main quest *Unbound*. Recommended to be started at level 20. Read the
book *Helgen Reborn Guide* in your inventory to start the quest.
* **The Tools of Kagrenac** - Join College of Winterhold and finish the
side questline *Arniel’s Endeavor*. You’ll also need to have finished
*The Way of the Voice*. A couple of days after you completed *Arniel’s
Endeavor* and claimed _Keening_, the quest will start automatically. Make
sure you have Keening in your inventory, it will turn into a quest item
when the mod starts.
* **The Gray Cowl of Nocturnal** - After reaching level 20 and after
pickpocketing or stealing anything. Level 30-35 is recommended, for
thief characters (sneaking and pickpocketing).

#### Late Game Quests

* **Darkend** - Can be started any time in *Voyager's End* north of Ysgramor's
Tomb. While generic enemies can be not as tough, the bosses will kick your ass.
At least level 15 is recommended from the author, I recommend at least level 35 even with the patches, which nerf the bosses. Without a follower.
* **Undeath** - Automatically without anything happening after reaching level
30 (I know, not immersive, unfortunately the patch for making it start
in a better way was removed from Nexus, going to deal with that later,
the late game quest, considered you should have gotten it after one
Dragonborn quest).
* **The Forgotten City** - Automatically after reaching level 40. The story
responds to your character’s individual history, actions, so a high
level of speech skill (approximately 60) is also recommended. Enemies
will be pretty tough, but not as tough as within other late game quests.
That’s and also the immersiveness is the reason for setting this quest
requirements as high, because by default it starts at level 5. Without a
follower.
* **The Ice Blade of the Monarch** - Can be started any time in *Pilgrim's
Trench* northeast of The Tower Stone, hard mod.
* **The Tournament of the Ten Bloods** - Can be started after reading *The
Story of Lyrisius* in the Arcanaeum, hard mod.
* **Wyrmstooth** - automatically after Level 10 and after finishing the main
quest *A Blade in the Dark*. According to the official guide book, it
can be challenging even for level 70 characters. It is also recommended
to be prepared before venturing into the quest with some potions and
arrows if you are an archer.
* **The Grand Paladin** - After reading a book *The Grand Paladin* in Bards
College or Skaal's Village Great Hall and after
finishing the main quest *Dragon Rising*. Having more than 300 health is
highly recommended. PC must be able to shout, very hard mod.
* **The Final Cataclysm** - Automatically after reaching level 50 and after
finishing the main quest *The Horn of Jurgen Windcaller*. Stealth and
combat oriented character required, very hard mod. After reaching level
60, a bonus quest becomes available.

I have tried to write as little information as I could so as not to
spoil the content. Won’t tell you any details about your potential new
followers and other surprises as they should be discovered pretty easily
while exploring. I hope if you were surprised something (in a good way), this section helped to learn about that a bit more.

---

## Bugs

I am sorry if you need to use this paragraph.

You have read right at the start on the Nexus page that if something bad
happens I want a normal report, not something like *nothing is working
wtf help plz*. In my opinion, it is a fair request, so, please, try your
best to follow.

Of course, if you are reporting not an in-game bug, I am not expecting 5
sentences about that, just write what the problem is in appropriate channels. 
And if another person reported any kind of issue you have too, mention that you are having the same issue.
That is important for me, because then I will know that issue is global and maybe I will need your help to resolve it. 

Report requirements:

*   Title of the report should be made according to the problem (not
    *Issue, HELP!!!!, problem*, but something like *Aela has Black Face, Flying
    Barrel Outside Whiterun* etc.);
    
    > Of course, appliable just for Nexus reports.

*   Confirmation that you haven't modified or added anything to the add-on;
    
    > If something even hints some kind of addition, you will be asked for **YOUR** *modlist.txt* and *loadorder.txt* (Navigate to your MO2
    folder, open *profiles* folder, then to the profile with problem) 
    (**don't copy those directly to report as text**);
    
    > Nexus users should use Google Drive, text sharing service or any other tool for the task.

*   Screenshot or video of the problem if that can be done (copy and paste in the report or again
    just use any kind of picture sharing service etc.) (when the problem is
    seeable, open the console (*\~* key) and press on the
    problem to see maybe the console gives more information on the source of the issue, then take the screenshot);

*   Description of the problem (what, when, where);

*   Try to repeat the issue (go somewhere else, then do whatever you
    were doing before again for at least 3 times);

*   How to repeat the issue (remember that Skyrim is Skyrim, so if the
    issue can’t be repeated, I won’t be able to help) (if by your
    report it is understandable how to repeat the issue (in the
    example), of course, you don’t need to write the same thing
    again).

#### Example

***Black Face***

A person has sent me a screenshot of a guard with black face and I
see all the data about the guard from a console, her perfect, untouched
modlist.txt and loadorder.txt.

_Was going to Whiterun for the first time, right near the gate of the
city one of the guards has black face. Have tried to get to Whiterun
and then return, but the issue is still there._

I will try to respond as fast as I can. Please, be mindful that I have
studies, other hobbies and many other things to do and places to be.

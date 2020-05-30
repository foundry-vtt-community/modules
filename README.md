# Foundry VTT Module Repository

![CI for Modules Repo](https://github.com/foundry-vtt-community/modules/workflows/CI%20for%20Modules%20Repo/badge.svg)

Foundry modules that work across all or most systems are noted here.  These may include reskins, general improvement mods, and more.

To clone this repository, along with every module in it, use the following command:

```
git clone --recurse-submodules https://github.com/foundry-vtt-community/modules.git
```

Instead, if you'd like to clone this repository and only fetch a specific module from it, use the following commands:

```
git clone https://github.com/foundry-vtt-community/modules.git
cd modules
git submodule init
git submodule update name-of-the-module
```


Get Modules for Foundry VTT on the official site: [https://foundryvtt.com/packages/](https://foundryvtt.com/packages/)

The list below is an unofficial list of game modules.

<!--tl=2-->
<!--ts-->
   * [Foundry VTT Modules (Universal)](#foundry-vtt-modules-universal)
      * [About Time](#about-time)
      * [Actually Private Rolls](#actually-private-rolls)
      * [Always Show Notes](#always-show-notes)
      * [Babele](#babele)
      * [Background Volume](#background-volume)
      * [Better FilePicker](#better-filepicker)
      * [BubbleRolls](#bubblerolls)
      * [Bullseye](#bullseye)
      * [Calendar/Weather](#calendarweather)
      * [Chat Autoloader](#chat-autoloader)
      * [Chat Colors &amp; More](#chat-colors--more)
      * [Combat Utility Belt](#combat-utility-belt)
      * [Create Actors from Folder](#create-actors-from-folder)
      * [Cursor Hider](#cursor-hider)
      * [Deselection](#deselection)
      * [Dice Calculator](#dice-calculator)
      * [Discord Rich Presence](#discord-rich-presence)
      * [Display Mode](#display-mode)
      * [Dungeondraft Import](#dungeondraft-import)
      * [Easy Target](#easy-target)
      * [Enhanced Playlist](#enhanced-playlist)
      * [FFG Roller](#ffg-roller)
      * [Foundry Hot Seat Observer](#foundry-hot-seat-observer)
      * [Foundry Patrol](#foundry-patrol)
      * [Foundry Pin](#foundry-pin)
      * [The Furnace](#the-furnace)
      * [FX Master](#fx-master)
      * [GM Notes](#gm-notes)
      * [GM Scene Background](#gm-scene-background)
      * [Grid Scaler](#grid-scaler)
      * [Group Initiative](#group-initiative)
      * [Image Drop](#image-drop)
      * [Image Previewer](#image-previewer)
      * [Layer Hotkeys](#layer-hotkeys)
      * [Less Fog](#less-fog)
      * [Simple Dice Roller](#simple-dice-roller)
      * [Special Dice Roller](#special-dice-roller)
      * [Maestro](#maestro)
      * [Merge Walls](#merge-walls)
      * [Modbox](#modbox)
      * [Mother, May I?](#mother-may-i)
      * [No Token Animations](#no-token-animations)
      * [Permission Viewer](#permission-viewer)
      * [Pings](#pings)
      * [Playlist Import](#playlist-import)
      * [Popout!](#popout)
      * [Pointer](#pointer)
      * [Roll Table Buttons](#roll-table-buttons)
      * [Route-Finder](#route-finder)
      * [Scaled Labels](#scaled-labels)
      * [Search Anywhere](#search-anywhere)
      * [Skycons](#skycons)
      * [Speaker Stats](#speaker-stats)
      * [Squeaker](#squeaker)
      * [SVG Loader](#svg-loader)
      * [Teleport](#teleport)
      * [Theatre Inserts](#theatre-inserts)
      * [Tiles Browser](#tiles-browser)
      * [Token Mold](#token-mold)
      * [Torch](#torch)
      * [Trigger Happy](#trigger-happy)
      * [VTTA Iconizer](#vtta-iconizer)
      * [VTTA Tokenizer](#vtta-tokenizer)
      * [ZoomKey](#zoomkey)
   * [Foundry VTT Modules for 13th Age](#foundry-vtt-modules-for-13th-age)
      * [13th Age Expanded](#13th-age-expanded)
   * [Foundry VTT Modules for DnD 5E](#foundry-vtt-modules-for-dnd-5e)
      * [Better NPC Sheet 5e](#better-npc-sheet-5e)
      * [Better Rolls for 5e](#better-rolls-for-5e)
      * [Beyond 20](#beyond-20)
      * [Chat Damage Buttons](#chat-damage-buttons)
      * [Chat Damage Buttons - Beyond20 Edition](#chat-damage-buttons---beyond20-edition)
      * [Compendium Browser](#compendium-browser)
      * [Critical Fumble](#critical-fumble)
      * [D&amp;D 5e Conditions](#dd-5e-conditions)
      * [D&amp;D5e Dark Mode](#dd5e-dark-mode)
      * [Dynamic Effects](#dynamic-effects)
      * [Dynamic Items](#dynamic-items)
      * [E-Z Roller](#e-z-roller)
      * [Encounter Builder](#encounter-builder)
      * [Favourite Item Tab](#favourite-item-tab)
      * [Group Roll](#group-roll)
      * [Item Sheet Buttons](#item-sheet-buttons)
      * [Item Collection](#item-collection)
      * [Kobold Press OGL](#kobold-press-ogl)
      * [Let Me Roll That For You! (LMRTFY)](#let-me-roll-that-for-you-lmrtfy)
      * [Loot Sheet NPC 5E](#loot-sheet-npc-5e)
      * [Magic Items](#magic-items)
      * [Max Crit Damage](#max-crit-damage)
      * [Minor QOL Improvements](#minor-qol-improvements)
      * [MyBeyond-Theme](#mybeyond-theme)
      * [Obsidian Character Sheets](#obsidian-character-sheets)
      * [Pin Cushion](#pin-cushion)
      * [Polyglot](#polyglot)
      * [Roll20 Converter](#roll20-converter)
      * [Request Roll](#request-roll)
      * [Sky's 5th Edition Dungeons &amp; Dragons Sheet](#skys-5th-edition-dungeons--dragons-sheet)
      * [Stat Drawer](#stat-drawer)
      * [Summoner](#summoner)
      * [Token Info Icons](#token-info-icons)
      * [VTTA D&amp;D Beyond Integration](#vtta-dd-beyond-integration)
      * [VTTA Party](#vtta-party)
   * [Foundry VTT Modules for GURPS](#foundry-vtt-modules-for-gurps)
      * [GURPSModule](#gurpsmodule)
   * [Foundry VTT Modules for WFRP 4E](#foundry-vtt-modules-for-wfrp-4e)
      * [Arcane Marks &amp; Careers](#arcane-marks--careers)
      * [Rough Nights &amp; Hard Days](#rough-nights--hard-days)
      * [Gerwin Waffenhalter’s Magnificent Weapons Gallery](#gerwin-waffenhalters-magnificent-weapons-gallery)
   * [Foundry VTT Modules (Defunct)](#foundry-vtt-modules-defunct)
      * [Anvil Menu](#anvil-menu)
      * [Arcane Viewing (module integrated into core)](#arcane-viewing-module-integrated-into-core)
      * [Chat Damage Buttons - Better Rolls Edition](#chat-damage-buttons---better-rolls-edition)
      * [DDB Popper (use VTTA-DNDBEYOND instead)](#ddb-popper-use-vtta-dndbeyond-instead)
      * [DnD Beyond Character Importer (non-functional -- use VTTA-D&amp;D Beyond Integration instead)](#dnd-beyond-character-importer-non-functional----use-vtta-dd-beyond-integration-instead)
      * [Encumbrance Variant](#encumbrance-variant)
      * [Entity Order](#entity-order)
      * [FVTT-Party (Discontinued, see VTTA-Party for an successor)](#fvtt-party-discontinued-see-vtta-party-for-an-successor)
      * [GM Roll Message](#gm-roll-message)
      * [Infinite Folders](#infinite-folders)
      * [Journal Drag](#journal-drag)
      * [NPC Browser](#npc-browser)
      * [Polymorpher](#polymorpher)
      * [Roll20 NPC Importer, for 5e](#roll20-npc-importer-for-5e)
      * [Spell Browser](#spell-browser)
      * [SRD Bestiary Module](#srd-bestiary-module)
      * [Z Order (functionality integrated into core)](#z-order-functionality-integrated-into-core)
   * [Appendix](#appendix)
      * [Appendix A: Best Editing Practices](#appendix-a-best-editing-practices)
<!--te-->

# Foundry VTT Modules (Universal)

Foundry modules that work across all or most systems are noted here. These may include reskins, general improvement mods, and more.

## [About Time](Foundry%20VTT%20Modules%20%28Universal%29/about-time.md)
Supports a pseudo real time game clock withe events and arbitrary calendars.

## [Actually Private Rolls](Foundry%20VTT%20Modules%20%28Universal%29/Actually-Private-Rolls.md)
Hides Private GM Rolls completely rather then just obfuscating the result.

## [Always Show Notes](Foundry%20VTT%20Modules%20%28Universal%29/alwaysshownotes.md)
Sets the Display Notes toggle to true by default

## [Babele](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-babele.md)
Babele is a module for runtime translation of Compendium packs.

## [Background Volume](Foundry%20VTT%20Modules%20%28Universal%29/background-volume.md)
Background Volume is a module for setting the volume of background videos.

## [Better FilePicker](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-better-filepicker.md)
Toggle image thumbnails in the file picker. Also improves file picker visibility on small screens.

## [BubbleRolls](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-bubblerolls.md)
This module displays Actor Rolls in Chat Bubbles located on just above the Token. This module makes it easy for contributors to add templates of their own. More information on the gitlab link.

## [Bullseye](Foundry%20VTT%20Modules%20%28Universal%29/foundry-vtt-bullseye.md)
This module adds a new Bullseye Application that shows all the currently active player's selected targets in a list. Allowing easy access to select and control the tokens your players are targeting.

## [Calendar/Weather](Foundry%20VTT%20Modules%20%28Universal%29/about-time.md)
A customizable module that accurately tracks and displays dates and time.

## [Chat Autoloader](Foundry%20VTT%20Modules%20%28Universal%29/chat-autoloader.md)
This module improves loading times by only rendering the last few chat messages at page load. Older messages will automatically get rendered while scrolling to the top. (This behavior is similar to e.g. scrolling in Discords chat)

## [Chat Colors & More](Foundry%20VTT%20Modules%20%28Universal%29/chat-colors-and-more.md)
This module allows players to set custom colors for different types of chat messages (IC speech, emotes, rolls, and all other messages) in the Module Settings. Players can also specify a default chat prefix, which will be prefixed to all their chat messages that are not already commands.

## [Combat Utility Belt](Foundry%20VTT%20Modules%20%28Universal%29/master.md)
You can read more about the module in the README @ (https://github.com/death-save/combat-utility-belt/tree/master).

## [Create Actors from Folder](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-create-actors-from-folder.md)
Recursivly creates actors from images in specified folder

## [Cursor Hider](Foundry%20VTT%20Modules%20%28Universal%29/cursor-hider.md)


## [Deselection](Foundry%20VTT%20Modules%20%28Universal%29/deselection.md)
This module lets the GM deselect a token or tokens by clicking anywhere on the map.

## [Dice Calculator](Foundry%20VTT%20Modules%20%28Universal%29/foundry-vtt-dice-calculator.md)
This module turns the d20 icon near the chat prompt into a clickable link that opens up a new dice calculator dialog. The dice calculator includes buttons for dice, numbers, attributes for the selected token, and simple math. In addition, it includes support for inline dice rolls, such as `[[2d6 + @abil.str.mod]]` in chat. [Screenshot of the calculator can be found here.](https://i.imgur.com/53XmxEN.png)

## [Discord Rich Presence](Foundry%20VTT%20Modules%20%28Universal%29/Companion%20API%20%28Required%21%29.md)
Enables Discord Rich Presence and Invites for http://foundryvtt.com/

## [Display Mode](Foundry%20VTT%20Modules%20%28Universal%29/displaymode.md)
This module makes it so that when you click the anvil in the top left of the screen, the sidebar in Foundry is hidden.

## [Dungeondraft Import](Foundry%20VTT%20Modules%20%28Universal%29/Moo%20Man%237518.md)


## [Enhanced Playlist](Foundry%20VTT%20Modules%20%28Universal%29/tweakplaylist.md)
Enhancements to Foundry playlists, including making playlists visible only to the GM, and allowing for random delays and volume changes in looped sounds.

## [FFG Roller](Foundry%20VTT%20Modules%20%28Universal%29/FFG-Roller.md)
This adds a simple dice rolling window for the special dice used in Fantasy Flight Games Star Wars RPG and Genesys.

## [Foundry Hot Seat Observer](Foundry%20VTT%20Modules%20%28Universal%29/FoundryHotSeatObserver.md)


## [Foundry Patrol](Foundry%20VTT%20Modules%20%28Universal%29/foundry-patrol.md)
TLDR: Create token automated token patrols

## [The Furnace](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-module-furnace.md)
This module contains a set of features that improve the Quality of Life of the DMs and Players.

## [FX Master](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-fxmaster.md)
This module adds weather effects to choose from in the scene configuration menu. You can now have animated flying birds, bubbles, embers and clouds.

## [GM Notes](Foundry%20VTT%20Modules%20%28Universal%29/gm-notes.md)
A Foundry VTT Module to add GM-Only notes to entities (Actor, Items (including owned items), RollTable and JournalEntry). This module is system independet, but has an additional feature to easily move GM notes to or from the actors bio, items description or JournalEntrys content.

## [GM Scene Background](Foundry%20VTT%20Modules%20%28Universal%29/Link.md)
Allows GMs to set a GM-only background image.

## [Grid Scaler](Foundry%20VTT%20Modules%20%28Universal%29/scaleGrid.md)
This mod allows you to resize a grid more easily within Foundry, allowing easier map setup when a grid is uneven or unclear within a background image.

## [Group Initiative](Foundry%20VTT%20Modules%20%28Universal%29/foundry-group-initiative.md)
Allows rolling initiative once for each NPC group. Each NPC inside the group will use the same initiative result.

## [Image Drop](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-image-drop.md)
Allows dropping images from journal entries to the canvas as tiles.

## [Image Previewer](Foundry%20VTT%20Modules%20%28Universal%29/image-previewer.md)
A little app to preview images on hover in the file picker menu.

## [Layer Hotkeys](Foundry%20VTT%20Modules%20%28Universal%29/layer-hotkeys.md)
This module adds hotkeys for switching layers and the active tool in canvas.

## [Less Fog](Foundry%20VTT%20Modules%20%28Universal%29/lessfog.md)
Module to enhance visibility for the GM in Foundry VTT.

## [Simple Dice Roller](Foundry%20VTT%20Modules%20%28Universal%29/fvtt---simple-dice-roller.md)


## [Special Dice Roller](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-special-dice-roller.md)
Supports rolling dice in your chat window for various non regular dice systems:

## [Maestro](Foundry%20VTT%20Modules%20%28Universal%29/maestro.md)
Adds some sound-focused features to Foundry Virtual Tabletop!

## [Merge Walls](Foundry%20VTT%20Modules%20%28Universal%29/master.md)
This module came about after looking at walls generated in DunGen and a discussion with Atropos about how to reduce the number or walls by merging neighbouring walls. For hand drawn maps there is only a small decrease but for DunGen and maps imported from Roll20 modules there can be 30% reduction in the number of walls. The results are not too far from hand crafted wall layouts.

## [Modbox](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-modbox.md)
Adds an input box to the toolbar that applies a modifier to the next roll.

## [Mother, May I?](Foundry%20VTT%20Modules%20%28Universal%29/mother-may-i.md)
Allows trusted players to drag items and actors they own to the canvas as long as a GM is logged in.

## [No Token Animations](Foundry%20VTT%20Modules%20%28Universal%29/No%20Token%20Animations.md)
Adds an option to the settings dialog to disable token movement animations. Tokens will drop immediately instead of sliding when dragged and dropped around the map with this setting enabled.

## [Permission Viewer](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-module-permission-viewer.md)
This Foundry VTT module allows a GM to quickly share actors, journal entries, items, etc.. with their players and displays colored diamonds/squares/circles to represent which players have which access to the various Entities.

## [Pings](Foundry%20VTT%20Modules%20%28Universal%29/pings.md)


## [Playlist Import](Foundry%20VTT%20Modules%20%28Universal%29/playlist_import.md)
This module aims to simplify the process of adding multiple music tracks to Foundry VTT, doing so in a timely manner.

## [Popout!](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-module-popout.md)
This Foundry VTT module lets you pop out journal entries and actor sheets into their own windows or into separate tabs.

## [Pointer](Foundry%20VTT%20Modules%20%28Universal%29/pointer.md)
This module adds the ability for each user to show a cursor following his mouse as well as adding the option to ping a certain location.

## [Roll Table Buttons](Foundry%20VTT%20Modules%20%28Universal%29/rolltable-buttons.md)
This module adds a button to the chat controls for easier access to rolltables. Came about as a way to add critical-hit decks for players.

## [Route-Finder](Foundry%20VTT%20Modules%20%28Universal%29/foundry-vtt-pathfinding.md)
A module to find the shortest route for a token to reach a chosen point.

## [Scaled Labels](Foundry%20VTT%20Modules%20%28Universal%29/Scaled%20Labels.md)
Scale labels of rulers and token nameplates when zoomed-out.

## [Search Anywhere](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-search-anywhere.md)
A FoundryVTT Module that adds a way to quickly search for any entity by name via a handy auto-complete widget.

## [Skycons](Foundry%20VTT%20Modules%20%28Universal%29/skycons.md)
Save/restore window position whem minimizing/maximizing.

## [Speaker Stats](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-speakerstats.md)
This FoundryVTT Module will add an button to the GM toolbar that allows to GM visualize the time spoken by each user as chat message.

## [Squeaker](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-squeaker.md)
Adds settings to control sounds that trigger when a chat message is received. You can use custom sounds, disable roll sounds and enable chat sound notifications even when it's not whispered messages. Based on an original idea from @Gen Kitty (she/her). **Default settings don't change anything.**

## [SVG Loader](Foundry%20VTT%20Modules%20%28Universal%29/svg-loader.md)
This module allows to load walls, lights and sources through .svg files, provided e.g. by DungeonFog.

## [Teleport](Foundry%20VTT%20Modules%20%28Universal%29/FVTT-Teleport.md)
A module for Foundry Virtual Tabletop to teleport tokens between two points within a scene or different scenes.

## [Theatre Inserts](Foundry%20VTT%20Modules%20%28Universal%29/theatre.md)
Theatre is a mod that allows for a visual novel style RP experience for text, and text-voice hybrid games. The primary function of Theatre is to allow for graphical 'theatre-inserts' or 'standin-graphics' to appear on screen with an accompanying area for text beneath them. This follows the style of visual novels, and even provides a means to animate or decorate the text as it appears in the below box. It also provides an emote system to allow users to configure different graphics for the various emotive expressions. Most of the emotes additionally have a built in 'emote animation' that occurs when the emote is selected, which can be toggled off globally if undesired.

## [Tiles Browser](Foundry%20VTT%20Modules%20%28Universal%29/tiles-browser.md)
Adds a browser to the tiles layer to conveniently preview and then drag and drop tiles onto the scene. Providing additional features to manipulate tile rotation and size while dragging.

## [Token Mold](Foundry%20VTT%20Modules%20%28Universal%29/token-mold.md)
What is a foundry without its molds? This module provides you with a customizable mold for your Tokens.

## [Torch](Foundry%20VTT%20Modules%20%28Universal%29/torch.md)
Adds a HUD button to toggle light of a specific radius. For the dnd5e system, will also deduct torches from inventory when turned on if the Actor does not know the Light or Dancing Lights cantrips. For Dancing Lights, creates four Dancing Light tokens for the player as long as there is a GM connected.

## [Trigger Happy](Foundry%20VTT%20Modules%20%28Universal%29/fvtt-module-trigger-happy.md)
This module adds a trigger->effect system for creating triggers and automating things within a world.

## [VTTA Iconizer](Foundry%20VTT%20Modules%20%28Universal%29/VTTA%20Iconizer.md)
Iconizer watches the creation of items in your world, and tries to find a suitable icon from a pre-populated name/icon dictionary. All you need to do, is

## [VTTA Tokenizer](Foundry%20VTT%20Modules%20%28Universal%29/VTTA%20Tokenizer.md)
Tokenizer provides the user with:

## [ZoomKey](Foundry%20VTT%20Modules%20%28Universal%29/foundryvtt-zoomkey.md)
Adds hotkeys for zooming and panning on the canvas without mousewheel

# Foundry VTT Modules for 13th Age

Foundry modules that work within the 13th Age System are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, and much, much more.

## [13th Age Expanded](Foundry%20VTT%20Modules%20for%2013th%20Age/FoundryVTT-13th-Age-Expanded%29.md)
A small set of additional features for https://gitlab.com/asacolips-projects/foundry-mods/archmage/tree/master, such as adding a place to keep track of Incremental Advances

# Foundry VTT Modules for DnD 5E

Foundry modules that work within Dungeons and Dragons 5th Edition are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, and much, much more.

## [Better NPC Sheet 5e](Foundry%20VTT%20Modules%20for%20DnD%205E/BetterNPCSheet5e.md)
This module overwrites the default NPC sheet that comes shipped with the dnd5e system and brings it closer to the well known official template. It also includes functionality supporting separation of action categories (legendary actions, actions, reactions, etc.), and features the ability to expand and view the description of the ability/action in-sheet.

## [Better Rolls for 5e](Foundry%20VTT%20Modules%20for%20DnD%205E/FoundryVTT-BetterRolls5e.md)
This module modifies certain sheet functions on Foundry VTT Character sheets for D&D 5th Edition. Currently, it adds compound rolls (for attack rolls and damage rolls combined), as well as "dual rolls" for all attacks, ability checks, and saving throws, rolling 2 d20s side-by-side in a single chat message. Additionally, it allows for configurable quick rolls for each item that can show desired details & rolls of an item on the sheet whenever it's clicked. On top of all this are a few options to customize layout and enable/disable certain features of the module.

## [Beyond 20](Foundry%20VTT%20Modules%20for%20DnD%205E/Beyond20.md)
This module allows you to use and roll sheets in DnD Beyond, and have those results displayed in Foundry VTT. For more details, see Kakaroto’s module page and readme files, or the official website.

## [Chat Damage Buttons](Foundry%20VTT%20Modules%20for%20DnD%205E/foundry-vtt---chat-damage-buttons.md)
This module replaces the right-click context menu with buttons on the dice-roll chat message. This allows for quicker application of damage/healing.

## [Chat Damage Buttons - Beyond20 Edition](Foundry%20VTT%20Modules%20for%20DnD%205E/foundry-vtt-chatdamagebuttons-beyond20.md)


## [Compendium Browser](Foundry%20VTT%20Modules%20for%20DnD%205E/compendium-browser.md)
A module to easily browse and filter spells as well as npcs loaded from compendie.

## [Critical Fumble](Foundry%20VTT%20Modules%20for%20DnD%205E/critical-fumble.md)
Do you find yourself forgetting to roll on the critical hit table? The critical fumble table? Do you find yourself forgetting to roll that pesky loot table after each monster dies?

## [D&D 5e Conditions](Foundry%20VTT%20Modules%20for%20DnD%205E/conditions5e.md)
Alter the icons in the Status Effects panel of the Token Hub to reflect the standard "conditions" in D&D 5e, and repurpose the effects overlay to display whether the token is seriously wounded, unconscious, or dead.

## [D&D5e Dark Mode](Foundry%20VTT%20Modules%20for%20DnD%205E/dnd5edark-foundryvtt.md)
A dark sheet style for the default D&D5e Character and NPC sheets.

## [Dynamic Effects](Foundry%20VTT%20Modules%20for%20DnD%205E/dynamiceffects.md)


## [Dynamic Items](Foundry%20VTT%20Modules%20for%20DnD%205E/dynamicitems.md)
Dynamic items are ones that makes changes to your stats/modifiers when they are active in your inventory. This module is really intended for player characters and NPCs that have linked tokens.

## [E-Z Roller](Foundry%20VTT%20Modules%20for%20DnD%205E/ezroller.md)
Causes item cards to open in a window rather than in chat. This allows you to open the item card before your turn and also to keep your common attack open so you can roll attack on the next turn without navigating back to your inventory.

## [Encounter Builder](Foundry%20VTT%20Modules%20for%20DnD%205E/encounter-builder.md)


## [Favourite Item Tab](Foundry%20VTT%20Modules%20for%20DnD%205E/favtab.md)
Adds a Favourite tab to display a customized list of items, feats and spells. Usable with the default dnd5e Character sheet. You can add any item from the inventory, spell book or feature section of the character sheet. This module also gives access to item charges. You can add these to any item on the favourite list or remove them by changing the maximum to 0. This uses the same data that is used by Moerill#7205's adnd5e module, since this data is not supported by default.

## [Group Roll](Foundry%20VTT%20Modules%20for%20DnD%205E/grouproll.md)
Implements group ability and skill check rolls per Player's Handbook, page 175: "*If at least half the group succeeds, the whole group succeeds.*" The module also implements a house rule to use the average of 2d20 for normal skill and ability check rolls, and partially implements the D&D 5e Halfling Lucky trait. Both of these patches can be disabled in config.js. All patches rely on the included `patchClass` utility function.

## [Item Sheet Buttons](Foundry%20VTT%20Modules%20for%20DnD%205E/foundry-vtt---item-sheet-buttons.md)
This module adds item card buttons into the description of items, so that the item cards do not need to be pinged in chat. It does have the side effect of making it harder to ping item descriptions within chat.

## [Item Collection](Foundry%20VTT%20Modules%20for%20DnD%205E/itemcollection.md)
This module allows the creation of bags which can contain other items, think backpack or bag of holding. These items can be put anywhere an item can.

## [Kobold Press OGL](Foundry%20VTT%20Modules%20for%20DnD%205E/Kobold%20Press%20OGL.md)
This module adds Kobold Press OGL content sourced from the KPOGL wiki. Currently there are two compendiums, one with over 800 monsters and the other with over 500 spells.

## [Let Me Roll That For You! (LMRTFY)](Foundry%20VTT%20Modules%20for%20DnD%205E/fvtt-module-lmrtfy.md)
LMRTFY is a module to let Game Masters request rolls from their players. This can help avoid questions like

## [Loot Sheet NPC 5E](Foundry%20VTT%20Modules%20for%20DnD%205E/fvtt---loot-sheet-npc-5e.md)
This module adds an additional NPC sheet which can be used for loot containers such as chests. It also allows spells to be automatically converted into spell scrolls by dragging them onto this sheet.

## [Magic Items](Foundry%20VTT%20Modules%20for%20DnD%205E/foundryvtt-magic-items.md)
This module adds the ability to create magical items with spells or feats that belong to the item itself, such as staffs or magic wands, which will be automatically inherited from the character who owns the item.

## [Max Crit Damage](Foundry%20VTT%20Modules%20for%20DnD%205E/master.zip.md)
Deals max damage for critical hit rolls.

## [Minor QOL Improvements](Foundry%20VTT%20Modules%20for%20DnD%205E/minor-qol.md)
Link: https://gitlab.com/tposney/minor-qol

## [MyBeyond-Theme](Foundry%20VTT%20Modules%20for%20DnD%205E/MyBeyond-Theme.md)
A simple css overwrite that brings the character sheet into a DnDBeyond like style without changing the function of the character sheet.

## [Pin Cushion](Foundry%20VTT%20Modules%20for%20DnD%205E/pin-cushion.md)
Changes map pin icon selection to filepicker

## [Polyglot](Foundry%20VTT%20Modules%20for%20DnD%205E/fvtt-module-polyglot.md)
Talk to others using a language your selected character can understand and scrambles in-character text you can't understand.

## [Roll20 Converter](Foundry%20VTT%20Modules%20for%20DnD%205E/Roll20%20Converter.md)
This module is a PC application that imports most facets of a Roll 20 campaign, including scenes, walls, dynamic lighting, character sheets (D&D 5e), handouts, chat logs and more.

## [Request Roll](Foundry%20VTT%20Modules%20for%20DnD%205E/request_roll.md)
Request Roll is a module designed to help Gamemasters speed up the rolling process by requesting rolls from PCs. This can help reduce player navigation time, questions about where a roll is located, and other unforseen delays that cause chokepoitns in your game. You can select from a range of options varying from hidden rolls, where only the gm knows, to rolls with advantage or disadvantage! Consider installing this module to speed along your game!

## [Sky's 5th Edition Dungeons & Dragons Sheet](Foundry%20VTT%20Modules%20for%20DnD%205E/alt5e.md)
This module provides a variant layout of the Core 5e Character Sheet in Foundry as well as providing some upgrades to various sections of the sheet.

## [Stat Drawer](Foundry%20VTT%20Modules%20for%20DnD%205E/statdrawer.md)
A module for Foundry VTT that lets you generate ablitiy scores for characters using the "Holy Grail" method as described [here](https://www.reddit.com/r/DnD/comments/c67dft/oc_another_character_stat_generation_method_i/)!

## [Summoner](Foundry%20VTT%20Modules%20for%20DnD%205E/summoner.md)
This FoundryVTT Module adds a simple compendium pack to help with DnD5e spells that summon creatures. It is nothing fancy. My players were casting find familiar and I tried to use the npc creatures that are in the DnD5e system and it wasn't working. So all I did was create actor/player types for each creature they could summon.

## [Token Info Icons](Foundry%20VTT%20Modules%20for%20DnD%205E/fvtt---token-info-icons.md)
Simple module that displays Speed, AC, and Passive Perception on Tokens for the GM.

## [VTTA D&D Beyond Integration](Foundry%20VTT%20Modules%20for%20DnD%205E/VTTA%20D%26D%20Beyond%20Integration.md)
Foundry VTT Modules (Defunct) Foundry VTT Modules (Universal) Foundry VTT Modules for 13th Age Foundry VTT Modules for DnD 5E Foundry VTT Modules for GURPS Foundry VTT Modules for WFRP 4E README.md csplit-modules-00 csplit-modules-25 csplit-modules-35 csplit-sections-00 csplit-sections-01 csplit-sections-02 csplit-sections-03 csplit-sections-04 csplit-sections-05 csplit-sections-06 csplit-sections-07 header.md modules.md update_modules.sh By clicking an inserted button on any D&D Beyond monster's page, you can **import that monster** straight into the game, with **all stats, all actions, all attacks, reactions and legendary actions**, fully Foundry compatible and up to date to the latest changes

## [VTTA Party](Foundry%20VTT%20Modules%20for%20DnD%205E/VTTA%20Party.md)
The overview window acts intelligently to not overload you with characters and NPCs:

# Foundry VTT Modules for GURPS

Foundry modules that work within GURPS 4th Edition are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, changes to roll tables, etc.


## [GURPSModule](Foundry%20VTT%20Modules%20for%20GURPS/GURPSmodule.md)
This mod changes the foundry ruler label to print out the GURPS range modifier from the size speed and range table. There are also some chat commands to roll on rolltables for hit location (off the grand unified hit location table), range, size modifier, fear results, critical hits, malfunctions, and more. Type in !ghelp into the chat for a bit of help.

# Foundry VTT Modules for WFRP 4E
Foundry modules that work within Warhammer Fantasy Roleplay 4th Edition are noted here. These may include NPC compendiums that may be legally shared, world saves, character sheet mods, changes to roll tables, etc.

## [Arcane Marks & Careers](Foundry%20VTT%20Modules%20for%20WFRP%204E/Arcane-Marks-Careers-FVTT.md)
[This homebrew](https://drive.google.com/file/d/1uTy2r0EDMdcISFqqyxeIOSadtzz-OTAg/view) supplement I made adds Lore specific careers and marks for WFRP4e.

## [Rough Nights & Hard Days](Foundry%20VTT%20Modules%20for%20WFRP%204E/fvtt-wfrp4e-rnhd.md)


## [Gerwin Waffenhalter’s Magnificent Weapons Gallery](Foundry%20VTT%20Modules%20for%20WFRP%204E/wfrp-gwmwg.md)
This module adds the 'Slashing' weapon quality as well as the expanded weapons from [The Ratter Vol. 1 Issue 2](https://indd.adobe.com/view/763c1883-228a-455f-a115-19f4059f4589)

# Foundry VTT Modules (Defunct)

Foundry VTT modules that no longer work are noted here. Modules included here have been defunct for at least one month. This exists to help document previous work on Foundry Virtual Tabletop by the community, as well as to exist as a record for anyone who chooses to remain on a previous version of Foundry VTT.  

## [Anvil Menu](Foundry%20VTT%20Modules%20%28Defunct%29/foundry-vtt-anvil-menu.md)


## [Arcane Viewing (module integrated into core)](Foundry%20VTT%20Modules%20%28Defunct%29/Arcane%20Viewing%20%28module%20integrated%20into%20core%29.md)
Arcane Viewing adds Audio/Video conferencing support directly from within FVTT.

## [Chat Damage Buttons - Better Rolls Edition](Foundry%20VTT%20Modules%20%28Defunct%29/Better%20Rolls%20for%205e.md)
A small module to add "Apply Damage" buttons to Red Reigns Better Rolls 5e Module, based on hookings Chat Damage Buttons.

## [DDB Popper (use VTTA-DNDBEYOND instead)](Foundry%20VTT%20Modules%20%28Defunct%29/ddb-popper.md)
Opens a D&D Beyond popup for a linked actor.

## [DnD Beyond Character Importer (non-functional -- use VTTA-D&D Beyond Integration instead)](Foundry%20VTT%20Modules%20%28Defunct%29/ddb-importer.md)
This module allows you to import character data from DnD Beyond into Foundry Virtual Tabletop.

## [Encumbrance Variant](Foundry%20VTT%20Modules%20%28Defunct%29/foundry-vtt---encumbrance-variant-5e.md)
This module modifies how the encumbrance bar in the actor sheet is displayed to distinguish the different levels of encumbrance when using the variant rules in **PHB pg. 175**. It does not currently support the Powerful Build feature, as doing so would require extending the base Actor5eSheet class.

## [Entity Order](Foundry%20VTT%20Modules%20%28Defunct%29/fvtt-module-entityorder.md)
This Foundry VTT module allows you to re-order entities (Actors, Scenes, Items and Journal entries).

## [FVTT-Party (Discontinued, see VTTA-Party for an successor)](Foundry%20VTT%20Modules%20%28Defunct%29/fvtt-party.md)
This module adds a convenient button to the actor’s tab, which will track the HP, AC, and Passive Perception, Investigation, and Insight of tokens on the Canvas. Currently a WIP, and may exhibit some bugs.

## [GM Roll Message](Foundry%20VTT%20Modules%20%28Defunct%29/gmrollmessage.md)
Sends an extra public message/hint when rolling a `gmroll` or `blindroll`.

## [Infinite Folders](Foundry%20VTT%20Modules%20%28Defunct%29/fvtt-module-infinite-folders.md)
This Foundry VTT module allows you to create infinite depth of folders for Scenes, Actors, Items and Journals. No more limit to a depth of 2 folders (or none for Journal entries). This will also add a `New entity` button on folders so you can create it directly in the folder (does not work for Scenes though).

## [NPC Browser](Foundry%20VTT%20Modules%20%28Defunct%29/npc-browser.md)
This module adds a search interface for actors. This enables more comfortable browsing and searching via predefined filters like challenge rating, type or ability score.

## [Polymorpher](Foundry%20VTT%20Modules%20%28Defunct%29/polymorpher.md)
A module for Foundry VTT that lets you polymorph characters into any other character! Just drag any Actor (NPC or Character) on top of another Actor to change the later into the prior. Support dropping both from Compendium or the sidebar.

## [Roll20 NPC Importer, for 5e](Foundry%20VTT%20Modules%20%28Defunct%29/roll20npcimporter.md)
This module allows for the importing of NPCs from Roll20, through use of JSONs exported via [VTT Enhancement Suite](https://ssstormy.github.io/roll20-enhancement-suite/). This import currently only supports NPCs created in the Roll20 OGL or Shaped version sheets. This module supports the Better NPC Sheet 5e, as well as the aDnD5e sheet in tagging actor items according to abilities, reactions, legendary actions, etc. To install, first download the module, unzip it into `/public/modules`, and then restart Foundry while it is running.

## [Spell Browser](Foundry%20VTT%20Modules%20%28Defunct%29/Spell-Browser.md)
This module adds a search interface for spells. This enables more comfortable browsing and searching via predefined filters like spell level, class or damage type.

## [SRD Bestiary Module](Foundry%20VTT%20Modules%20%28Defunct%29/SRD%20Bestiary%20Module.md)
This module includes each SRD NPC in 5th edition, imported into Foundry VTT. This includes all of their features, immunities/resistances/vulnerabilities, actions, and much, much more. Other than lacking token images (token images do not appear to be part of the SRD), each NPC is built and ready for use in Foundry Virtual Tabletop. Included in the module is a folder containing each individual NPC json, in case you wish to experiment with importing them, or future updates break the NPCs in this module. These can be imported individually using the Roll20 NPC Importer, for 5e module.

## [Z Order (functionality integrated into core)](Foundry%20VTT%20Modules%20%28Defunct%29/fvtt-module-zorder.md)
This Foundry VTT module lets you send tiles to the front or the back of the scene.


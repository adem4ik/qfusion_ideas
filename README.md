# Qfusion ideas
It is ideas for <a href="https://github.com/Qfusion/qfusion">Qfusion</a> prototype game. Mostly just changes that should be done in compare with <a href="https://warsow.net">Warsow 2.1</a>.

## General gameplay
* Unlimit ammo in warmup
* Warmup similar to QW, where no damage happens, only knockbacks and hitsounds
* Remove stun
* Remove dead bodies' damage 

## Gametypes

### Duel
* 15 max ammo for EB
* 180 max ammo for LG, 60 on weapon pickup, 120 on ammo pickup

### Bomb'n'defuse
* Ammo box drops on frag
* Defuse sound as in CS

### FFA
* Quad killer becomes quad carrier, none gets the quad on self kill

### CTF
* Restore Flag-carrier's HP, only when he not gets damaged, like 1HP per 1 second
* Flag carrier indicator is visible for anyone and through the walls

## UI/HUD
* Hotkeys for the menu
* Frag stemp like in volleyball for duels/tdm, place needs more investigation
* Leader score in DM/FFA on HUD
* Trick indicator as complementation/replacement for pressed keys
* Item timers for client side demos on HUD like in WolfcamQL, so unknown timers are shown as "-" or "x"
* Transparent/grey font for the servers w/o players in the server browser
* Ingame wiki
* HUD message "press ESC to use Demo Panel" /add it to my HUD with cg_showhelp "1"
* Team mates indicators on HUD for invisible team mates
* HUD classic: move "Stunned" text higher
* HUD default: move "low ammo" text below crosshair
* UI for demolist / demoget
* Improve team info bar http://i.imgur.com/qLWy7gi.png
* ~~Limit fps in UI to 60, when player isn't connected to any server~~
* Show walljump cooldown indicator in cg_ShowPressedKeys
* Rework minimap to radar to show only a part of a map with navigation to important items (like in Xonotic)
* Show minimap in any gametype
* Show actual binds near weapon bar and pressed keys
* Show weapon icons/siluette near the weapon names in Settings - Input
* Rework scoreboard using librocket
* Rework menu after connecting to the server 

## Engine/graphics/others
* Force own model/color for non-team based gametypes demos
* Smooth transition from enemy color to gray on frag
* cg_quadqaunter, cg_followkiller for demos and TV
* Restore desktop resolution after alt+tab from fullscreen
* Weapon placement indicators on missing weapon bind key press (like in Xonotic)
* Console transparency
* Dust from jumps including on jumppads
* Player view beam in demos/TV (like in CS:GO)
* "timescale -X.X" for the back rewind
* Particles from enemy model coming after hit
* Indication when player can't pickup an armor - no symbol/hud message/gray model/something else
* Gun bob on wall jump
* Global chat message on power-up pickup
* Global for spectators, team only for player chat messages of item pickups (not weapons)
* Add trail effect for MG bullets
* Add damage plums/numbers as a replacement of cartoon hits effect
* Team mate indicator shows health similar to QL, needs more investigation of possible solutions
* Team mate indicator use Power Up icon if the player has one of PU
* Save console input into text file in order to scroll through the whole history (az it was done in ezQuake)
* Fix a bug where grenade can't jump at the same time with the player on jump-pad
* Spec feature: AP/HP/DMG difference graph as in Dota 2
* Transparent items when they are blocking player view
* Don't start the demo until screen is loaded. It often happens when you have high disk or cpu usage, that the demo playback is already started in the background, while the screen is shown after a while

## Sound
* OpenAL installator out of box, or at least UI link to get it
* Possibility to disable map static sounds similar to QL s_ambient
* UH/MH global spawn sound
* MH dried up sound coming from the player possibly with gfx effect
* Low ammo sound as in QL
* Fix cg_flip for OpenAL
* Sound on dropping weapon/ammo by bind

## Linux
* ~~Disable KDE compositor while the game is in full-screen~~ (already works as expected)
* Disable any hotkeys apart from WIN/META & Alt+Enter & Alt+TAB while the game is in fullscreen

## Server
* Cross-platform GUI with minimum requirements (possibly written on Go)

# Qfusion ideas
It is ideas for <a href="https://github.com/Qfusion/qfusion">Qfusion</a> prototype game. Mostly just changes that should be done in compare with <a href="https://warsow.net">Warsow 2.1</a>.

## General gameplay
* Lower view height similar to QL/Q3
* Slower jumping scalled accordigly to view height changes
* Smaller maps scalled accordingly to movement and view height changes
* Slower projectiles
* Smaller knockbacks
* Unlimit ammo in warmup
* Warmup similar to Qw, where no frags happen
* Remove stun

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
* Restore Flag-carrier's HP, only when he not gets damaged
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
* Limit fps in UI to 62, when player isn't connected to any server

## Engine/graphics/others
* Force own model/color for non-team based gametypes demos
* Smooth transition from enemy color to gray on frag
* cg_quadqaunter, cg_followkiller for demos and TV
* Restore desktop resolution after alt+tab from fullscreen
* Weapon placement indicators on missing weapon bind key press like in Xonotic
* Console transparency
* Dust from jumps including on jumppads
* Player view beam in demos/TV
* "timescale -X.X" for the back rewind
* Particles from enemy model coming after hit
* Indication when player can't pickup an armor - no symbol/hud message/gray model/something else
* OpenAL installator out of box, or at least UI link to get it
* Possibility to disable map static sounds similar to QL s_ambient
* UH/MH global spawn sound
* MH dried up sound coming from the player
* Low ammo sound as in QL
* Gun bob on wall jump
* Fix cg_flip for OpenAL
* Global chat message on power-up pickup
* Global for spectators, team only for player chat messages of item pickups (not weapons)
* Sound on dropping weapon by bind
* Add trail effect for MG bullets
* Add damage plums/numbers as a replacement of cartoon hits effect
* Team mate indicator shows health similar to QL, needs more investigation of possible solutions
* Team mate indicator use Power Up icon if the player has one of PU
* Save console input into text file in order to scroll through the whole history (az it was done in ezQuake)
* Fix a bug where grenade can't jump at the same time with the player
* Spec feature: AP/HP/DMG difference graph as in Dota 2
* Transparent items when they are blocking player view

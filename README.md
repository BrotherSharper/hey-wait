# Hey, Wait! :raised_hand:

**9.x / 0.8.x version:**
![Downloads](https://img.shields.io/github/downloads/1000nettles/hey-wait/latest/hey-wait-v0.6.3.zip?style=flat-square)

**0.7.x version:**
![Downloads](https://img.shields.io/github/downloads/1000nettles/hey-wait/v0.4.0/hey-wait-v0.4.0.zip?style=flat-square)

![Forge Installs](https://img.shields.io/badge/dynamic/json?label=Forge%20Installs&query=package.installs&suffix=%25&url=https%3A%2F%2Fforge-vtt.com%2Fapi%2Fbazaar%2Fpackage%2Fhey-wait&style=flat-square)
![Issues](https://img.shields.io/github/issues/1000nettles/hey-wait?style=flat-square)
![MIT License](https://img.shields.io/github/license/1000nettles/hey-wait?style=flat-square)

[![Patreon](img/become_a_patron.png)](https://www.patreon.com/1000nettles)

“Hey, Wait!” is a FoundryVTT module allowing a GM to place “event triggers” as tiles on a scene. When players collide with these triggers, the game pauses and the scene shifts to the player, allowing a GM to explain the theatre-of-the-mind landscape, if the player has ran into a pack of monsters, or anything else you can think of! You can even trigger and execute macros. The intent is to give GMs a bit of breathing room with a pack of players who love to explore.

## What Does This Look Like? :eyes:

On the left, we see the GM's screen where they have placed a Hey, Wait! tile (shown in red.) On the right, we see the player's screen, where they are unable to see the tile. After a collision into the Hey, Wait! tile, the game pauses and pans over to the player who triggered the tile. When a tile is triggered, it turns green. Hey, Wait! also picks up if a player has dragged their token across the scene.

![Hey, Wait! preview](img/preview1_v030.gif)

Thanks to [Neutral Party](https://www.patreon.com/neutralparty) for the sample background map above.

## Instructions :scroll:

Start by installing the module, and enabling it for your world. If you click on the Tile button in the toolbar, you'll see a new button added denoted by a :hand:. This is the same as the Tile creation tool, except it's used to create Hey, Wait! tiles. These tiles are hidden "triggers" which, when a player steps on them with the token they're moving, will trigger a game pause and pans all players' views over to them. You are still able to use the normal tile functionality in FoundryVTT.

![Hey, Wait! in the toolbar](img/preview2_v030.jpg)

You can also toggle the triggered state of the Hey, Wait! tile. Right-click on the tile and toggle it like so:

![Hey, Wait! tile toggling](img/preview3_v030.gif)

Note that the visibility button has disappeared. Hey, Wait! tiles are always invisible to players.

If you would like to adjust the volume of the sound effects, the "Interface" volume slider can be used. Or, you can disable the sound effects completely.

You can also set a macro to be executed when a player triggers a Hey, Wait! tile. Configure this in the tile configuration dialog.

## Settings :ballot_box_with_check:

* **Token Disposition Types Allowed** The token disposition types that are allowed to trigger Hey, Wait! tiles. Defaults to "Friendly" only
* **Restrict GM from Triggering Tiles:** If checked, triggering of the Hey, Wait! tiles will be locked down to only player's token movement and not the GM
* **Warp Players:** If checked, triggering of a Hey, Wait! tile on a scene that a player isn't viewing will warp them to that scene. GMs will always be warped regardless
* **Disable Tile Triggering Sound Effects:** If checked, the module will disable playing sound effects when anyone triggers Hey, Wait! tiles. This will disable it for all players

## Changelog :mag_right:

Please see the [Changelog](https://github.com/1000nettles/hey-wait/blob/main/CHANGELOG.md) for all changes between updates

## Known Limitations :x:

* In the 0.8.x, patterning of Hey, Wait! tiles is not working (sorry!)
* No rotation allowed on Hey, Wait! tiles
* Updating a Hey, Wait! Tile's reaction animation without refreshing the Scene will show the old reaction to players
* Chat macros executed will always be from the GM's name, not the token who triggered the tile

## Future Planned Features :crystal_ball:

* Ability to choose your define your own sound effects
* Ability to customize the symbols and their font / colour in the reaction animations  
* ...please suggest some!

## Acknowledgements :wave:

* Thanks to [Game-icons.net](https://game-icons.net) for the use of the ["Halt" icon](https://game-icons.net/1x1/skoll/halt.html), and the ["Confirmed" icon](https://game-icons.net/1x1/delapouite/confirmed.html``)
* Thanks to [Toptal](https://www.toptal.com) for their ["Toptal Subtle Patterns"](https://www.toptal.com/designers/subtlepatterns/) - used within the backgrounds of the Hey, Wait! tiles
* Default sound effects obtained from [ZapSplat](https://www.zapsplat.com) - used as reactions when stumbling upon Hey, Wait! tiles

# Auto Pathing Tool

A free Geode mod for Geometry Dash 2.2081 (Windows) that finds by itself how to beat a level. It simulates the game's
physics, searches the simulation for the clicks that beat the level, and plays them in the real game. A tick by tick
path editor (F3) lets you correct the bot and let it go on from there.

How to use it: [about.md](about.md). Changes: [changelog.md](changelog.md).

## Installation

### Go back to GD 2.2081 (skip if you're already on it)
Save your data to the cloud first: Settings > Account > Save.

Type steam://open/console in your browser's address bar and let it open Steam.

In the Steam console, enter:

download_depot 322170 322171 3816559102876907245


Wait for the download to finish (if you get a permission error, run Steam as administrator).

Copy everything from

C:\Program Files (x86)\Steam\steamapps\content\app_322170\depot_322171
into
C:\Program Files (x86)\Steam\steamapps\common\Geometry Dash
and replace the existing files.

To stop Steam from updating the game: in C:\Program Files (x86)\Steam\steamapps, right click appmanifest_322170.acf > Properties > tick Read-only > OK.

### Install Geode 5.11.2
Use the installer from https://geode-sdk.org/, then launch the game once.

### Install the mod
Put aliaky.auto-pathing-tool.geode in
C:\Program Files (x86)\Steam\steamapps\common\Geometry Dash\geode\mods
and restart the game. Open a level and press F1 to open the menu.

### Good to know
• Don't use other mods that change the physics or the inputs at the same time (TPS bypass, Click Between Frames, speedhack, noclip, other bots).

• To get the latest GD back later: untick Read-only, then use Verify integrity of game files in Steam.

The paths above are for a default Steam install.
Questions or problems? Feel free to join the Discord server!

## Terms and conditions

By installing or using Auto Pathing Tool you accept these terms.

1. **Free, personal use.** The mod is free. You may use it for showcases, playtesting, creating and editing macros.
2. **No commercial use.** The mod, its code, and the way it works (finding and playing a level's path by searching a
   simulation of the game, live or ahead of time) may not be used for any commercial purpose without written
   permission from the author. This includes selling it or access to it, bundling it or a copy or reimplementation of
   it in a paid or subscription mod menu, bot or tool, and using it to attract customers to a paid product.
   Collaborations can be considered after discussion: contact the author on Discord.
3. **No redistribution as your own.** Do not publish modified or repackaged versions under this name or as your own
   work. Links to the official page are welcome.
4. **Your responsibility.** Bot completions break the rules of leaderboards and of many communities, and can lead to
   removed scores or banned accounts. Use Safe mode (on by default) and do not submit bot results as your own play.
5. **No warranty.** The mod is provided as is, without any warranty. The author is not liable for any damage, data
   loss, or account action that comes from using it.
6. These terms may change with new versions of the mod.

## Support

Questions, bugs and ideas on [Discord](https://discord.gg/S4QzXYf65G). If the mod saves you time, you can leave a tip
on [Ko-fi](https://ko-fi.com/aliaky).

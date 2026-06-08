# Cartographer's Toolkit for Doodle Empires
Both a map size unlocker and a PNG to Map converter.

## Requirements
- BepInEx 5 x64 (Mono). Download from the official BepInEx releases. https://github.com/bepinex/bepinex/releases

## Install
1. Extract the BepInEx zip into the game folder (next to the exe). Run the game once.
2. **EXTRACT** **this mod’s zip** into the plugins location so that:
   - BepInEx\plugins\CartographersToolkit.dll exists
3. Run the game. Check `BepInEx/LogOutput.log` for "Cartographer's Toolkit loaded".

## Converter Instructions
1. Take a PNG and change the colors so they match the game's terrain. If you want to paint a map using a digital brush there is a setting in the config that will make it so if a color is not found it defaults to whatever the closest acceptable color is. If you don't select this then whatever the game doesn't recognize will become water.
2. Edit the config (Steam\steamapps\common\Doodle Empires\BepInEx\config) to change what map is being targeted. Make sure the map is already made in-game. You can make it a blank map if you'd like and the chosen size will not matter. I recommend making a map named "Converter" and using that as your perpetual conversion spot.
3. Once that is done exit the game and restart it. Make sure the PNG inside the map folder has been altered and then renamed to fit the map name.
4. Go to the map and edit it. The game will read the PNG and convert it to a map. Then just save the map and voila, you now have a working map.

## Warnings
The game was not meant to handle sizes much beyond 1000x1000. If you create a map past that expect long loading times and some lag if the map is big enough and you zoom out.

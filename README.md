# Better MC [FORGE] - BMC4 v28, game version: 1.20.1 Cobblemon Integration

## Prerequisites

- Installed `Better MC [FORGE] - BMC4 v28` for `MC 1.20.1` in `curseforge` client
- Download this repo as a .zip as you will need the mods and resourcepacks from here

## Configuration/Additional Setup

1. Go to `My Modpacks` in the `curseforge` client and click `open folder`. (While you're at it make sure to set your ram allocation to 6-8gb under `profile options`, 10gb max)
2. Move mods from the `mods` folder in this repo to the client or server `mods` folder.
3. Move resourcepacks from the `resourcepacks` folder in this repo to the client `resourcepacks` folder and make sure to activate them through the in-game UI to see the pokemon on the minimap (the resourcepack to activate should be called something like `XaerosCobblemon-2.0.7+1.5`).
4. If you like the vanilla minecraft recipe crafting book, inside the `config` folder find the `recipeessentials.json` file and edit the `disableRecipebook: true` and change `true` to `false` with a text editor e.g. `Notepad`, `TextEdit`, `VSCode`
5. Start the game. 
6. Keybindings
   - You can either edit the keybindings using the minecraft UI or the `options.txt` file 
   - Set the cobblemon `open summary` keybinding to j or do it by editing the `options` file and putting the following in `key_key.cobblemon.summary:key.keyboard.j`
   - Set the cobblemon `throw` keybinding to `r (default)` or something you prefer (without conflict e.g. sometimes `shader reload` is also set to `r`)

![](https://raw.githubusercontent.com/cubismvr/Mods/main/Images/Logo.png)

# Custom Themes

As of version 1.1.0, you can modify Cubism's color theme by dropping a Cubism theme file (`.ctf`) in a specific folder on your Quest/Computer. This will let you modify the appearance aspects of the game's environment, puzzle grid and menu. 

- [Custom theme example](#Custom-theme-example)
- [Sideloading a custom theme on Quest](#Sideloading-a-custom-theme-on-Quest)
- [Adding a custom theme on PC](#Adding-a-custom-theme-on-PC)
- [Removing a custom theme](#Removing-a-custom-theme)

## Custom theme example
This repo contains [a theme file example](https://github.com/cubismvr/Mods/blob/main/CustomColorTheme/ExampleLight.ctf) with comments to explain how the `.ctf` format works. You can use this file as a template to make your own themes.

## Sideloading a custom theme on Quest
1. Download a `.ctf` file on your computer from a trusted source, or make your own using [the example in this repo.](https://github.com/cubismvr/Mods/blob/main/CustomColorTheme/ExampleLight.ctf)
2. Connect your Quest to your computer and [open up SideQuest](https://sidequestvr.com/)
3. Open the File Explorer in the top right

![](https://github.com/cubismvr/mods/blob/main/Images/SideQuest1.png)

4. Navigate to the `sdcard/Android/data/com.tvb.cubism/files/`.
5. Press the plus button in the bottom right to add files to this folder. Select the `.ctf` file from your filesystem and upload it here. Note that if multiple `.ctf` files are present in this directory, the game will use the first one it finds.

![](https://github.com/cubismvr/mods/blob/main/Images/SideQuest3.png)

6. When you launch Cubism, the theme file should now be applied. In the settings menu, you should now see that the dark mode option is crossed out, with a message explaining which theme file is overriding.

## Adding a custom theme on PC
WIP

## Removing a custom theme
To remove a custom theme and go back to Cubism's default style, simple remove the `.ctf` file from the game's directory on your Quest or your computer.


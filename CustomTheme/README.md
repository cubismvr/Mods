![](https://raw.githubusercontent.com/cubismvr/Mods/main/Images/Logo.png)

# Custom Themes

As of version 1.1.0, you can modify Cubism's color theme by dropping a Cubism theme file (`.ctf`) in a specific folder on your Quest/Computer, letting you modify the appearance of the game's environment, puzzle grid and menu.
This can be particularly useful if you're making mixed reality content of the game and want to tweak the look of certain elements for better results or to aid in compositing.

The theming system is still very experimental, and is likely to change in future updates. If you have any feedback, or would like to share your own themes with me, you can reach me at thomas@cubism-vr.com.

- [Custom theme example](#Custom-theme-example)
- [Sideloading a custom theme on Quest](#Sideloading-a-custom-theme-on-Quest)
- [Using custom themes on Quest for faux-AR mixed reality using Reality Mixer](#Using-custom-themes-on-Quest-for-faux-AR-mixed-reality-using-Reality-Mixer)
- [Adding a custom theme on PC](#Adding-a-custom-theme-on-PC)
- [Removing a custom theme](#Removing-a-custom-theme)

## Custom theme example
This repo contains [a simple theme file example](https://github.com/cubismvr/Mods/blob/main/CustomTheme/ExampleLight.ctf) based on the Quest's default light theme. This example includes comments to explain how the `.ctf` format works. You can use this file as a template to make your own themes.

## Sideloading a custom theme on Quest
1. Download a `.ctf` file on your computer from a trusted source, or make your own using [the example in this repo.](https://github.com/cubismvr/Mods/blob/main/CustomTheme/ExampleLight.ctf)
2. Connect your Quest to your computer and [open up SideQuest](https://sidequestvr.com/)
3. Open the File Explorer in the top right

![](https://github.com/cubismvr/mods/blob/main/Images/SideQuest1.png)

4. Navigate to the `sdcard/Android/data/com.tvb.cubism/files/`.
5. Press the plus button in the bottom right to add files to this folder. Select the `.ctf` file from your filesystem and upload it here. Note that if multiple `.ctf` files are present in this directory, the game will use the first one it finds.

![](https://github.com/cubismvr/mods/blob/main/Images/SideQuest3.png)

6. When you launch Cubism, the theme file should now be applied. In the settings menu, you should now see that the dark mode option is crossed out, with a message explaining which theme file is overriding.

![](https://github.com/cubismvr/mods/blob/main/Images/CtfMenu.jpg)


## Using custom themes on Quest for faux-AR mixed reality using Reality Mixer
If you have an iPhone or iPad, you can use Fabio Dela Antonio's app [Reality Mixer app](https://apps.apple.com/us/app/reality-mixer/id1539307552) in combination with a custom theme to make mixed reality footage that looks like AR. Here are some examples:
![](https://raw.githubusercontent.com/cubismvr/Mods/main/Images/MR.png)
https://twitter.com/fabio914/status/1341910507327008768?s=20
https://twitter.com/tovanbo/status/1366002113323667465?s=20

To achieve a similar effect, follow these steps:

1. Download and sideload this [mixed reality theme](https://github.com/cubismvr/Mods/blob/main/CustomTheme/MixedRealityTheme.ctf) on your Quest following the instructions above.
2. Install the Reality Mixer app on your iOS device, and follow [these instructions](https://github.com/fabio914/RealityMixer/blob/main/Instructions.md) to calibrate your device for mixed reality.
3. Launch Cubism. If the custom theme was sideloaded correctly, the game will look like this:
![](https://raw.githubusercontent.com/cubismvr/Mods/main/Images/ARTheme.jpg)

4. In the Reality Mixer app, go to "Start Mixed Reality", and before connecting, set the "Background visibility" setting to "Filtered", and the "Color to alpha" setting to "Black".
5. Once you connect, the Reality Mixer app footage should now look like AR footage.

## Adding a custom theme on PC
1. Download a `.ctf` file on your computer from a trusted source, or make your own using [the example in this repo.](https://github.com/cubismvr/Mods/blob/main/CustomColorTheme/ExampleLight.ctf)
2. Copy the `.ctf` file to this folder on your PC: `C:\Users\[yourPcName]\Documents\Cubism`.
3. When you launch Cubism, the theme file should now be applied. In the settings menu, you should now see that the dark mode option is crossed out, with a message explaining which theme file is overriding.

## Removing a custom theme
To remove a custom theme and go back to Cubism's default style, simple remove the `.ctf` file from the game's directory on your Quest or your computer.
In SideQuest, you can do this by clicking the red X next to the file.

![](https://github.com/cubismvr/mods/blob/main/Images/SideQuest4.png)

![](https://raw.githubusercontent.com/cubismvr/Mods/main/Images/Logo.png)

NOTE: this guide requires you to enable dev mode on your quest. For a simpeler way of sideloading Puzzles that doesn't require this, check out [this tutorial instead](https://www.cubism-vr.com/editor/);

# Custom Puzzles

As of version 1.1.0, you can now sideload custom puzzles into [Cubism](https://www.oculus.com/experiences/quest/2264524423619421/?locale=en_US). 

Puzzles are described by a `.cube` file (JSON with a fancy file type). These can be placed in a specific folder on your Quest/Computer, after which they will show up in a new 'Custom Puzzles' menu item in the game.

The long term goal is to add a proper in-VR level editor to the game to generate these files, but by enabeling puzzle sideloading and publishing the puzzle file format, my hope is to already take a first small step towards enabeling player created puzzles.

If you have any feedback or would like to share your custom puzzles with me, you can reach me at thomas@cubism-vr.com.

- [Puzzle examples and downloads](#puzzle-examples-and-downloads) 
- [Sideloading puzzles on Quest](#sideloading-custom-puzzles-on-quest)  
- [Adding puzzles on PC](#adding-custom-puzzles-on-pc)  
- [Community Level Editors](#community-level-editors)

![](https://github.com/cubismvr/mods/blob/main/Images/CustomPuzzles2.jpg) 

## Puzzle examples and downloads

#### Example Puzzle - ([view here](https://github.com/cubismvr/Mods/blob/main/CustomPuzzles/Example.cube))
This is simple example puzzle with comments to help explain how the `.cube` format works. You can use this file as a template to start making your own puzzles.

#### B-Sides Puzzlepack - ([download here](https://github.com/cubismvr/mods/releases/tag/B-Sides))
This is a small unofficial puzzlepack containing a collection of puzzles that were cut from the main game. Follow the steps below to sideload them in the game.

## Sideloading custom puzzles on Quest

1. Download some `.cube` files on your computer from a trusted source. You can download [some example puzzles here](https://github.com/cubismvr/mods/releases/tag/B-Sides).
2. Connect your Quest to your computer and [open up SideQuest](https://sidequestvr.com/)
3. Open the File Explorer in the top right

![](https://github.com/cubismvr/mods/blob/main/Images/SideQuest1.png)

4. Navigate to the `sdcard/Android/data/com.tvb.cubism/files/CustomPuzzles`. If you don't see a `CustomPuzzles` folder, make sure you've updated Cubism to version 1.1.0 or later, and have opened the game at least once since updating.
5. Press the plus button in the bottom right to add files to this folder. Select the `.cube` files from your filesystem and upload them here.

![](https://github.com/cubismvr/mods/blob/main/Images/SideQuest2.png)

6. When you launch the game, you should now see a new "Custom Puzzles" menu item in the main menu, with your sideloaded puzzles within. Note this menu item will not be visible if no puzzles have been sideloaded, and that puzzles which don't follow [the correct fileformat](https://github.com/cubismvr/Mods/blob/main/CustomPuzzles/Example.cube) won't show up either.

![](https://github.com/cubismvr/mods/blob/main/Images/CustomPuzzles1.jpg)

## Adding custom puzzles on PC

1. Download some `.cube` files on your computer from a trusted source. You can download [some example puzzles here](https://github.com/cubismvr/mods/releases/tag/B-Sides).
2. Copy the puzzle files to this folder on your PC: `C:\Users\[yourPcName]\Documents\Cubism\CustomPuzzles`. If you don't see a `CustomPuzzles` folder, make sure you've updated Cubism to version 1.1.0 or later, and have opened the game at least once since updating.

![](https://github.com/cubismvr/mods/blob/main/Images/CustomFolderPC1.jpg)

3. When you launch the game, you should now see a new "Custom Puzzles" menu item in the main menu, with your downloaded custom puzzles within.

## Community level editors

Some members of the Cubism community have made their own level editors to help create custom levels for Cubism!
- [Cubism Level Editor](https://github.com/DevPika/cubismvr-level-editor) by [DevPika](https://github.com/DevPika)
- [Cubism Web Level Editor](https://shiva-kannan.github.io/CubismWebLevelEditor/Build/index.html) by [Shiva Kannan](https://twitter.com/ShivaKannan7)

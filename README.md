# Download
1. Download the .blend from the latest release on the [Releases](https://github.com/goribby/L4D2-MultiRig/releases) page.

2. Open the file.

# Instructions

## Enable/Disable Meshes
Click the "Properties" bone, the one shaped like a cog. <br>
From that, press N on your keyboard to pull up the N panel, then go to the Item tab, then in Properties. <br>
There, you can drag the menus to select which arm and weapon/item you want. Setting either to 0 disables the corresponding mesh. <br>

## Using the Rig
- The way the L4D2 skeleton works, you have to "build" the weapon/item using the bones. That means you have to manually place the magazine, bolt, whatever in the right place and keyframe the bone. The positions are different for every weapon. I included the idle animation from my pistol mod to help you a bit.

- Selecting some weapons or items shows/hides certain bones specific to that prop, that way you don't have to worry about chainsaw bones when animating a pistol, for example. If you'd like to remove this behavior, go to the bone layers in the armature and remove the drivers from the hide button (eye icon).

- All fingertip bones have IK to make posing easier, that means you can just move the tip and the other finger bones will follow it, instead of rotating each bone individually. If you'd like to disable this, go to the Properties bone and set "Hand_L/Hand_R IK Fingers" to 0.

## Modding
This rig <b><i>should</i></b> be fully modding compatible. With that said, I may have missed some stuff, so feel free to open up an issue on the [Issues](https://github.com/goribby/L4D2-MultiRig/issues) page or message me on Discord. <br>
Some bones are already set up to match the game camera. They're all in the "Skeleton" bone layer, so avoid messing with that if you're using the rig to mod the game.

## Credits

- Rig: Goribby
- Meshes and Textures: Valve Software
    
You can modify and use this rig however you want. Except for Commercial use, as this would break Valve's copyright since these are their assets.

# About
A Left 4 Dead 2 IK Multi Rig for Blender 4.1+. <br>
It features every Arm model, as well as every weapon and item.

<i>If you need any additional help, feel free to message me on Discord:</i> <b>@goribby</b>

---
If you're curious to see how the rig exports to Source, check out my pistol mod below:

[![Pistol mod](http://img.youtube.com/vi/SeFOuWl7bZY/0.jpg)](https://youtu.be/SeFOuWl7bZY?si=nazp9xHaqjtE8Ypb "Pistol mod")

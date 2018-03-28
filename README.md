# Vanilla-Normals-Renewed
A shaders compatible minecraft texturepack, based on vanilla but with normals and specular highlights.
This version (renewed) is made for PBR, but still a WORK IN PROGRESS, so you may encounter some textures with strange behavior.

## Description

I didn't want any of those fancy high-resolution texturepacks in order to enjoy normal mapping and specular highlights.
So i decided to make my own, but based on vanilla textures.

I release this texturepack to the public, because everyone should be able to enjoy it.

## Screenshots
Textures have bump mapping informations, allowing parallax occlusion mapping and normal mapping.
Smoothness informations is very important for the credibility of materials too, especially when the sun lights it at grazing angles.

![Normals and smoothness](https://user-images.githubusercontent.com/18035775/34640565-eb2fc134-f2f4-11e7-9d06-c615fb50aed1.png)

Metals and smooth materials now have the correct informations to compute reflections.
SEUS renewed heavily realies on Screen Space Reflections for this, so the reflections won't be perfect if you really pay attention to it, but most of the time it does a good job.

![Metal and smooth materials](https://user-images.githubusercontent.com/18035775/34640564-eb1388de-f2f4-11e7-8597-e132e9cde2db.png)

## Installation

- Install a shader supporting normal and specular mapping. If you don't know which one, give this one a shot :
http://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/1280299-sonic-ethers-unbelievable-shaders-compatible-with
- On this page, click on «Clone or download», then «Download as ZIP»
- Type %appdata% on your start menu. (for windows, not sure for mac or linux)
- Go to the .minecraft folder
- Go into the resourcepacks folder. Create it if it doesn't exist
- Extract the file you downloaded here
- Select the right shader and resourcepack in minecraft options
- Enjoy !

## Known Bugs (on SEUS renewed 1.00)
- Double doors do not correctly take into account direction of light (for the second door)
- Same for Anvils, and other rotated textures, such as rails
- Very smooth surfaces may be too dark when not facing the sun (mainly fixed, but some problems maybe stayed)
- Parallax behaves strangely on rotated textures (rails, for example)
- If parallax self-shadow are on, 3D ores will look weird when lighted from direct sunlight (Pretty rare underground)
- ???

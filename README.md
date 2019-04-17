# Vanilla-Normals-Renewed-1.12
A shaders compatible minecraft texturepack, based on vanilla but with normals and proper glossiness informations.
This version (renewed) is made for PBR, but still a WORK IN PROGRESS, so you may encounter some textures with strange behavior.

⚠️ THIS VERSION IS NOT COMPATIBLE FOR MINECRAFT ≥ 1.13 ⚠️

## Description

I didn't want any of those fancy high-resolution texturepacks in order to enjoy normal mapping and specular highlights.
So i decided to make my own, but based on vanilla textures.

I release this texturepack to the public, because everyone should be able to enjoy it.

## Copyright

You can do whatever you want with my texturepack, screenshots, videos, modifications for personnal use or redistribution, as long as you don't sell it and provide a link to this page.

## Screenshots
⚠️ The screenshots provided here were made using SEUS renewed v1.0, the results will differ with other shaders ⚠️

Textures have bump mapping informations, allowing parallax occlusion mapping and normal mapping.
Smoothness informations is very important for the credibility of materials too, especially when the sun lights it at grazing angles.

![Normals and smoothness](https://user-images.githubusercontent.com/18035775/34640565-eb2fc134-f2f4-11e7-9d06-c615fb50aed1.png)

Metals and smooth materials now have the correct informations to compute reflections.
SEUS renewed heavily relies on Screen Space Reflections for this and don't take correctly roughness surfaces for it, so the reflections may be too shiny and imperfect. However using SEUS PTGI will provide Path-Traced reflections and indirect lighting, and correctly take into account roughness.

![Metal and smooth materials](https://user-images.githubusercontent.com/18035775/34640564-eb1388de-f2f4-11e7-8597-e132e9cde2db.png)

## Installation

- Install a shader supporting normal and specular mapping. If you don't know which one, give this one a shot : https://sonicether.com/seus/ and if you want raytracing, it should also work properly with SEUS PTGI6 : https://www.patreon.com/sonicether

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
- If parallax self-shadow are on, 3D ores might look weird when lighted from direct sunlight (Pretty rare underground)
- ???

# RimWorldMod
Rimworld mod template including About.xml, readme.md. For personal use, Copy the files, and select this as template, when making another mod.

> Don't forget that every XML document should start with ```<?xml version="1.0" encoding="UTF-8"?>```
> These are the dynamic buttons from the DogApparel mod that you can copy and use for your other RimWorld mods. only change the repo/modname.
> 1. First button is for RimWorld support and only shows up when there is a Master/About/About.xml otherwise it errors.
> 2. Second dynamic badge shows License and is anchored with a link to mod/blob/LICENSE page.
> 3. Third dynamic button is to redirect you to the mod's issues page.
> 4. Fourth dynamic button is to redirect people to my discord server. (you can just copy)
> 5. Fifth dynamic button is to redirect people to my ko-fi page to donate if they like. (you can just copy)

> Reserve some space between the buttons, using this ``&emsp;``

> How to make these dyanamic badges this site is for github ```https://shields.io/badges/git-hub``` it provides a tool so you can also select icon and icon color.
1. Start with GitHub badges for issues,discussions,license ```<a href="https://github.com/username/repo/blob/master>```
2. The before last and last button: Depending on if you choose to use discussion page or issue page to solve bugs) would be after 3 --> 4,5 are dynamic buttons to redirect people to my discord server and if they want they can donate on my kofi page. These buttons are consistent to all mod readme.md pages.
3. Check if all buttons have magenta in their button to match all my github readme.md pages.
4. Dynamic buttons are done with the ```HTML``` syntax. If they won't work, choose markdown instead which is !github]```(https://shields.io/badges/git-hub)``` first part is alt text in square brackets, second part is the shield.io link between parathese  

<a href="https://rimworldgame.com">
  <img alt="Built for RimWorld" src="https://img.shields.io/badge/dynamic/xml?url=https%3A%2F%2Fraw.githubusercontent.com%2FChunnyluny%2FDogApparel%2Fmaster%2FAbout%2FAbout.xml&query=%2FModMetaData%2FsupportedVersions%2Fli%5Blast()%5D&label=Built%20for%20RimWorld&style=for-the-badge&color=magenta" />
</a>
&emsp;
<a href="https://github.com/Chunnyluny/DogApparel/blob/Master/LICENSE">
  <img alt="GitHub" src="https://img.shields.io/github/license/Chunnyluny/DogApparel?style=for-the-badge&logo=Github&color=magenta" />
</a>
&emsp;
<a href="https://github.com/Chunnyluny/DogApparel/issues">
<img alt="GitHub issues" src="https://img.shields.io/github/issues/chunnyluny/DogApparel?style=for-the-badge&logo=github&color=magenta">
</a>
&emsp;
<a href="https://discord.gg/Njbw9RTQkA">
  <img alt="Join me on Discord" src="https://img.shields.io/badge/join_me_on-discord-magenta?style=for-the-badge&logo=discord" />
</a>
&emsp;
<a href="https://ko-fi.com/T6T1NNFAL">
  <img alt="Buy me a coffee" src="https://shields.io/badge/ko--fi-Buy_me_a_coffee-magenta?logo=ko-fi&style=for-the-badge" />
</a>

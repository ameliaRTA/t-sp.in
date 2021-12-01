---
layout: post
title: "Cambridge: The Open-Source Arcade Stacker"
---
![Cambridge logo](/public/img/cambridge.png)

# Welcome to Cambridge!

As you might have guessed, Cambridge is the next open-source falling-block game engine - written and maintained exclusively by [Milla](https://github.com/MillaBasset), [joezeng](https://github.com/joezeng) and [Oshisaure](https://github.com/oshisaure).

The [Discord server](https://discord.gg/AADZUmgsph) has been reopened!

# Downloads + How to run Cambridge

## Windows

### Stable
[64-Bit Download (pick this if you're not sure)](https://github.com/MillaBasset/cambridge/releases/latest/download/cambridge-windows.zip)

[32-Bit Download](https://github.com/MillaBasset/cambridge/releases/latest/download/cambridge-win32.zip)

Extract the contents of the .zip file into a folder and run `cambridge.exe`.

### Bleeding Edge / Unstable

**Keep in mind that this is an unstable version and there is a chance that the game might crash.**

Make sure that you have LÖVE installed: [https://love2d.org/](https://love2d.org/)

Then download the source code for Cambridge over at [https://github.com/MillaBasset/cambridge/archive/master.zip](https://github.com/MillaBasset/cambridge/archive/master.zip). Extract the .zip file, open a command prompt inside the cambridge-master folder and then then run this command to launch Cambridge:

`dist\windows\love.exe .`

For 32-Bit Windows installations, you'll have to run this instead:

`dist\win32\love.exe .`

## macOS and Linux

If you haven't already, install `love` with your favourite package manager (Homebrew on macOS, your system's default on Linux). **Make sure you're using LÖVE 11, because it won't work with earlier versions!** You will need it for both Stable and Bleeding Edge / Unstable releases.

### Stable

[Download (cambridge-other.zip, a universal version that works on any OS that can run .love files using `love`)](https://github.com/MillaBasset/cambridge/releases/latest/download/cambridge-other.zip)

Extract the contents of the .zip file into a folder, open the Terminal in the extracted folder and then run `love cambridge.love`.

### Bleeding Edge / Unstable

**Keep in mind that this is an unstable version and there is a chance that the game might crash.**

You have two options:

* Clone the repository using `git clone https://github.com/MillaBasset/cambridge` in your Terminal
* Download the .zip archive of the repository at [https://github.com/MillaBasset/cambridge/releases](https://github.com/MillaBasset/cambridge/releases) and extract it

From there, head into the repository folder (either `cambridge` or `cambridge-master` depending on which route you took) and execute `love .` - that's all there is to it.

# Installing modpacks

Yes indeed, Cambridge supports modpacks! However, it should be noted that since these are not part of the main Cambridge experience, your mileage in terms of how well they work may vary. If this doesn't deter you, go to [the Cambridge Modpack repository over at GitHub](https://github.com/MillaBasset/cambridge-modpack) to get a taste of the mod potential.

# Credits

- [Milla](https://github.com/MillaBasset) for writing these credits originally and developing the game!
- [Lilla Oshisaure](https://www.youtube.com/user/LeSpyroshisaure) for being my co-dev!
- [joezeng](https://github.com/joezeng) for the original project, and for offering to help with the expansion!
- [The Tetra Legends Discord](http://discord.com/invite/7hMx5r2) for supporting me and playtesting!
- [The Absolute Plus](https://discord.gg/6Gf2awJ) for being another source of motivation!
- [sinefuse](https://sinefuse.moe) for hosting this document on t-sp.in and help with other small bits and bobs!

More special thanks can be found in-game, under the "Credits" menu.

# Other Notable Games

- [TGMsim](https://github.com/2Tie/TGMsim) by 2Tie
- [Multimino](https://gamejolt.com/games/multimino/556683) by Axel Fox
- [Tetra Legends](https://tetralegends.app) by Dr Ocelot
- [ZTrix](https://discord.gg/MGhqCBDGNH) by Electra
- [Shiromino](https://github.com/shiromino/shiromino) by Felicity/nightmareci/kdex
- [Cursed Blocks](https://github.com/Manabender/Cursed-Blocks) by Manabender
- [Picoris 2](https://www.lexaloffle.com/bbs/?tid=41733) by MarkGamed
- [Tetra Online](https://github.com/Juan-Cartes/Tetra-Offline) by Mine
- [Techmino](https://discord.gg/6Yuww44tq8) by MrZ
- [Example Block Game](https://github.com/oshisaure/example-block-game) by Oshisaure
- [Master of Blocks](https://discord.gg/72FZ49mjWh) by Phoenix Flare
- [Spirit Drop](https://rayblastgames.com/spiritdrop.php) by RayRay26
- [Puzzle Trial](https://kagamine-rin.itch.io/puzzle-trial) by Rin
- [stackfuse](https://github.com/sinefuse/stackfuse) by sinefuse

![Cambridge Logo](https://cdn.discordapp.com/attachments/625496179433668635/763363717730664458/Icon_2.png)

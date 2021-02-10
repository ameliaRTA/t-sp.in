---
layout: post
title: "Cambridge: The Open-Source Arcade Stacker"
---
![Cambridge logo](public/img/cambridge.png)

# Welcome to Cambridge!

As you might have guessed, Cambridge is the next open-source falling-block game engine - written and maintained exclusively by [SashLilac](https://github.com/SashLilac), [joezeng](https://github.com/joezeng) and [Oshisaure](https://github.com/oshisaure).

[Join our Discord server for help and a welcoming community!](https://discord.gg/mteMJw4)

# Downloads + How to run Cambridge

## Windows

### Stable
[64-Bit Download (pick this if you're not sure)](https://github.com/SashLilac/cambridge/releases/latest/download/cambridge-windows.zip)

[32-Bit Download](https://github.com/SashLilac/cambridge/releases/latest/download/cambridge-win32.zip)

Extract the contents of the .zip file into a folder and run `cambridge.exe`.

### Bleeding Edge / Unstable

**Keep in mind that this is an unstable version and there is a chance that the game might crash.**

Make sure that you have LÖVE installed: [https://love2d.org/](https://love2d.org/)

Then download the source code for Cambridge over at [https://github.com/SashLilac/cambridge/archive/master.zip](https://github.com/SashLilac/cambridge/archive/master.zip). Extract the .zip file, open a command prompt inside the cambridge-master folder and then then run this command to launch Cambridge:

`dist\windows\love.exe .`

For 32-Bit Windows installations, you'll have to run this instead:

`dist\win32\love.exe .`

## macOS and Linux

If you haven't already, install `love` with your favourite package manager (Homebrew on macOS, your system's default on Linux). **Make sure you're using LÖVE 11, because it won't work with earlier versions!** You will need it for both Stable and Bleeding Edge / Unstable releases.

### Stable

[Download (cambridge.love, an universal file that works on any OS that can run .love files using `love`)](https://github.com/SashLilac/cambridge/releases/latest/download/cambridge.love)

Put `cambridge.love` anywhere you'd like, open the Terminal in the folder with the file and then run `love cambridge.love`.

### Bleeding Edge / Unstable

**Keep in mind that this is an unstable version and there is a chance that the game might crash.**

You have two options:

* Clone the repository using `git clone https://github.com/SashLilac/cambridge` in your Terminal
* Download the .zip archive of the repository at [https://github.com/SashLilac/cambridge/releases](https://github.com/SashLilac/cambridge/releases) and extract it

From there, head into the repository folder (either `cambridge` or `cambridge-master` depending on which route you took) and execute `love .` - that's all there is to it.

# Installing modpacks

Yes indeed, Cambridge supports modpacks! However, it should be noted that since these are not part of the main Cambridge experience, your mileage in terms of how well they work may vary. If this doesn't deter you, go to [the Cambridge Modpack repository over at GitHub](https://github.com/SashLilac/cambridge-modpack) to get a taste of the mod potential.

# Credits

- [SashLilac](https://github.com/SashLilac) for writing these credits originally
- [Lilla Oshisaure](https://www.youtube.com/user/LeSpyroshisaure) for being my co-dev!
- [joezeng](https://github.com/joezeng) for the original project, and for offering to help with the expansion!
- [The Tetra Legends Discord](http://discord.com/invite/7hMx5r2) for supporting me and playtesting!
- [The Absolute Plus](https://discord.gg/6Gf2awJ) for being another source of motivation!
- [sinefuse](https://sinefuse.moe) for hosting this document on t-sp.in and help with other small bits and bobs!

The following people in no particular order also helped with the project:
- [Hailey](https://github.com/haileylgbt)
- CylinderKnot
- MarkGamed7794
- [Mizu](https://github.com/rexxt)
- MattMayuga
- Kitaru
- switchpalacecorner
- [2Tie](https://github.com/2Tie)
- [nightmareci](https://github.com/nightmareci)
- [MyPasswordIsWeak](https://github.com/MyPasswordIsWeak)
- [Dr Ocelot](https://github.com/Dr-Ocelot)

![Cambridge Logo](https://cdn.discordapp.com/attachments/625496179433668635/763363717730664458/Icon_2.png)

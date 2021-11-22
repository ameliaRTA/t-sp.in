---
layout: post
title: "DTET - Installation and Setup"
---

Quick heads up before you read on: This guide is a work in progress. I plan to go properly in depth with installing this game once I've created screenshots and everything, but for now some of the less important instructions may be missing. That being said, following this guide you should still be able to download and install the game just fine, provided you do some of your own research via Google if you have to.

# Downloading DTET and other related things

First off, you need to download DTET. For some reason Mihys, the developer, does not have a download link on his website, so here is one provided by the internet archive. [Click here to download it.](https://archive.org/download/dtet.7z/Dtet.7z) Note that you will need 7-Zip to unpack the archive.

Next, you want to get a dll file named `dx7vb.dll`. Just google for it, you can find it pretty easily. Be sure to apply common sense in order to not download a version packed full of malware on steroids - you have been warned.

Finally, since DTET can emulate a MIDI synthesizer but the one included with Windows is very Not Good, you're better off downloading a new MIDI driver. OmniMIDI is an incredible MIDI driver, optimized to work with MIDI files that have a very large amounts of notes at the same time. DTET's MIDI files aren't *super* crazy, but you will have missing sound channels if you use the normal MIDI synthesizer included in Windows. [You can download OmniMIDI here, straight from its GitHub repository.](https://github.com/KeppySoftware/OmniMIDI/releases)

Do note that for OmniMIDI, you will also need a soundfont file. Just google for the Microsoft "GM" soundfont, you'll probably find a bunch of results - as long as it's a .sf2 file, you should be fine.

**OPTIONAL:** If you want to have a workaround for DTET's currently existing "global input" issue (read: it will capture every keystroke you do, even while out of focus, which can be a bit of a faff when typing somewhere while the game is still open), you will need Sandboxie Plus. [Download Sandboxie Plus from here.](https://github.com/sandboxie-plus/Sandboxie/releases)

# Installing DTET

Just unpack the archive containing the actual game somewhere like `C:\Games\DTET` for example. Put the `dx7vb.dll` file into the DTET folder. Install OmniMIDI and enable the soundfont you downloaded.

If you downloaded Sandboxie Plus, which, again, is not a necessity by any means, but can circumvent the global input issue I mentioned, just install it.

We're not quite done yet though, as we will have to register the DLL file that we downloaded and put into the DTET folder. Open up the command prompt (Or Powershell, whatever works for you) as Administrator. Then, using the `cd` command, we will want to navigate into our DTET folder. For this, you can just do this:

`cd "INSERT DTET FOLDER PATH HERE"`

If you unpacked the game where this guide told you to, you would type this, for example:

`cd "C:\Games\DTET"`

Now that we are in the directory we have to be, all that's left to execute is this:

`regsvr32.exe dx7vb.dll`

If all went well, you should see a pop-up that says that it worked successfully. From here on, you can now run the game!

# Configuring DTET

**Sandboxie is not covered here. I will make a guide for that later down the line, but for now, you're on your own. Don't worry though, it should be easy enough to configure to your liking.**

The only thing you really need to configure in DTET are keybinds (which should be easy to change) and the MIDI driver used, which should also be easy to figure out. Just head into the options menu and mess around a bit. I will add proper instructions for it when I have proper time for making screenshots and everything.

Either way, it's not exactly rocket science. I'm sure you'll figure the rest out from here. gl;hf
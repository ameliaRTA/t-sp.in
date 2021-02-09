---
layout: post
title: An Explanation of HMS
---

## What is this HMS stuff?

HMS, (also known as HMS123, HMS123311 or "Hyper Mysterious Shaddonic 123311", yes, you read correctly) is an overpowered joke character (read: "DeviantArt-tier recolor of Sonic which is incredibly overpowered", the parody) mod for Sonic Robo Blast 2. He has several unique abilities which set him apart, some of which aid a lot in speedrunning through levels in ways you never even thought were possible in the first place. This document will go into a few of those abilities which make him incredibly broken.

### "Super state"-invincibility

Pretty self-explanatory... except not really. You see, *technically*, HMS always enters a "Super" state - something that you normally only can do once you earn all 7 Chaos Emeralds and have 50 rings. However, HMS just kind of starts out with all 7 Emeralds and 50 rings every time he respawns. So basically, he can run into lots of things that usually hurt you, such as enemies, lava and spikes. There's two things that *can* actually hurt (and subsequently, kill) HMS: bottomless pits and getting crushed. More on the crushed part later due to other abilities.

### Incredibly stupid base stats

This one is actually self-explanatory. HMS simply has ridiculously high base stats for running speed, jump height and spindash speed. Ideally, you want to spindash and then once you've let go of the spin button, jump, in order to preserve the crazy spindash speed. Running is still incredibly fast but *easily* outmatched by a spindash, if you're able to preserve its momentum over longer periods of time.

### Chaos Control Thok

And here is by far the craziest part of HMS, hands down. If you thok mid-air by pressing and holding the jump button, you enter a "Chaos Control" state. Every frame, the game will kick you forwards by 80 fracunits (this is the measurement DOOM engines, and as such SRB2, use for length). This only stops once you hit the floor, which you won't unless you just happen to line up with a sector which *just happens* to have the same height as you do, you let go of the jump button, or you die.

Notice how I didn't say that Chaos Controlling into a wall would stop you - because it **doesn't.** In fact, there are 5 possible outcomes for what happens next:

* If it's a ceiling below the wall you hit, you get *downwarped to that ceiling* and continue to Chaos Control
* If it's a floor above the wall you hit, you get *upwarped to that floor* and stop chaos controlling
* If the wall just thin enough (read: less than 80 fracunits thick) and there isn't a thok barrier behind it, you'll flat out just *clip through*
* If it's a thok barrier, you'll likely bounce back but continue Chaos Controlling
* If it's multiple sectors behind eachother or a specific kind of thok barrier, you will warp inbetween the floor and ceiling, getting crushed and you die (Yes, this means that the Thok actually doesn't have noclip properties)

There is technically a 6th outcome, but that involves what's called the "blockmap border", and it's a rather complicated affair. You see, DOOM maps (and as such, SRB2 maps) are -32768 by 32768 fracunits large, in both directions. If you somehow escaped the map (for example from inside a cave, where people sometimes just don't really care much about thok barriers because they'll just make one sector for a wall and call it a day), you can run up to that very edge of the blockmap, and if you thok into it, you're underflowing or overflowing your X or Z value, which will put you at the exact opposite end of the map. So if you thok into the wall at Z=32768, you'll pop out at Z=-32768, with the X value being intact, unless of course you moved along that axis.

And by the way, yes, this trick does find use: Castle Eggman Zone 1 and Neo Aerial Garden Zone use this to just zoom their way to the finish. CEZ1 is easy, NAGZ is absolutely not easy, especially on OpenGL renderer because all you get is pitch black darkness and your character running in the void. Software renderer makes this a bit easier because you get a "Hall of mirrors" effect, but you can still see parts of the map and orientate yourself alongside those (this is why I use software renderer to run HMS, by the way).

As you can see, this is incredibly broken and well abused throughout the entire run. Each map has been checked (or sometimes still is being checked) for potential routes to thok through, in order to make them many times faster to clear than they were ever intended to be. That's all in terms of abilities relevant for speedrunning, go check the HMS release post if you want to know more about his other fun abilities.

## The incredibly random noises you hear

As mentioned at the beginning, HMS is a joke character. There are two variants of the character - one normal version which is just the character, and then another version with the voicepack, which strived to be as annoying, obnoxious and pretentious as possible (Again, keep in mind that HMS is a joke character which is basically just an overpowered Sonic recolor). The voicepack is the super weird noises you hear sometimes if I do a HMS run. Here's the kicker: Using the voicepack version is slightly faster, because Eggman's death animation ends faster and thus spawns the capsule faster, resulting in a bunch of seconds saved across the entire run, which as you can imagine, adds up.

## Where's the super music?

I wrote my own .soc which disables Super Sonic-music across all stages, except for the final boss. The music in the HMS voicepack is quite frankly annoying after a while, and besides, the v2.2 music is incredibly good, even if you only hear very little of it during the runs. It's certainly far better than hearing the same song's 5-10 beginning seconds over and over again.

Since no one has complained about the usage of this .soc, since there isn't really a category for HMS runs on speedrun.com or any other "official" platform to measure best times against others and since I'm the only runner anyways, I will continue doing so for my own sanity (and honestly, likely yours too).

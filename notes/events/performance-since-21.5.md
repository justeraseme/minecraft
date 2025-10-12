# Game Performance since 1.21.5

## TL;DR
Minecraft: Java Edition release 1.21.5 heavily overhauled rendering in a way, that you may or may not experience lower performance than expected. Some snapshots from 1.21.6 appear to have made it worse, and the alleged cause [is already documented](https://github.com/CaffeineMC/sodium/issues/3115#issuecomment-2885657933). 

Optifine itself has officially skipped version 1.21.5, making Sodium your only option on that version. Another reason why Sodium is better for most modern use cases.

**YMMV**. For most users, this shouldn't be anything to worry about. You can keep playing without issues, though your performance may be worse than expected.

## What Happened?
On March 25th, 2025, update 1.21.5 for Minecraft: Java Edition released. Most of the additions were mostly aesthetical, such as the new mob variants for some of the game's passive mobs, new plant focused blocks and new spawn egg textures.

However, according to some players, performance in 1.21.5 was allegedly lower than in 1.21.4. Some early snapshots for 1.21.6 (specifically [25w16a](https://bugs.mojang.com/browse/MC/issues/MC-297122) and 25w17a) seems to have made performance **significantly worse**, and is caused by code that Sodium does not touch at all.

Sodium would report on their 1.21.5 release on April 3rd, 2025, that there had been performance regressions, likely caused by rendering engine changes. Versions since then are believed to have "performance regressions". Sodium has decided to wait for Mojang to calm down on their rendering chaos before working on these versions.

## That sounds scary, what can I do? Will I notice any issues?
Unfortunately, you can't do much. If you are on a version later than 1.21.6, you will have access to OptiFine like normal (why would you want to though) and Sodium will be available, but **your only option on 1.21.5 is Sodium**. And if you're smart, you won't settle for no mods.

You can still optimize 1.21.6+ and versions before 1.21.5 like normal, and for the most part, things will be smooth sailing. Your performance could be lower than expected, or perhaps you might not even notice a thing.

It is very possible that you might not notice a difference, but it is still **highly** recommended to avoid 1.21.5+ for the time being if you can. If you are in a modded enviornment or have control of the version, 1.21.1 is recommended for the wider selection of mods using it as an LTS version over 1.21.2+.

## What about now? (1.21.9+)
Since this guide was first written, some improvements were made in the performance department that may or may not make the game slightly better to run. A small list of these changes include no more spawn chunks, entity rendering order improvements, and particle culling.

Note that this is **not** a confirmation that the performance regressions are resolved.

25w41a (the first snapshopt for 1.21.11) will seemingly upgrade the performance even more with graphics presets and and internal server changes that aim to improve client FPS. FPS may be higher in 1.21.11, we will have to wait and see.

## Further reading
- [Performance regresions since Minecraft 1.21.5](https://github.com/CaffeineMC/sodium/issues/3115) (links to Sodium's GitHub)
- [MC-297122 (Significant performance regression in 25w16a)](https://bugs.mojang.com/browse/MC/issues/MC-297122)
- [MC-295893 (Significant performance regressions with vertex/index buffer uploads)](https://bugs.mojang.com/browse/MC/issues/MC-295893)
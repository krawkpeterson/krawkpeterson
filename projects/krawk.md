# KRAWK

![KRAWK on the real terrain of Telluride](../assets/work/krawk.jpg)

Your zip code. Their graveyard.

Type any US zip code. The game pulls public elevation, streets, buildings, and live weather, and an AI director writes the battle. You get a .45 double-stack 1911 and a .44 Magnum Colt Anaconda, both synthesized, and a drill sergeant through boot camp.

On the public build the director is a rules engine, worlds are cached in the browser, and the killboard stays on the device. Locally, the same pipeline runs on an Express API with sharded SQLite, and can hand the battle to a model.

[Play it](https://krawkpeterson.github.io/GoblinShooter/) · [Source](https://github.com/krawkpeterson/GoblinShooter)

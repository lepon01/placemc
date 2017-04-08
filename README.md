# placemc
Mirrors Place into Minecraft

## I'm a noob, I just want to join!

The server that has previously ran the server has been **discontinued due to the end of Reddit Place.**

You can download the final map that has been hosted on the server at http://moustacheminer.com/place/world.tar

## Building

Spigot requires a jar containing plugin.yml plus the classes.

Ensure that all of org.apache.httpcomponents:fluent-hc:jar:4.5.3's (and its dependencies's) classes are in the jar too.

## Server setup

Use spigot. Add plugin VoidGenerator, plus this one.

Add to `bukkit.yml`:

    worlds:
      world:
        generator: VoidGenerator

## License

Copyright 2017 JJJollyjim

Available under the terms of the MIT license, except for Apache HTTPClient Fluent and its dependencies which are provided by Apache under their license

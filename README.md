# mewnbase_papermaps
Opening the map drains energy and doesn't pause the game anymore.

 - This is a beta quality so ensure you backup your saves or use a second install.
 - This is only tested for _0.51.2_ and _Windows_.

## Download
From the [Releases page (Just the JAR file)](https://github.com/StuartKent17/mewnbase_papermaps/releases)

## Installation

1. Add the `papermaps.jar` file to the `/game/` directory in the Mewnbase install.
2. Edit `config.json` in the main directory. Add: `"game/papermaps.jar"`

Your config.json should now look like, the order matters as we are overriding a singular file:

    
        "classPath": [
            "game/papermaps.jar",
            "game/desktop-1.0.jar"
        ],
    
## Notes
This method of loading mods can be abused to run code that can damage your computer. Only install from reputable sites.

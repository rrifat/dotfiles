# Starbound JSON File Syntax Highlighter
This extension adds support for the various Starbound JSON files used to create mods and content for the game.

All file types as of the 1.0 release should now be included. If I have missed anything I can be found on the [Starbound Community](http://community.playstarbound.com/members/kyleetehkitty.261992/), leave a message if you find any missing file types.

I still plan to start building JSON Schemas for various file types while I work on my mod, and adding them to this extension as I go. Got a bit bored with modding back in February waiting for 1.0 and it never happened xD.

#### Update 7/26/2016 - Starbound was finally released \0.0/
* .achievement
* .event
* .itemdescription
* .tooltip
* .radiomessages
* .metadata
* Extension will now show anything JSON like as Starbound JSON to cover future additions by Chucklefish in post 1.0 updates
* .config and .patch no longer matches to JSON due to a conflict with the built in VSCode XML and Diff extensions. Here is a workaround.
Add the following to the Visual Studio Code settings.json will fix these for now
```json
    "files.associations": {
        "*.config": "json",
        "*.patch": "json"
    }
```

I will keep tinkering with the above to see how to get around it, maybe it is just a bug \\o.o/

#### Update 2/8/2016
* Updated extension to new Visual Studio Code version

#### Added 12/20/2015
* .old
* .disabled
* .config
* .behavior
* .configfunctions
* .cursor
* .dungeon
* .effectsource
* .activeitem
* .weaponcolors
* .combofinisher
* .altability
* .wiretool
* .liquid
* .monstercolors
* .partparams
* .bush
* .grass
* .structure
* .spawntypes
* .stagehand
* .tenant
* .treasurechests
* .vehicle

### List of all Starbound file extensions included:

* .modinfo
* .object
* .item
* .head
* .body
* .back
* .legs
* .chest
* .config
* .frames
* .aicommand
* .aimission
* .animation
* .biome
* .cinematic
* .codex
* .codexitem
* .damage
* .effectsource
* .unlock
* .liqitem
* .coinitem
* .sword
* .consumable
* .gun
* .instrument
* .matitem
* .generatedshield
* .staff
* .thrownitem
* .flashlight
* .grapplinghook
* .harvestingtool
* .painttool
* .beamaxe
* .miningtool
* .tillingtool
* .functions
* .monstertype
* .monsterpart
* .monsterskill
* .namesource
* .npctype
* .parallax
* .particle
* .particlesource
* .modularfoliage
* .modularstem
* .projectile
* .questtemplate
* .recipe
* .structure
* .species
* .statuseffect
* .tech
* .techitem
* .terrain
* .ridgeblocks
* .material
* .matmod
* .treasurepools
* .weather
* .patch
* .old
* .disabled
* .behavior
* .configfunctions
* .cursor
* .dungeon
* .effectsource
* .activeitem
* .weaponcolors
* .combofinisher
* .altability
* .wiretool
* .liquid
* .monstercolors
* .partparams
* .bush
* .grass
* .structure
* .spawntypes
* .stagehand
* .tenant
* .treasurechests
* .vehicle
* .achievement
* .event
* .itemdescription
* .tooltip
* .radiomessages
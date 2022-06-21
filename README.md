# Pokemon-Green-Rock
A modification of Pokemon Emerald built using [pret's disassembly][1] of the game.

# Installation instructions:

Use [FLIPS][2] to patch the .BPS file onto a clean Pokemon Emerald ROM (the option will appear as "Apply Patch"). From there, FLIPS will ask you for the clean unmodified ROM and THEN the patch (.BPS) file.

Changelog:
-----------------------------------------------------------------------------
- dismounting after surfing now properly renders ground effects
- HP bars drain faster on Pokemon with higher max HP
- running indoors!
- vsync optimization (saves battery power and processing power)
- snow weather effect is fixed and has the proper associated message
- Viewing Pokemon Summaries is now less expensive on hardware and optimized
- you can now change Pokemon nicknames from the party menu!
- TMs are now infinite use!
- PLA-style change moves option!
- removal of redundant strings
- updated sitrus berry effect to Gen 4+
- physical/special split
    - corresponding icons in the summary screen
- can forget HM moves!
- Linking Cord from PLA!
- Impossible Evos have been changed
    - any items used for trading evos are now usable items like evolution stones
    - also now available in the Lilicove Department Store
- a new NPC in Slateport City now gives you a Scyther!
- updated Figy/Wiki/Mago/Aguav/Iapapa berry effects to Gen 4+
- new scripts have been added
    - you can now obtain all 3 starters without trading!
- the first option for berries is now use as opposed to check tag

### Moves: (Most have been changed to their Gen 7+ attributes)
- Cut
    - Type: Normal -> Grass
    - Power: 50 -> 60
    - Accuracy: 95 -> 100
- Fly
    - Power: 70 -> 90
    - Accuracy: 95 -> 100
- Rock Throw
    - Accuracy: 90 -> 100
- Rock Slide
    - Accuracy: 90 -> 100
- Rock Blast
    - Accuracy: 90 -> 100

[1]: https://github.com/pret/pokeemerald    "pret/pokeemerald"
[2]: https://www.smwcentral.net/?p=section&a=details&id=11474 "FLIPS"

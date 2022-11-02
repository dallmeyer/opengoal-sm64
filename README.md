# OpenGoal Jak 1 - Super Mario 64 style

https://opengoal-unofficial-mods.github.io/

- Gameplay mimicks SM64, with:
  - Stars -> Power Cells
  - Coins -> Precursor Orbs
  - Red Coins -> Scout Flies
- Scout Flies give you an extra 2 Precusor Orbs (like Red Coins), so there are 16x7x2 = 224 extra Precusor Orbs across the entire game
- There are 9 extra Power Cells (110 total) for collecting 100 Precursor Orbs within a single level (only in levels that have at least 100)
- Any time you collect a Power Cell* or die, the entire level will be reset (except for collected Power Cells and related objects) and you'll respawn at the beginning of the level
  - *Exceptions:
    - Power Cells in the "connector" levels (Fire Canyon, Mountain Pass, Lava Tube) 
    - Power Cells from collecting 100 Precursor Orbs
- Random notes:
  - Dying in final boss originally warped you back to Geyser Rock due to missed case in the code
    - If for some reason you want to revisit this, there's a toggle under Misc Options
  - Power Cells/Precursor Orbs/Scout Flies are gold/gold/red to match Stars/Coins/Red Coins (duh)
  - Autosplitter should still work, and there's an [updated ASL file here](https://github.com/dallmeyer/opengoal-sm64/blob/main/opengoal-jak1-autosplitter-SM64.asl) which supports splitting on the Power Cells from collecting 100 Precursor Orbs
  

<img src=https://github.com/dallmeyer/opengoal-sm64/blob/main/ModImage.png width=400/>

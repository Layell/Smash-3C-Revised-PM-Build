=======================================================================================
Guide for Adding ROB Costumes
=======================================================================================

As per the LegacyTE_PSA_edits file, Kart ROB has specific effects in slots 20-29.

Only add Kart ROB costume files in the 20-29 range. Due to bone-specific requirements, your game will crash otherwise.

In addition, for tag-based costumes, any ROB costumes loaded over Kart ROB without the additional wheel bones will crash the game.

ROB uses individual Etc files for each costume. These files include a GFX bank, the "ef_robotX[..]" ARC, that stores his armtrail texture/model. When adding ROB costume slots, make sure to copy an existing RobotEtc file as well, and rename it to match the costume number.

Inside the RobotEtc file, rename the ef_robotX[..] ARC to match the new costume number, and make the proper adjustments to the texture inside. The spintrace texture should match ROB's arm color.
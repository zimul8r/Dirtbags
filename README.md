# How To Use This Sheet
## Dirtbags! Third Party License
## Sheet Tabs
At the top of the page are three buttons: PC, THREATS, and HELP.

The PC button brings you to the main player character sheet. The THREATS button brings you to the monsters sheet. The HELP button brings you to these directions.

## Dice Manager
Ths sheet has a number of built-in features to help you manage moving the dice totals around amongst the various dice pools. The Dice Manager check box turns these features on and off. If you turn off the Dice Manager, then all of the dice manipulation buttons will be disabled. With the Dice Manager off you must do all of the dice accounting manually between the different dice pools.

The only automated feature that is not disabled by this checkbox is the rolling buttons: ACTION, FIRE, and RESIST. When these buttons are pressed to roll the dice, they will automatically move the rolled dice to the Reserve section.
For the remainder of these instructions, all dice management features are marked with (DM).

## The Player Character Sheet
This sheet is based on the Dirtbags! character sheet, with some modifications to aid in online play and some concessions made due to the Roll20 system.

### Action, Ammunition, and Reserve
Each dice pool has a pair of counters for the current and maximum dice counts, separated by a /. In the Ammunition Pool section there are 3 counter pairs for tracking the ammo of up to 3 equipped weapons. There are no automatic dice management features activated by these dice pool controls. There are no maximum values set for any of these dice counters. The minimum for each of these counters is zero. This is to allow for house rules and to ensure that you can always reset these pools manually should they ever become out of sync during play.

(DM) The Action Pool REPLENISH button pulls expended dice from the RESERVE pool back to the Action Pool.

(DM) The 3 RELOAD buttons in the AMMUNITION POOL section do the same for expended ammo dice for each of the three weapon ammo pools.

### The ROLL POOLS
At the top left of the sheet there are 4 colored ROLL POOLS: yellow for ACTION rolls, and red, green, and blue for FIRE rolls for different weapons.

(DM) When you increase the number of dice in the ACTION ROLL POOL, it decreases the dice in the ACTION POOL section by that same amount.

The Dice Management tools will only update the ACTION POOL after you have finished updating the ACTION ROLL POOL value and clicked outside of the ACTION POOL control.
### The ACTION Button
Clicking the ACTION button performs and Action roll with the number of dice in the ACTION ROLL POOL. A window will pop up to allow you to choose the difficulty for the roll. Then the results will be displayed in the chat window. The results will show the type of roll (Action, in this case), the number of dice rolled, the Difficulty, and the number of successes. By hovering your mouse over the Successes number, you can view the individual dice results. You will need to use this feature to determine if you have scored a crit and get to recover an additional die from your reserve.

When you click the ACTION button, the dice in the ACTION ROLL POOL will automatically move to the RESERVE. This is not a DM feature and cannot be disabled.
If you click on the ACTION button when the ACTION ROLL POOL is empty, a roll will occur with o dice and o successes.

### The SUCCESSES/CRIT Button
It turned out to be quite difficult to automatically return dice that rolled successes to the ACTION POOL. We may solve that one day, but for now, you can use the SUCCESSES/CRIT button to recover dice from the RESERVE into your ACTION POOL. (DM) Simply click the SUCCESSES/CRIT button once for each success you had in the action roll and those dice will move out of the RESERVE. You can also click it once if you scored a crit to claim your extra RESERVE die. If there are no dice in RESERVE, clicking this button does nothing.

### The FIRE Button
The FIRE button works exactly like the ACTION button, except instead of making a roll using the number of dice indicated in the ACTION ROLL POOL, it makes a dice roll using all of the dice in all three AMMUNITION ROLL POOLs. It is up to you to load up these pools with the appropriate number of dice for your weapons' firing modes.

When you click the FIRE button, all the dice in the AMMUNITION ROLL POOLs will automatically move to the RESERVE. This is not a DM feature and cannot be disabled.
If you click on the FIRE button when all of the AMMUNITION ROLL POOLs are empty, a roll will occur with o dice and o successes.

### The RESIST Button
The RESIST button works exactly like the ACTION and FIRE buttons, except that it makes a dice roll using all of the dice in the ACTION ROLL POOL and all three AMMUNITION ROLL POOLs. It is up to you to load up these pools with the appropriate number of dice for your weapons' firing modes.

When you click the RESIST button, all the dice in the ACTION and AMMUNITION ROLL POOLs will automatically move to the RESERVE. This is not a DM feature and cannot be disabled.
If you click on the RESIST button when the ACTION ROLL POOL and all of the AMMUNITION ROLL POOLs are empty, a roll will occur with o dice and o successes.

### The CLEAR POOLS Button
(DM) When you click the CLEAR POOLS button, all of the dice in all 4 ROLL POOLS are moved back into their respective action and ammo pools.

### PERSONAL EFFECTS, TRAITS, P.O., And FALLOUT
These 4 text areas are for listing your equipment and other details. The boxes will scroll if they are filled, or you can use the lower right corner handles to resize them.

### Other Stats
All of the other stats fields, M.I.L.K., Carrying Capacity, Confirmed Kills, Credits, and Bones, Cunning, Nerves, and body stats, are there to record and track your stats.

(DM) Whenever you change the current value of Bones, Cunning, or Nerves, your ACTION Maximum will update to the sum of those three stats.

## The Threats Sheet
This sheet is based on the Dirtbags! threat profiles, with some modifications to aid in online play and some concessions made due to the Roll20 system.

The Threats Sheet is a threat profile for one monster or group of monsters. The relevant stats for the monster type can be filled in. Since Dirtbags! often call for multiple monsters of the same type, there are 6 monster blocks at the bottom of the tab.

The RESET ALL HITS button sets the hits on all 6 monster blocks to the starting HP of the monster type from the HP setting.

Each of the six monster blocks has it's own Hits field for keeping track of damage dealt to the monster. Since each block has its own Hits field, you can track the damage to each monster individually.

Each monster block can be linked to a different token. Drag a token from the Journal to the map for each copy of the monster you want to use. Then seelct them one at a time and click the corresponding Link Selected Token button for the block you want to link to that token. Once linked, the Hits in the monster block and Bar 1 of the token should be linked. The link button will also set the max HP onthe token to the monster type HP value and change the token name to an indexed copy of the monster type name.

NOTE: There seems to be a little "glitchiness" in the Link button that I haven't fully diagnosed yet. If the link doesn't populate the max HP on the token, change the linked Hits value on the monster block a few times and try the Link button again. When everything is properly linked, the green health bar should appear above the icon with the correct number of current hits for the monster block.

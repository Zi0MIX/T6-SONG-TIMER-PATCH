# History of broken versions

- 4.0 - Broken perma perks -> Fixed in 4.1. </br>
- 5.0 - Inaccurate velocity meter -> Fixed in 5.1. </br>

# Changelog

See detailed information about changes introduced in the patch

## Version 3

- Seconds decimals (ms) have been reduced to one, due to 2nd decimal being inaccurate at times. Eg: `.8 == 800ms`
- Mob song names have been fixed.
- Patch prints have been improved.

## Version 4

- Attempt counter has been added. It will reset between maps and game restarts.
- All perma perks are now awarded at the beginning of each game on maps supporting them.
- Progress counter has been added for Access Level 1 & 2.

## Version 4.1

- Fixed an issue where permaperk would not be lost and would remain active for the entire game if player would break permaperk conditions within first few seconds of the game

## Version 5

- Removed access levels, players agree to have all the functionalities in competitive runs
- Added Velocity meter and Gspeed display
- Improved zone HUD handling

## Version 5.1

- Fixed Z axis movement speed values counting towards velocity meter

## Version 6

- Added point drops tracker.
- Added First Box detector.
- Made zone hud less visible.
- Made optional First Box module (separate file).

## Version 7

- Changed tech from `irony.dll` to `gsc-tool`
- Applied more proper gsc style to the codebase
- Scrapped old timing system and created it from scratch
- Songs now have splits
- HUD has been completely reworked
- Added optional built-in leaderboard system
- First box functionality moved to the main file and made optional (based on FR FIX)
- Box is now forcebly moved to Yellow House backyard on Nuketown
- Scrapped old permaperk system and applied one from FRFIX

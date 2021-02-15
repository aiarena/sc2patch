# Starcraft 2 backwards compatability patch
Modifies map files to replicate behavior of the live version of Starcraft 2 in patch 4.10.0

Intended for use with latest Sc2 linux binary 4.10.0 to speed up AI competition & training

## Download
https://github.com/shostyn/sc2patch/raw/master/Maps/506.zip

## How to use
A version manager should no longer be required to adjust IDs between game versions.

To detect these maps query map name through the Sc2 API and all map names will end with "5.0.6"

## Changelog
### 20/02/04
Added 5.0.6 Maps
- All IDs (units\abilities\buffs\etc) are now equivelant between these maps and 5.0.6
- Shield batteries now use "Ex5" abilities to match version 5.0.6
- Battlecruiser & Oracle weapons are visible through the API
- Maps should work on 5.0.6 live without issues (not thoroughly tested)

Bugfixes
- Fixed some instances of "LE" appearing in map name
- Warp prism mineral cost 200 -> 250 to match 5.0.6

## Known Issues
- Stop ability on shield battery disables autocast for Shield Recharge on 4.10.0
- No localized strings exist for non enUS clients
- Acceleration zones don't appear on mimimap
- No fade in on cloak animation from mothership

## How to apply the patch manually to a map
https://www.youtube.com/watch?v=1dtGEkLXv3E

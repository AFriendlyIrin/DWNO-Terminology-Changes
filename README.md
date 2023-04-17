# Digimon World: Next Order - Terminology Changes
Cosmetic mod altering some terminologies in Digimon World: Next Order. Changes Digimon stage names to their Japanese counterparts, fixes some questionable terminology translations, and tweaks a few other names to ones I believe flow better or make more sense.

The English language CSVs have been provided here if you wish to make your own adjustments. **Note: If you are editing the CSVs with spreadsheet software, you must import the hash column as text to avoid errors.**

## List of Changes
```
In-Training       → Baby
Rookie            → Child
Champion          → Adult
Ultimate          → Perfect
Mega              → Ultimate
Ingredients       → Food
DigiWhitegold     → DigiPlatinum
MegaGargomon      → SaintGargomon
Hand-to-Hand      → Martial
Weapon/Apparatus  → Machine
[Skill] Type      → [Skill] System
Reverse Type      → Rebirth System
Zeal Injection    → Passion Injection
Mental Trainer    → Mind Over Matter
Mister Cook       → Mister Cuisine
Real X Hunt       → Rare X Hunt
Arena             → Arcade
Ohguino Wasteland → Ohguino Wilderness
Faulty Ex Machina → Fault Ex Machina
Training Failure  → Care Mistake
  (in digivolve screen, TF → Mistakes)
Digivolution Conditions → Conditions
  (to make the text less squished)
Call Jijimon      → Jijimon's Report
```
Additionally, there are a few more detailed changes:
* Some Digimon's special moves have been changed to more accurate translations (most notably, Pummel Whack → Fist of the Supreme King & Diamond Storm → Fox Arrows, with the quiz questions updated accordingly)
* Fixed the error in Vikemon's contingency message (he now says to get rid of any Black Digitrout instead of "I'll take that off your hands")
* Corrected Ophanimon's pronouns to female in her recruitment message
* Fixed an it's/its mistake in one of the item descriptions
* Reverted Kuro-rin and Kuro-cchi to their original localized names Blackie and Blackosaurus
* Added information to attack skill descriptions about the magnitude and duration of added buffs, as well as information about attack skills that self-buff
  * Changed Upgrade's description to accurately convey that it buffs all stats, not just strength and stamina
* Tweaked some odd wording in attack skill descriptions ("much damage" changed to "huge damage")

## Installation
Only the raw asset files are provided. You will need to pack them into `DigimonDataR.cpk` using a CPK file tool. If you do this, the mod is compatible with the Switch version on any custom firmware with LayeredFS compatibility.

## Known Issues
 * Replacing all 6 files in the CPK causes the game to hang when entering Jijimon's house. It's not any particular file, it's just any 6 file changes. I have no idea why this happens, but choose 1 file to exclude until the problem can be resolved.
 * Repacking the CPK, at least with the CPK tool I'm using (CPK File Browser), causes the game to hang when attempting to load any story cutscene.

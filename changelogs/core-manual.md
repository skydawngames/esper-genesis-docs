---
layout: default
title: Core Manual Changelog (Foundry VTT)
permalink: /changelogs/core-manual
---

Release notes for the **Esper Genesis Core Manual** module.

The current release requires Foundry VTT v14 and the dnd5e system
(minimum 5.0.0, verified against 6.0.6).

---

## 1.2.1

- Fixed an error that prevented player starships from opening for anyone running the Core Manual without the *Master Technician's Guide* active. Ships carrying starship weapons with a hardpoint value keep their hardpoint totals either way.
- Esper Genesis skill names now appear in the skill choice dropdown during character advancement. Renamed skills are sorted back into alphabetical order.
- Fixed the player starship sheet displaying the ship's name twice when using dnd5e v6.0.
- Fixed NPC starship sheets and tokens not opening in dnd5e v6.0.
- Fixed Effects (PC) and Condition Immunities (NPC) labels in dnd5e v6.0.
- Fixed the expertise tooltip on NPC starship saving throws.
- Esper Genesis weapons, armor and tools now display correctly during character advancement.
- Tool checks using Esper Genesis tools now apply tool proficiency correctly.
- Fixed Paragon's Imbued Strike number of uses.
- Fixed Storm Guard's Weapon Surge damage. Also fixed ongoing damage and damage types for Frost Strike and Flame Burst.
- Corrected number of powers that can be prepared by Engineers and Sentinels. Melder limit now matches the talents known at each level.
- Fixed duplicate identifier warning for Warrior.
- Characters created before this version keep their existing copies of these classes and features. Remove and re-add Imbued Strike and Weapon Surge effects to acquire fixes, and update the preparation formula on an existing Engineer, Sentinel or Melder class.

## 1.2.0

- Fixed bug where NPC starships could not roll initiative. NPC starship initiative also displays the pilot’s ability modifier when rolled as intended.
- Armor and shield upgrade properties (from the *Master Technician's Guide*) can now be set on armor. Added the Honed and Reflexive armor properties, and the Concealed and Breach weapon properties.
- Finesse weapons now use Dexterity on attack rolls as intended.
- Fixed bug where certain weapon attack activities could not be edited.
- All equipment items are now priced in cubil instead of gp.
- Added the Stun Grenade, which was missing from the Equipment compendium.
- Grenades now marked as Thrown and Special while remaining consumables.
- Fixed misnamed NPC starship tokens.
- Restored missing icon to the Esper Powers tab of the PC sheet.
- A player starship’s AC is now visible in combat and chat cards.
- Journal styling updated to match Threats Database and MTG. Inline subheads are tinted in dark mode.
- Importing an NPC starship into a world no longer causes an error during Foundry start-up.
- Added NPC starship stat block embeds to journal pages.
- NPC Starship sheet: Fixed missing Action Stations on NPC starship sheet. Fixed listing order of ship features.
- Split PC starship "Max Payload" field to instead show caps for weapon systems and hardpoints. Added hardpoint features from the *Master Technician's Guide*.
- Fixed bug on PC ship sheet where optional and propulsion systems doubled on drag and drop.
- Added type flags to equipment and systems on player starship sheet.
- Changed main compendium folder name from "Esper Genesis" to “Esper Genesis Core Manual”.
- Updated book source of all esper powers to “Esper Genesis Core Manual”.
- Removed unused icons in library folders. These are not intended for distribution with the product.

## 1.1.0

- Restored display of Esper Genesis skill lists on item sheets. Skills displayed depend on the type of sheet selected (DnD or Esper Genesis).
- Restored 70 missing advancements that were removed in error during a prior update.
- All 12 backgrounds now grant their skill, tool and language proficiencies.
- Fixed advancements for the following subclasses: Animota, Battlemind, Celestian, Defender, Dreamshaper, Infiltrator, Investigator, Metakinetic and Psychogenic.
- Fixed the Adaptable and Minor Telekinetic feats.
- Pilot, Scholar and Shipper/Transporter grant Astrophysics, and Techie grants Mechanics to match the v1.0.3 skill update.
- Restored the D&D language list so it is available when the Core Manual is active. Those languages are now listed under "D&D Standard Languages" and "D&D Rare Languages". Existing characters are not affected.

## 1.0.3

- Esper Genesis skill names are now restricted to the character sheet. Players can switch to the standard 5E SRD sheet, which displays the Animal Handling, Arcana, History, Nature and Religion skills while an Esper Genesis character retains their own skills, allowing both to be playable in the same game.
- Astrophysics and Mechanics now use skill keys with a matching ability.
- A one-time update script for Astrophysics and Mechanics runs for existing characters on load, with a preview of what will change. It can be re-run from the Esper Genesis Core Manual module settings in the Game Settings menu.
- Esper Genesis skill names now appear in roll dialogs and chat cards.

## 1.0.2

- Journal headings no longer draw their underline across floated artwork.
- Fixed the mouseover tooltip to display the correct skill on the Esper Genesis PC sheet.

## 1.0.1

- Typo fixes and starship sheet calculation correction.
- Added missing advancements to backgrounds and subclasses.

## 1.0.0

Initial release.

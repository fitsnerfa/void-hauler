# VOID HAULER Changelog

## v1.5.0 — Black Box Flight Recorder

- Renamed the Recovery Center to the **Black Box Flight Recorder**.
- Expanded recovery history from 10 to **15 flight logs**.
- Added **Progression Lock** checkboxes.
- Up to **5 locked logs** are permanently protected from rotation.
- Added a warning when attempting to lock a sixth flight log.
- Restoring an older log archives the current timeline before loading it.
- Quick-save timer changed to every **2 minutes**.
- Added five-minute emergency recovery checkpoints.
- Added labeled milestone logs for captain levels, Contract Vessel levels, named WANTED pirate defeats, and Contract Vessel acquisition.
- Export remains read-only and downloads the stored JSON save.
- Import, restore, and new-game actions archive the current flight first.

## v1.4.9 — Reliable Export

- Changed Export Save to read local browser storage synchronously.
- Download begins directly from the user click to avoid browser blocking.
- Added clear download status feedback and timestamped filenames.

## v1.4.8 — Fortified Saves

- Added multiple timestamped recovery snapshots.
- Added Recovery Center with restore, export, raw-view, and export-all tools.
- Blocked title-screen/default-state writes before game initialization.
- Starting over requires typing `NEW GAME` and archives the existing game.

## v1.4.6 — Contract Vessel

- Frigate Bounty awards a Contract Vessel.
- Added vessel levels and certifications at 25, 50, 75, 100, and 150.
- Added FP upgrades for Mining Laser, Cargo Hold, Gas Hold, Engines, and Hull Plating.
- Added visible vessel upgrade graphics.
- Added material transfer with **T**.
- Standardized sticky close buttons on major menus.

## v1.4.5 — WANTED Bosses

- Added persistent named pirate bosses with unique colors, escorts, health bars, labels, and radar pulses.
- Every pirate now drops Scrap Metal based on ship class.
- Distress salvage increased to 100–200 Scrap Metal.
- Equipment restricted to hideouts and dungeon-style encounters.
- Added copyright notice.

## v1.4.4 — Browser Saves

- Added Launch / Continue, Export Save, Import Save, save status, and reset confirmation.
- Preserved the existing `ore:save` browser-storage key.

## v1.4.3 — Selective Selling

- Replaced Sell All with cargo checkboxes and Sell Selected.
- Added protection and confirmation for quest resources and Water.

## v1.4.2 — Renewable Space

- Increased asteroid population.
- Added edge-of-space warnings.
- Improved renewable Dark Matter behavior.
- Increased Corvette Scrap rewards.

## v1.4.1 — Crew, Hideout, and Quest Journal

- Added the Quest Journal on **J**.
- Expanded crew and armory equipment systems.
- Added permanent pirate hideout progression.
- Added equipment upgrading and recycling.

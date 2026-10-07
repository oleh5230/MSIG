Sound addons I use personally (excluding default GAMMA addons).

- **If you encounter issues with this setup, report to me first, not addon authors or support channels**
- **Disabling default GAMMA sound addons is not required**
- **All of addons below are safe to install/uninstall mid-playthrough (except Arrival)**

<img width="537" height="303" alt="image" src="https://github.com/user-attachments/assets/4941e5e5-3b0c-4cac-ad07-1a16228011d2" />

- [Spatial Audio Rework](https://www.moddb.com/mods/stalker-anomaly/addons/spatial-audio-rework) - indoor reverberations + better indoors detection for MSIG rain
- [Oleh's Miscellaneous Sound Improvements (MSIG)](https://github.com/oleh5230/MSIG) - mandatory for Oleh's addons
- [Oleh's Weapon Sounds (WSTFG)](https://github.com/oleh5230/WSTFG) - weapon foley and gunfire
- [Oleh's MovementSFX](https://github.com/oleh5230/MovementSFX) - player movement
- [Oleh's NPC Footstep Sounds](https://github.com/oleh5230/NPC-footsteps) - stalker and mutant movement
- [Ukrainian voices](https://www.moddb.com/addons/dxml-anomaly-ukrainian-voices) - extra voices variety
- [Audio Expansion](https://www.moddb.com/mods/stalker-anomaly/addons/audio-expansion) - ambient beds:
  - None *(Inventory and core)*
  - [GAMMA] Ambience Basic
  - [ADDON PATCH] S2 HoC Soundscape Overhaul
  - [GAMMA] Storms and PSI Blowouts
  - [GAMMA] Detectors *(includes a script with questinable performance)*
  
  Other modules are left unselected.

- [S.T.A.L.K.E.R. 2 HoC - Soundscape](https://www.moddb.com/mods/stalker-anomaly/addons/stalker-2-hoc-ambience-overhaul-for-anomaly) - actual sound spots to maps instead of just fake ambience **(currently has an issue of some MCM toggles not working, resulting in duplicate rain sounds and questionable thunder sounds)**
  
- [Arrival](https://www.moddb.com/mods/stalker-anomaly/addons/arrival-anomalies) **(new game required)** - anomalies sounds and visuals

  By default Arrival affects gameplay, if you want to keep SFX and VFX only:
  - Install the mod via Mod Organizer, select modules to your preference
  - If you selected 'Barrels and shit Scattered, keep these files': `scripts/barrel_flame_aoe.script`,`scripts/barrel_flame.script`,`configs/mod_system_zz_arrival_explosions.ltx`
  - Delete `scripts` folder (except `arrival_environmental_particles.script` if you selected flying seeds/leaves)
  - Delete `configs` folder (except `zones` and `scripts/generators` subfolders and `mod_system_SSS_zones.ltx`)
  
  **If you have issues after doing this don't report to Semitone or support channels, ask me or reinstall the full mod.**
  
- [Relax'ing Ambience Overhaul](https://www.moddb.com/mods/stalker-anomaly/addons/relaxing-the-ambience-overhaul-rao-upd06152025) (subjective, try it if you're bored of GAMMA soundtrack)


## Incompatible addons
- Dark signal Amplified footsteps/Audio Expansion Movement - disable MovementSFX to use a different movement addon
- Dark signal Amplified Item and UI/Audio Expansion Inventory - reinstall MSIG without the optional module to use a different UI addon

## Recommended in-game settings:
- SFX Volume (`snd_volume_eff`): `0.5` - otherwise some sounds may have imbalanced volume
- Rendering Distance (World) (`rs_vis_distance`): at least `0.9` (50% of the slider) - otherwise distant gunfire sounds would not be audible

**Beware that distant gunfire sounds may have a significant impact on performance.**

## Recommended MCM settings:
- Spatial Audio Rework\NPC-specific ray detection: off

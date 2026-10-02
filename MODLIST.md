Only sound addons I use personally (excluding default GAMMA addons)

- **If you encounter issues with this setup, report to me first, not addon authors or support channels**
- **Disabling default GAMMA sound addons is not required**
- **All of addons below are safe to install/uninstall mid-playthrough (except Arrival)**

<img width="537" height="303" alt="image" src="https://github.com/user-attachments/assets/4941e5e5-3b0c-4cac-ad07-1a16228011d2" />

- [Spatial Audio Rework](https://www.moddb.com/mods/stalker-anomaly/addons/spatial-audio-rework)
- [Oleh's Miscellaneous Sound Improvements](https://github.com/oleh5230/MSIG)
- [Oleh's Weapon Sounds](https://github.com/oleh5230/WSTFG)
- [Oleh's MovementSFX](https://github.com/oleh5230/MovementSFX)
- [Oleh's NPC Footstep Sounds](https://github.com/oleh5230/NPC-footsteps)
- [Ukrainian voices](https://www.moddb.com/addons/dxml-anomaly-ukrainian-voices)
- [S.T.A.L.K.E.R. 2 HoC - Soundscape](https://www.moddb.com/mods/stalker-anomaly/addons/stalker-2-hoc-ambience-overhaul-for-anomaly)
- [Audio Expansion](https://www.moddb.com/mods/stalker-anomaly/addons/audio-expansion):
  - None *(Inventory and core)*
  - [GAMMA] Ambience Basic
  - [ADDON PATCH] S2 HoC Soundscape Overhaul
  - [GAMMA] Storms and PSI Blowouts
  - [GAMMA] Detectors
  
  Other modules are left unselected
  
- [Relax'ing Ambience Overhaul](https://www.moddb.com/mods/stalker-anomaly/addons/relaxing-the-ambience-overhaul-rao-upd06152025) (subjective, try it if you're bored of GAMMA soundtrack)
- [Arrival](https://www.moddb.com/mods/stalker-anomaly/addons/arrival-anomalies) **(new game required)**

  By default Arrival affects gameplay, if you want to keep SFX and VFX only:
  - delete `scripts` folder (except `arrival_environmental_particles.script` if you selected flying seeds/leaves)
  - delete `configs` folder (except `zones` and `generators` subfolders and `mod_system_SSS_zones.ltx`)
  
  **If you have issues after doing this don't report to Semitone or support channels, ask me or reinstall the full mod**


## Incompatible addons
- Dark signal Amplified footsteps/Audio Expansion Movement - disable MovementSFX to use a different movement addon
- Dark signal Amplified Item and UI/Audio Expansion Inventory - reinstall MSIG without the optional module to use a different UI addon

## Recommended in-game settings:
- SFX Volume (`snd_volume_eff`): `0.5` - otherwise some sounds may have imbalanced volume
- Rendering Distance (World) (`rs_vis_distance`): at least `0.9` (50% of the slider) - otherwise distant gunfire sounds would not be audible

**Beware that distant gunfire sounds may have a significant impact on performance.**

# Working Title G3000

### Latest version: v0.2.0 PRE-release 2

### Changes from v0.2.0 PRE-release 1
- Fixed compatibility issue with G1000 mod causing avionics screens to freeze.

### Description
This is a mod for MSFS2020 that aims to improve the in-game G3000. The goal is to bring functionality closer to the real-life G3000, with a focus on both features and layout/UI. Most of development and testing was done with the TBM 930, and the TBM 930 version of the G3000 pilot's guide was used as the primary reference.

This mod was created with cross-compatibility in mind. It modifies the minimum number of base files possible to achieve its goals, so it should be compatible with most other mods, including all other WorkingTitle mods. However, because of the nature of the mod, it will conflict with other mods that make changes to the G3000.

**NOTE:** This version of the mod only makes changes to the TBM 930 for now.

### Installation
To install, copy the `workingtitle-g3000` folder from the zip file into your `Community` directory.

### Release Highlights (v0.2.0-pre2)
Please refer to the changelog for a more detailed description of updates.

- The G3000 mod is now integrated with the WorkingTitle ecosystem! This has allowed the addition of the following features:
  - Certain G3000 settings (including all newly added ones) are now saved across flights.
  - SVT toggle for the PFD.
  - Altimeter baro units toggle between IN HG and HPA.
- More new navigational map features:
  - Added range ring/range compass overlay.
  - Map zoom behavior now more closely matches the real G3000.
  - Added ability to show track vector, altitude intercept arc, and fuel range ring.
  - Added city display backed by a worldwide 26,000-city database from simplemaps.
  - Toggle between none/absolute/relative terrain modes.
  - Auto-North Up.
- Terrain colors on the navigational map have been changed to better match the real G3000.
- Bug Fixes:
  - Map scroll is no longer broken in HDG/TRK UP modes.

### Known Issues
- \[PFD\] (Vanilla issue) Co-pilot PFD softkeys are nonfunctional.
- \[NavMap\] (Vanilla issue) The road overlay for the navigational map will sometimes fail to draw roads close to the aircraft, instead prioritizing roads farther away. This usually only happens when the map range is set to large values (>100 NM).
- \[NavMap\] (Vanilla issue) Sometimes airport symbols will not update on the navmap. Zooming in then back out will usually fix it.
- \[NavMap\] At large map ranges (>250 NM), map symbols may not line up correctly with the underlying terrain. This is because the terrain map is projected differently from the symbols. The effect is worse at the edges of the map and also worse at high latitudes.

### Credits
- Custom city database is sourced from simplemaps (simplemaps.com/data/world-cities) under the CC Attribution 4.0 license.
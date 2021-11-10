
## [git] - 2021-11-09
(Poikilos; starting by importing 2018 b3d into Blender)

### Added
- Markers

### Changed
- Set all bones to single arrow (See utilities/blender/change_every_empty_to_single_arrow.py in https://github.com/poikilos/EnlivenMinetest)
- Scale animations by .25 starting at second frame (frame 2, though doc says frame 1 is start of idle)
  - New framerate (mobs redo `speed`) is 15.
  - New end frame is 702 (formerly 2800, though doc says 2801)
  - See updated readme for new sequences.

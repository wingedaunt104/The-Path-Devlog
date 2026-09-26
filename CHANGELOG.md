# The Path - Changelog

This file tracks major development milestones, gameplay systems, improvements, and fixes made during the development of The Path.
## September 26, 2026

### Added
- Completed the core Storming Peaks dynamic weather system
- Added GPU-simulated rain throughout the level
- Added player-following rain with automatic reattachment after respawn
- Added looping rain ambience
- Added randomized close and distant thunder sound pools
- Added distance-based thunder selection and thunder delay
- Added custom Niagara lightning impact explosions
- Added electric flash and outward energy streak effects
- Added parkour lightning blast zones
- Added directional lightning knockback based on strike location
- Added custom ragdoll death impulse support
- Added stronger physics-based lightning deaths that launch the ragdoll away from the impact
- Preserved existing projectile ragdoll behavior using fallback impulse logic

### Improved
- Improved lightning strike frequency and parkour hazard pacing
- Improved thunder variety and spatial feedback
- Improved storm atmosphere and environmental audio
- Improved Niagara performance by moving rain simulation to GPU Compute
- Improved lightning impact readability with larger flashes and electric burst effects
- Improved death feedback by combining ragdoll physics with directional impact forces
- Improved the ragdoll system so different hazards can provide different death impulses

### Fixed
- Fixed rain not reattaching after player respawn
- Fixed projectile deaths failing to continue through the normal respawn sequence after adding custom lightning impulses
- Fixed lightning-affected ragdolls always flying in the same world direction
- Fixed repeated Niagara lightning impact effects by converting emitters to one-shot lifecycle behavior

### In Progress
- Continuing development of the Storming Peaks parkour course
- Expanding ruins and traversal sections
- Final lighting and atmosphere polish
- Further tuning lightning hazard balance and impact strength

## September 23, 2026

### Added
- Added dynamic thunder audio to Storming Peaks lightning strikes
- Added separate close and distant thunder sound pools
- Added randomized thunder sound selection to reduce repetitive audio
- Added distance-based thunder selection using player-to-strike distance
- Added realistic thunder delay based on lightning strike distance

### Improved
- Increased spacing between lightning strikes for more natural storm pacing
- Improved close lightning impact with sharper thunder sounds
- Improved distant lightning atmosphere with delayed rolling thunder
- Improved overall storm audio variety and environmental immersion

### In Progress
- Continuing development of the Storming Peaks parkour course
- Expanding environmental design of Storming Peaks
- Adding rain and additional storm effects
- Adding additional parkour lightning strike locations
- Continuing atmosphere, lighting, fog, cloud, and audio polish

## September 20, 2026

### Added
- Added new detailed stone ruin assets for the Storming Peaks environment
- Added modular stone wall-running surfaces designed for reliable parkour traversal
- Added additional environmental architecture for expanding the level

### Improved
- Improved wall-running geometry by keeping playable surfaces flat and collision-friendly
- Improved environmental detail and variety throughout Storming Peaks
- Improved the Blender-to-Unreal Engine asset workflow for importing custom static meshes

### In Progress
- Expanding the main parkour route
- Adding additional environmental ruins and floating rock formations
- Adding rain and additional storm effects
- Adding thunder and environmental storm audio
- Continuing atmosphere, lighting, fog, and cloud polish

## September 9, 2026

### Added
- Added parkour lightning strike locations
- Added localized 3D warning audio before hazardous lightning strikes
- Added lethal lightning radius detection using player-to-strike-point distance
- Integrated lightning deaths with the existing ragdoll and respawn system

### Improved
- Expanded the Storming Peaks parkour environment
- Improved environmental composition with additional ruins, floating rock formations, fog, and blue flame landmarks
- Improved storm lighting and level atmosphere

### In Progress
- Continuing development of the Storming Peaks parkour course
- Expanding background scenery and floating rock formations
- Adding additional parkour lightning strike locations
- Tuning lightning hazard timing and kill radius
- Improving level readability and visual guidance
- Adding rain and additional storm effects
- Adding thunder and environmental storm audio
- Continuing atmosphere, lighting, fog, and cloud polish
  
## September 7 2026

### Added
- Began development of the Storming Peaks level
- Added volumetric storm clouds and atmospheric lighting
- Added dynamic lightning flash system
- Created Niagara-based lightning bolt effects
- Added randomized background lightning strike locations
- Added lower cloud layers to create a bottomless high-altitude environment
- Added blue environmental flame effects on strutures

### Improved
- Improved Storming Peaks lighting and sky atmosphere
- Improved cloud density and storm appearance
- Improved environmental readability in dark areas

### In Progress
- Storming Peaks parkour course
- Parkour lightning hazards
- Additional environmental detailing

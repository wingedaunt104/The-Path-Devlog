# The Path - Changelog

This file tracks major development milestones, gameplay systems, improvements, and fixes made during the development of The Path.

## October 9, 2026

### Added
- Completed a major portion of the Storming Peaks parkour course
- Expanded the main traversal route with additional ruins, floating rock formations, elevated platforms, and interconnected parkour sections
- Added additional blue flame landmarks throughout the environment to help guide traversal

### Improved
- Improved the overall layout and environmental composition of Storming Peaks
- Improved visual guidance using blue flames, ruins, and large rock formations
- Improved the scale and atmosphere of the level with larger architectural structures and layered traversal areas
- Continued performance testing using Standalone Game for more accurate gameplay performance

### Fixed
- Fixed major Niagara fire visibility and camera-angle culling issues
- Increased Niagara fixed bounds for large blue flame effects so they remain visible from greater distances and wider viewing angles
- Improved consistency of large environmental fire effects throughout the level

### In Progress
- Completing the remaining Storming Peaks parkour course
- Further environment and traversal polish
- Additional performance optimization and testing

## September 2026

- **Storming Peaks Environment:** Began and substantially developed the Storming Peaks parkour level with volumetric storm clouds, atmospheric lighting, lower cloud layers, floating rock formations, ruins, blue environmental flames, modular wall-running surfaces, and an expanded traversal route. Improved fog, lighting, cloud density, environmental composition, level readability, and the Blender-to-Unreal asset workflow.

- **Lightning & Hazards:** Built a dynamic lightning system using Niagara, including randomized background and parkour strikes, localized 3D warning audio, lethal blast zones, player-to-strike distance detection, directional knockback, lightning impact explosions, electric flashes, and outward energy streak effects.

- **Weather & Audio:** Added GPU-simulated player-following rain, automatic rain reattachment after respawn, looping rain ambience, randomized close and distant thunder sound pools, distance-based thunder selection, and realistic thunder delay. Improved storm pacing, spatial audio, thunder variety, and Niagara performance.

- **Death & Ragdoll Systems:** Integrated lightning hazards with the existing death and respawn systems, added physics-based directional ragdoll impulses, supported different impulses for individual hazards, preserved projectile death behavior through fallback logic, and improved overall death feedback.

- **Fixes & Respawn Behavior:** Fixed rain failing to reattach after respawn, projectile deaths breaking the normal respawn sequence, lightning ragdolls launching in the same world direction, and repeating Niagara impact effects. Added moving-platform reset and restart logic so parkour platforms return to their starting state and become usable again after player death.

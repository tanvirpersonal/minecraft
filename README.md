# Blockscape — Browser Voxel Sandbox

Code-first Minecraft-style voxel sandbox using HTML5, CSS3, ES modules and Three.js. Static-site compatible with GitHub Pages.

## Implemented

- Chunk-based 16×16×32 voxel sections, 64-block world height
- Deterministic seeded layered noise terrain
- Plains, forest, desert, mountains, snow, beach and ocean biomes
- Caves, water and deterministic trees
- Pointer-lock first-person movement, sprint, jump and swimming
- Block breaking and placement
- Hotbar and local inventory
- localStorage world edits save/load
- Runtime chunk streaming and visible-face chunk meshing
- Day/night lighting
- Centralized custom texture asset paths

## Custom assets — no generated art

This repo does not generate textures, images, sprites, models, music or sound effects.

Upload your own block textures under assets/textures/blocks/.

Expected filenames:

- grass_top.png
- grass_side.png
- dirt.png
- stone.png
- sand.png
- wood_side.png
- wood_top.png
- leaves.png
- glass.png
- planks.png
- bricks.png
- cobblestone.png
- snow.png
- gravel.png
- water.png
- bedrock.png

Replace a file and the game will use it automatically. To move the folder or rename files, edit only src/config.js. Missing assets produce a developer warning and a code-only solid-color debug material; no fake texture is generated.

## Controls

WASD move · Shift sprint · Space jump/swim · mouse look · left click break · right click place · 1–9 hotbar · ESC pause

## GitHub Pages

Enable Pages from the main branch root. No backend is required.

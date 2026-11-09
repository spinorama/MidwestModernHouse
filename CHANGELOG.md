# Changelog — American Midwestern Modern House (`MidwestModernHouse`)

All notable versions and milestones of the **American Midwestern Modern House (840 Estate)** 4-Mode WebXR architectural experience are documented in this file.

---

## [v1.0.0] — 2026-11-09
### Initial Release — 4-Mode WebXR Experience & Minimalist Blocky Cat Gallery
- **Blender Architectural Preparation (`midwest_modern_house.glb`)**:
  - **Step 1 (`Roof_Group`)**: Grouped the main butterfly `roof` and all 88 `m_ceiling*` interior ceiling assemblies under `Roof_Group` (`Set_house -> Roof_Group`) so the entire roof and ceiling system can be toggled on/off (`🏠 Roof`) for cutaway floorplan inspection.
  - **Step 2 (`Context_Group`)**: Added lightweight mid-century suburban neighborhood context (`Ctx_Lawn_*`, `Ctx_WestHouse_*`, `Ctx_EastHouse_*`, `Ctx_SouthWest_*`, `Ctx_SouthEast_*`, `Ctx_Tree_*`) aligned with the lot's neighboring driveway aprons, toggleable via `🌳 Context`.
  - **Step 3 (`m_cat_art_vcol` — Minimalist Blocky Cat Gallery)**: Converted all 19 figures across all 15 matted wall picture frames (`slot_10` Entry Foyer & `slot_9` East Wing Gallery Hallway) plus all 5 two-tone horizon wall canvases (`slot_8` Home Office, `slot_7` South Bedroom, `slot_1` Primary Bedroom) into **minimalist geometric blocky cats** in the exact same 3D relief style (wide cat heads, pointed triangular ears, inner ear triangles, minimalist geometric eyes & nose, tuxedo chest bibs, and upright hooked cat tails).
  - **Step 4 (`Cameras_Group` & `Waypoints_Group`)**: Created 17 verified camera viewpoints and floor waypoints covering every unique interior room and exterior space.
- **4-Mode WebXR Single-Page Application (`index.html`)**:
  - **Mode 1 (`🖥️ 1 · 3D View`)**: Desktop mouse look + right-drag pan + scroll/WASD locomotion; Mobile phone 1-finger 360° orbit + 2-finger pinch zoom + 2-finger pan.
  - **Mode 2 (`🥽 2 · Quest VR`)**: Immersive 1:1 VR with floor-mesh teleportation reticle, thumbstick walk/snap-turn, and wrist/HUD space switcher.
  - **Mode 3 (`📱 3 · 1:1 AR Walk`)**: Full-scale world-anchored AR walkthrough on Android Chrome and Meta Quest Passthrough.
  - **Mode 4 (`🏡 4 · Tabletop AR`)**: Full-site architectural model including neighborhood context auto-scaled to fit the viewport, with 2-finger pinch-to-scale and 1-finger drag rotation.
  - **Subtle Hidden-Line CAD Render (`✏️ Lines` / `[L]`)**: Toggleable `THREE.EdgesGeometry` architectural line overlay with depth-occluded paper shading.
  - **Dual-Engine Graphic Design (`📐 Style` / `[T]`)**: German DIN 1451 E-Ink technical specification UI (default) toggleable with 24th-century Star Trek LCARS telemetry and procedural Web Audio synthesizer feedback.

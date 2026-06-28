# Credits & Asset Sources

This mod uses **no** art, music, text, icons, or logos from *Civilization Revolution* or any Firaxis / 2K title. Game *mechanics* are not copyrightable; this is a clean-room systems recreation.

## Icons

All icons in `Images/` are **original works created for this mod**, generated programmatically as 200×200 px white silhouettes on a transparent background (the format Unciv expects). They are released into the **public domain (CC0)** by the author.

- **Style:** monogram emblems with category-distinct frames (units = shield, buildings = house, wonders = star, techs = hexagon, nations = circle, resources = diamond, improvements = square, policies = pentagon).
- **Tooling:** rendered with Python + Pillow using the **DejaVu Sans Bold** font (DejaVu Fonts license — a permissive, freely redistributable license). The font is used only as a rendering tool; the resulting PNGs are original output, not redistributions of the font.

These placeholder-quality icons are meant to be swapped for themed art if desired. Open/CC sources suitable for replacements include:
- **game-icons.net** — CC BY 3.0 (attribute the individual icon authors here if you use them)
- **The Noun Project** — CC / open icons (attribute per icon)

If you replace any icon, record the source and creator in this file.

## Ruleset data

Terrain, tile-improvement, and tile-resource **definitions** (stat values and map-generation parameters) were adapted from **Unciv's** open-source bundled "Civ V – Vanilla" ruleset:
- Unciv — https://github.com/yairm210/Unciv (by yairm210 and contributors)

Unciv's rulesets are part of its open-source project and are explicitly intended to be moddable. Those files are themselves a clean reimplementation of game systems, not Firaxis assets. All other JSON in this mod (eras, techs, units, buildings, nations, policies, victory types, speeds, difficulties) was authored for this project.

## Game design reference (mechanics only)

Civilization Revolution's systems — civ talents/era bonuses, the technology tree, unit roster and special units, wonders, governments, Great People, and victory conditions — were reconstructed from public community references: CivFanatics Civilopedia (civfanatics.com/civrev), Stra
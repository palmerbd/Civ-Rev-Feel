# Civ Rev Feel — an Unciv Base-Ruleset Mod

A **base ruleset (total conversion)** for [Unciv](https://github.com/yairm210/Unciv) that recreates **Sid Meier's Civilization Revolution** (the 2008 console/iOS game) as closely as Unciv's engine allows — the real civilizations and their bonuses, the actual tech tree, the 21 world wonders, the governments, Great People, and the four victory paths.

> **Fan project. Not affiliated with, endorsed by, or using any assets from Firaxis or 2K.** This mod recreates *game mechanics* (which are not copyrightable). All art is original; no Civ Rev / Firaxis art, music, text, icons, or logos are used. Game data was reconstructed from public community wikis (CivFanatics, StrategyWiki, Civ Fandom), which document mechanics, not assets. See `Credits.md`.

This is **not a visual twin.** Unciv uses a hex grid (Civ Rev used squares) — the grid is engine-level and can't be changed by a mod. The cartoony console UI, advisor characters, and animations are out of scope. What's matched is **content, mechanics, pacing, and civ identity.**

---

## What's inside (modeled on the real game)

| System | Content |
|---|---|
| **Eras** | 4 — Ancient → Medieval → Industrial → Modern |
| **Tech tree** | 47 techs — the actual Civ Rev tree (Alphabet→Writing→Code of Laws→…→Space Flight→Superconductor), each unlocking the right unit/building/wonder |
| **Units** | 55 — full roster (Warrior, Legion, Catapult, Horsemen, Pikemen, Knight, Rifleman, Cannon, Tank, Artillery, Modern Infantry), naval (Galley→Galleon→Cruiser→Submarine→Battleship), air (Fighter, Bomber), spaceship parts, Great People, **and every civ's real special units** (Legion, Hoplite, Samurai Knight, Keshik, Cataphract, Cossack, Conquistador, Impi, Jaguar Warrior, Longbow Archer, Trebuchet, Panzer/Sherman/T34 Tanks, Spitfire/Zero/ME109 Fighters, Lancaster/Heinkel/Val Bombers, etc.) |
| **Buildings** | Granary, Library, Barracks, Temple, Walls, Trading Post, Market, Courthouse, Workshop, Aqueduct, Harbour, University, Bank, Cathedral, Factory, SDI Defense, Palace |
| **Wonders** | The 21 Civ Rev wonders with mapped effects — Colossus of Rhodes, Great Library, Great Pyramid, Great Wall, Hanging Gardens, Oracle of Delphi, Stonehenge, East India Company, Himeji Castle, Leonardo's Workshop, Magna Carta, Oxford University, Shakespeare's Theatre, Trade Fair of Troyes, Hollywood, The Internet, Manhattan Project, Military-Industrial Complex, Apollo Program, **World Bank** (Economic capstone), **United Nations** (Cultural capstone) |
| **Civilizations** | All 16 — America, Arabia, Aztecs, China, Egypt, England, France, Germany, Greece, India, Japan, Mongolia, Rome, Russia, Spain, Zulu — with their real leaders, signature talents/era bonuses (mapped to Unciv uniques, later-era bonuses gated by the appropriate tech), and special units |
| **Governments** | Despotism, Monarchy, Republic, Democracy, Communism, Fundamentalism (as policy branches; Democracy gives +50% Science as in the original) |
| **Great People** | Great Scientist, Merchant, Artist, Engineer — generated from specialist slots, settle or expend for a bonus (build Academy/Customs House/Manufactory/Landmark) |
| **Victories** | Domination (capture all capitals), Scientific (Apollo + spaceship), Economic (build the World Bank), Cultural (build the United Nations) |
| **Game speed** | One compressed "Standard" speed tuned for short (~3-hour) games |

---

## Install

**Option A — in-app (recommended):** Unciv → **Mods** → **Download mod from URL** → paste `https://github.com/palmerbd/Civ-Rev-Feel` → enable **Civ-Rev-Feel** as the Base Ruleset when starting a new game.

**Option B — manual (desktop):** Unzip / drop the `Civ-Rev-Feel` folder into your Unciv `/mods` directory (next to the desktop `.jar`), launch Unciv, and pick **Civ-Rev-Feel** as the Base Ruleset.

**First launch:** Unciv builds the texture atlas from `Images/` on first desktop load. If icons look missing, restart Unciv once.

**Validate on your version:** Options → **Locate mod errors** runs Unciv's built-in Ruleset Validator (also runs when starting a new game). This is the authoritative check for your installed Unciv build.

## Playing on iPhone

Run it on **Windows desktop Unciv** and stream the PC — **Steam Link** (add Unciv as a Non-Steam Game) or **Moonlight + Sunshine**. Turn-based pacing makes latency a non-issue. No iOS build needed.

---

## Fidelity — what matches, and the known divergences

**Faithfully reproduced:** the 16 civs with their real leaders and bonuses, the actual tech tree and what each tech unlocks, the unit roster and each civ's named special units, the 21 wonders, the six governments (incl. Democracy's +50% science), Great People, fast pacing, and the four victory categories.

**Where Unciv's engine forces a divergence** (none block loading or a full playthrough):

1. **Hex grid, not square** — engine-level.
2. **No Armies.** Civ Rev's signature 3-units-into-an-Army stacking has no Unciv equivalent; units fight individually.
3. **Economic victory = build the World Bank.** Unciv has no "accumulate 20,000 gold" victory milestone, so the World Bank world wonder is the trigger (gated behind a Bank + late tech).
4. **Cultural victory = build the United Nations.** Unciv has no "collect 20 culture events" counter, so the UN world wonder is the trigger.
5. **Workers & tile improvements are present** (Unciv's economy is improvement-based). Civ Rev auto-works tiles with no workers — kept Unciv's model for playability.
6. **Per-era civ bonuses are approximated.** Each civ's Special Talent + its most defining era bonuses are mapped to Unciv uniques, with later-era bonuses gated by the relevant tech. Bonuses with no Unciv equivalent (e.g. "2% interest on gold reserves", "rush at ½ cost", "cities immune to Anarchy", "barbarian villages join you", "Overrun") are dropped or substituted with the nearest effect.
7. **Special units share their base unit's stats** (as in Civ Rev — they're historically-flavored replacements); civ era bonuses that buff
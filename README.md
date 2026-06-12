# Epoch Arena — Playtest Builds

**Battle of the Ages.** A lane-push civilization strategy game: build an economy, climb the tech tree through four historical eras, and march ever-stronger armies down three lanes until the enemy team's capitals fall.

Inspired by *Civilization Wars*, the classic Warcraft III custom map. Built from scratch in Unity 6 by a solo developer.

> **This repo hosts playable Windows builds only** — grab the newest zip from [**Releases**](../../releases/latest). The game's source is developed in a private repository; every release here ships with detailed change notes.

---

## How it plays

- **Build → spawn → push.** You don't control units directly. Place spawn buildings and every 30 seconds they send another wave marching down your lane. Win the fight at the front line and your survivors push on toward the enemy capital.
- **Three lanes, three players per team.** Top is a naval lane (docks, galleys, raiders), Mid and Bot are land fronts. In 3v3, each player owns one lane — but your economy is tied to your whole team's map control.
- **Four eras.** Ancient → Medieval → Industrial → Modern. Each era unlocks new spawn buildings, units, towers, and economy options. Era advancement is gated by research — 40+ technologies with real prerequisite chains.
- **Economy is the real war.** Control points along each lane feed the markets keyed to that lane (Trade→Top, Food→Mid, Materials→Bot) — for *every* player on the team. Holding your lane's circles keeps your teammates' markets profitable. Banks compound. The player who out-economizes usually out-armies.
- **Wonders.** 40 unique wonders across the eras — income engines, global auras, unit spawners. Race-to-finish: if two players start the same wonder, only the first to complete it gets it (the loser is refunded).
- **Win condition:** destroy the enemy team's **capital buildings**. A team is eliminated when every capital on it has fallen.

## Download & run

1. Download the latest `EpochArena_vX.Y.Z.zip` from [Releases](../../releases/latest)
2. Extract anywhere
3. Run `Epoch Arena.exe`

**Requirements:** Windows 10/11, 64-bit, a DirectX 12 capable GPU.

- **Single-player vs AI** works fully offline — Steam is not required.
- **Multiplayer (up to 3v3)** uses Steam's relay network for connections: have Steam running, host a lobby in-game, and invite friends via the Steam overlay. Builds currently run on Steam's public test app id, so no purchase or key is needed.

## Status

**Early prototype, in active development.** Expect rough edges, placeholder visuals on some units, and balance that swings between releases. The AI opponents are under heavy iteration — recent releases have focused on making them tech, expand, and fight like humans do. Every release's notes document exactly what changed and why.

Bug reports and feedback are very welcome — drop them in the Civilization Wars community Discord, or open an issue here.

## Credits

A solo project by Frank Bosco / **Bergen Palisades Technology LLC**. All code is original. 3D models, icons, and UI art are licensed from Unity Asset Store packs by their respective artists — the full attribution list is on the in-game credits screen.

*Epoch Arena is a fan-inspired original game and is not affiliated with Blizzard Entertainment or the original Civilization Wars map authors.*

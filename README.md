# Neon Debris

**Neon Debris** is a cyberpunk auto-battler roguelike where you build a squad of unstable operatives, outfit them with upgrades and implants, position them on a station deck, and try to survive escalating fights across a dying orbital world.

A solo project built by **Marcy Kuhn** at **42 Pixel Studios**.

![Main Menu](screenshots/main_menu.png)

![Combat](screenshots/combat.png)

## Download

**[Latest Release](https://github.com/MarcelineVPQ/neon-debris/releases/latest)** — Windows · Linux · macOS

## Community

**[Join the Neon Debris Discord](https://discord.gg/fqkbyEsTkB)** — patch notes, daily leaderboard digests, top-10 break-in alerts, win-streak callouts, bug reports, feature requests, lore archives, and a direct line to the dev team.

---

## Early Alpha — Live, Evolving, Honest About It

Neon Debris is in **active early development**. This page works like an early-access storefront:

- the core combat loop is playable end-to-end
- ranked PvP, single-player roguelike, and daily run modes are all live
- balance, polish, and presentation are still moving fast
- patch notes, leaderboards, and feature requests are all wired into the Discord

Expect frequent updates, tuning passes, UI refinements, and new systems landing as the project grows. The build's main menu carries a "demo update available" banner so you'll always know when a fresh release is out.

> ### A Note on the Art
>
> **All current art in Neon Debris is AI-generated and is a placeholder.** Portraits, icons, splash images, tilesets, and environment art will all be replaced. A dedicated human artist will be hired to redo the entire visual identity ahead of the full release. Treat the current look as a working stand-in — the gameplay, audio, and systems are the parts I'm asking you to evaluate today.

---

## The Pitch

Recruit a crew of cyberpunk operatives, survive auto-battles on a drifting station, and push your build farther each run through upgrades, synergies, commander bonuses, choice-card pickups, and persistent meta-progression.

If you like games such as **Teamfight Tactics**, **Super Auto Pets**, backpack/buildcraft roguelikes, or squad-based strategy with strong progression loops — that's the lane Neon Debris is aiming for, with a distinct cyberpunk identity.

---

## What You Do In The Game

1. **Pick a Commander** — six backgrounds (Street Fixer, Corp Defector, Trauma Surgeon, Black Hat, Corpo Merc, Netdasher), each with a unique perk and 10-level mastery track.
2. **Hire operatives** from the shop and position them on the station deck.
3. **Buy upgrades, reroll, lock, sell, merge duplicates** — and watch your class identity sharpen as primary stats hit a +50% boost rate.
4. **Fight auto-battles** where movement, range, energy regen, abilities, attack-redirect bullet time, and targeting all matter.
5. **Choose your path** — branching roguelike map across 3 acts, or a fixed 20-round ranked PvP gauntlet with composite scoring.
6. **Earn permanent progression** through Datakeys, firmware, dossiers, augments, threat protocols, and commander mastery.

---

## Game Modes

### Single Player — Roguelike Run

A 3-act branching map: **Lower Decks → Mid Ring → Command Deck**. Combat, elites, bosses, black markets, treasure caches, NPC contacts (Kira / Sable / Null / Ratchet), and unknown event nodes.

### Ranked PvP — 20-Round Gauntlet

A fixed-length solo ladder against real player squads / ghost boards via a Nakama backend.

- **20 rounds, ~1 hour per run** — fixed-length, so every decision actually matters
- **Composite score** — final ranking blends rounds-survived, win-streak, lives, credits, and threat-protocol multipliers
- **Choice cards** — at rounds 3 / 6 / 9 / 12 / 15 / 18 you pick 1 of 3 cards (implant / squad-wide upgrade / credits skip), Vampire Survivors style
- **Win-streak gold** — consecutive wins stack income (+1c at 3, +2c at 5, +3c at 7+)
- **Streak achievements** — Hot Hand (5), On Fire (8), Untouchable (12)
- **Rotating bi-weekly pool** — 25% of implants and upgrades are locked per rotation, shared across all players, so leaderboards stay comparable. The Cortex menu shows active vs. locked items with a live countdown to the next rotation.
- **Live opponent banner** — see their squad, lives, credits, and changes round-over-round
- **Dossier unlocks** by climbing the ladder

### Daily Run

Same seed for everyone, no firmware bonuses, separate leaderboard. Bring your skill, not your meta.

> **Heads-up:** Daily Run currently uses the single-player map structure and is **noticeably easier** than Ranked PvP — the difficulty curve hasn't been balanced for fixed-seed daily play yet. Expect a tuning pass; for now, treat it as a low-stakes warm-up rather than a serious challenge.

---

## Combat

- **Hybrid** real-time movement with tick-based attacks and ability timing
- **Positioning matters** — range, frontline pressure, support placement, threat access
- **Attack redirect** — Matrix-style bullet time, 2 per battle (+1 with implant), full slowdown/snapback cinematic
- **Hitstop, knockback, crit flash, blood splatter, shields, poison, psi effects** — full juice pipeline on every hit
- **9 combat shaders** for status effects and feedback
- **Speed controls** — fast-forward through combat when you want to

---

## 10 Operative Classes

Each operative spawns with a **random callsign** and one of three **ability variants**, so two of the same class can play very differently.

Tier 1: **Street Samurai** · **Medtech**
Tier 2: **Riot Frame** · **Ghost** · **Psion**
Tier 3: **Chemist** · **Enforcer** · **Railgun Sniper**
Tier 4: **Drone Rigger** · **Combat Drone**

### Class Specialization

Every class has a **primary stat (+50% boost)** and **secondary stat (+25%)** when you upgrade them. A Riot Frame stacking armor becomes an absolute wall; a Ghost stacking crit becomes a surgical assassin. Specialization stats are highlighted in class colors with `[+50%]` / `[+25%]` tags throughout the UI.

Stat purchases also grant fractional XP — primary stats give more XP per buy than secondary, opening a slow-burn alternative to merging duplicates.

---

## Run-Building Systems

- **Duplicate merging** with XP-based leveling
- **Stat upgrades** with escalating costs and class-aware previews
- **Synergies** — 5 dual-class synergies (Wetwork, Overwatch, Field Medicine, Neural Warfare, Siege Line) plus 3 hidden conditional synergies that show as `???` until discovered
- **Implants** — base + 16 unlockable augments via the Cortex
- **Commander perks** — 6 backgrounds, each shapes opening turns and shop bias
- **Economy choices** — reroll, lock, save for interest, time your power spikes

---

## Meta-Progression — The Cortex

Permanent power and unlocks built across runs:

- **Datakeys** — earned every run (base + floors + win + elites + bosses, multiplied by active threat protocols)
- **Firmware** — 12 permanent upgrade tracks
- **Dossiers** — unlock additional operative classes
- **Augments** — 16 new implants added to the run pool
- **Threat Protocols** — 9 difficulty modifiers, each with a Datakey% multiplier
- **Commander Mastery** — 10 levels per commander, with specializations (Aggression / Fortification / Adaptation / Scavenger / etc.)
- **Achievements** — 36 total across bronze / silver / gold / platinum tiers
- **Player Titles** — 20 with unique unlock conditions

---

## Replays + Mirror-Match PvP

Every meaningful ranked run is recorded as a snapshot + action log, gzipped 50× for upload. The "Replays" button on the main menu opens your match history with round-by-round detail. Ranked PvP plays your locked opponent's prep decisions back round-for-round, so you fight an evolving squad — not a frozen one.

---

## Audio

- **119+ sound effects**, 12-player pool, mastered
- **80 combat grunts** across 10 classes
- **1,164 hero voice lines** generated with ElevenLabs v3 and emotion tags
- **230+ enemy taunts** with class-specific delivery
- **100 announcer round callouts** + 14 event lines
- **5-track battle music pool**, random per battle
- **42PS logo sting** with mascot Jinx voice

---

## Current Features

✓ Playable combat loop with full juice pipeline
✓ Roguelike map across 3 acts with NPC contacts and event nodes
✓ 20-round Ranked PvP with composite scoring and live opponent banner
✓ Choice cards + win-streak gold + rotating bi-weekly pool
✓ Daily run mode
✓ Multi-profile saves
✓ 6-commander system with mastery and specializations
✓ Op Dock — full roster bar with stat bars, fatigue, drag-drop bench
✓ The Cortex meta-progression hub
✓ Replay system with mirror-match PvP playback
✓ Discord-integrated leaderboards and patch notes
✓ Tutorial walkthrough (31 steps with narration and action-gating)

## Still Evolving

- balance and matchmaking pacing
- progression curves for new players
- tournament mode (planned, north-star feature)
- equipment/items system
- intel reports between PvP rounds
- expanded animations (victory, fatigue, revive, crit, throw)
- campaign story (3-act narrative)

---

## Why Play Now

If you like getting into games early and watching them sharpen over time, Neon Debris already has:

- a strong theme and identity
- a complete, playable core loop
- meaningful build decisions every round
- persistent progression that rewards time
- an active Discord and a developer who reads every bug report

Good fit if you enjoy:

- discovering systems before they're fully solved
- giving feedback that actually shows up in the next patch
- watching a strategy game take shape in public

---

## Platforms

- Windows (64-bit)
- Linux (x86_64)
- macOS (unsigned alpha — see release notes for Gatekeeper instructions)

---

## Status

**Early alpha. Actively in development.**

Neon Debris is not "finished" and is not pretending to be. The goal is to keep pushing toward a distinctive, replayable cyberpunk strategy game with a strong progression loop, a clear identity, and a real community around it.

---

## Follow Development

- **GitHub Releases** — patch notes and downloads: https://github.com/MarcelineVPQ/neon-debris/releases/latest
- **Discord** — daily standings, alerts, lore, and direct dev contact: https://discord.gg/fqkbyEsTkB
- **In-game Report Issue** — every report goes straight to the team

---

*Neon Debris — a 42 Pixel Studios joint, developed by Marcy Kuhn.*

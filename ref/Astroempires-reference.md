# AstroEmpires: Reference Notes

> *“Know the rules not to obey them—but to use them.”*  
> — Strategos Umbratheon, Reference Core INIT

---

## 🎮 Game Overview
**AstroEmpires** is a persistent, massively multiplayer space strategy game.
- Turn-based with real-time unit movement
- Focus on base building, fleet control, and alliance warfare
- Universes are large grid-based sectors (e.g. C11:23:59:30)

### Key Mechanics:
- **Bases** built on planets, moons, asteroids, and more
- **Fleets** move with real travel time (hours or days)
- **Economy** generated via structures like Economic Centers
- **Combat** is deterministic—fleet with best stats wins

---

## 🧱 Base Types
- **Planet (Earth-like, Cratered):** Large area, good for production
- **Moon (Crystalline):** Limited space, ideal for labs/intel
- **Asteroid:** Lower area, fast to build, defense/scramble nodes

---

## ⚙️ Core Structures

| Structure             | Purpose                              |
|----------------------|---------------------------------------|
| Urban Structures      | Population & structure cap            |
| Solar/Gas/Fusion/AM  | Energy production                     |
| Metal/Crystal/Gas     | Resource mining                       |
| Robotic/Nanite/Android| Build acceleration                   |
| Research Labs         | Technology unlock + speed             |
| Shipyards/Orbital     | Fleet construction                    |
| Spaceports            | Logistics/transport                   |
| Economic Centers       | Credit income                        |
| Terraforming          | Area expansion                       |
| Jumpgate              | Instant travel between JGs           |
| Command Center         | Base control, detection               |
| Defenses (Turrets)    | Planetary protection                 |

---

## 📊 Game Stats

## 📐 Game Formulas

### 🚀 Travel Time
- **Formula:** `Travel Time = Distance / Speed`
- Measured in hours; faster ships arrive sooner but may be weaker
- Travel between sectors can take 1–48 hours depending on ship and distance

### ⚡ Energy Efficiency
- Buildings consume energy; production must always stay positive
- **Common ratios:**
  - 2 Solar → 1 Metal Refinery
  - 5 Solar → 1 Nanite
- **Tip:** Upgrade Fusion or AM Plants when Solar becomes area-inefficient

### 💰 Economy Formula
- Each Economic Center gives base credits per tick (scales with tech bonuses)
- **Approximate base:** `Econ = (Econ Center Level) × (Population Modifiers)`
- Don’t build until core production and energy are stable

### 🧪 Lab Effectiveness
- Research speed increases with **Computer Tech** and **Lab Level**
- Ideal moon lab base: 10–20 Labs with Computer Tech ≥ 8

- **Fleet Strength:** Point-based measure of military power
- **Economy:** Passive credit generation per tick
- **Technology:** Enables stronger fleets and faster growth

---

## 🪐 Factions

While gameplay is not locked to distinct factions, players often form long-term **alliances** or **guilds** that serve as de facto factions. These include:

- **WAR (Wonton Allocation Rejects):** Tactical defense, decentralized leadership
- **Empire Hives:** Often large, power-focused, expand aggressively
- **Ghost Nets:** Small guilds that specialize in stealth/espionage
- **Nomad Cells:** Roaming players or fleets with high cloak and mobility

Faction behavior is defined by fleet tactics, jumpgate coverage, and diplomacy styles.

---

## 🚢 Units Overview

| Unit             | Role                            | Notes                                   |
|------------------|----------------------------------|-----------------------------------------|
| **Fighter**      | Interceptor / defense            | Cheap and fast, vulnerable in bulk      |
| **Bomber**       | Anti-structure                   | Targets base defenses, low survivability|
| **Corvette**     | Recon / light attack             | High speed, used for scouting           |
| **Frigate**      | Light multi-role combat          | Good vs Fighters, decent survivability  |
| **Destroyer**    | Anti-medium ship                 | Reliable backbone unit                  |
| **Cruiser**      | Heavy firepower                  | Strong in large numbers                 |
| **Heavy Cruiser**| Capital ship killer              | Costly but effective                    |
| **Battleship**   | Late-game capital                | Excellent for base sieges               |
| **Carrier**      | Deploys Fighters/Bombers         | Useful for mixed fleet dynamics         |
| **Fleet Carrier**| Enhanced carrier + logistics     | Flagship utility                        |
| **Dreadnought**  | Supercapital ship                | Rare, powerful, slow                    |
| **Recycler**     | Salvage unit                     | Collects debris from battles            |
| **Scout**        | Auto-explore                     | Auto-pings moons and small bases        |
| **Outpost Ship** | Base construction                | Required to claim new astros            |

---

## 🔗 External Reference

> **Source Version:** Tracking [`UmbralEmpires`](https://github.com/jamesphenry/UmbralEmpires) as live upstream  
> **Last Reviewed:** 01 May 2025  
> **Next Review Due:** 01 June 2025

> **Source Version:** Tracking [`UmbralEmpires`](https://github.com/jamesphenry/UmbralEmpires) as live upstream  
> **Last Reviewed:** 01 May 2025

For purposes of this project (`Umbratheon`), all mechanical assumptions and gameplay emulation align with the upstream design tracked in:

- [UmbralEmpires (GitHub)](https://github.com/jamesphenry/UmbralEmpires)

This repo serves as the **live upstream** for rules, systems, and simulated mechanics. Reference data here remains accurate to current AE behavior but will adapt in parallel with UmbralEmpires progression.

Additional systems analysis and gameplay mechanics can be found in the related clone project repository:

- [UmbralEmpires (GitHub)](https://github.com/jamesphenry/UmbralEmpires) — A clone-in-development of AstroEmpires, containing structured code, game logic breakdowns, and mechanic reference docs.

For purposes of this project (`Umbratheon`), all mechanical assumptions and gameplay emulation align with the upstream design tracked in:

- [UmbralEmpires (GitHub)](https://github.com/jamesphenry/UmbralEmpires)

This repo serves as the **live upstream** for rules, systems, and simulated mechanics. Reference data here remains accurate to current AE behavior but will adapt in parallel with UmbralEmpires progression.

Additional systems analysis and gameplay mechanics can be found in the related clone project repository:

- [UmbralEmpires (GitHub)](https://github.com/jamesphenry/UmbralEmpires) — A clone-in-development of AstroEmpires, containing structured code, game logic breakdowns, and mechanic reference docs.

---

## 🧠 Strategic Themes
- Scouting and visibility are vital—auto-scout moons
- Hide fleets to mask strength; decloak when decisive
- Jumpgates enable instant surprise attacks—monitor JG clusters

> *“The game never ends. The players merely forget to keep playing.”*


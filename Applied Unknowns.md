# Applied Unknowns

**Your Actions Become Infrastructure.**

Applied Unknowns is an open-source, action-adventure scientific sandbox where gameplay is not just entertainment—it is structured contribution to a living, deterministic simulation. Every meaningful player action is captured, validated, and, if proven useful, permanently integrated into the evolving world.

This is not a traditional game loop.  
This is a **measured reality system disguised as a game**.

---

## Core Concept

Players do not simply progress through content. They:

- Discover systems
- Build infrastructure
- Solve environmental and logistical constraints
- Stress-test simulated realities
- Generate reusable world logic

If it works, it stays.  
If it helps others, it becomes infrastructure.

---

## 🧠 Core Features (Full Modular System)

### 1. Core Simulation Engine
- Deterministic, tick-based world simulation
- Server-authoritative world state
- ECS-based architecture (Entity–Component–System)
- Fully replayable world history from event logs
- Modular physics and rule system (swappable world laws)
- Biome-based world segmentation

---

### 2. Event & Action System
- Structured event schema for all player actions
- Real-time event streaming pipeline
- Signed action logs per player
- Categorized actions (exploration, construction, experimentation, optimization, discovery)
- Input normalization layer to prevent client-side manipulation

---

### 3. Contribution & Credit System
- Contribution scoring engine based on usefulness, adoption, and longevity
- Credit proposal system (pending → validated → permanent)
- Domain-based reputation system (ecology, engineering, logistics, systems, etc.)
- Anti-grind weighting and diminishing returns on repetition
- Time-decay model for relevance of contributions

---

### 4. AI Integrity & Validation System
- Real-time anomaly detection for exploit behavior
- Deterministic replay sandbox for validation
- Quarantine system for suspicious credits or items
- Explainable AI decision output (reason codes required)
- Time-delayed settlement (provisional → confirmed → permanent)

---

### 5. Infrastructure Dependency Graph
- Full dependency tracking across systems, items, and actions
- Multi-hop causal graph generation (A → B → C relationships)
- Real-time world dependency visualization
- Critical node detection (systems everything depends on)
- Collapse simulation engine (what breaks if removed)
- Contribution lineage tracing (full forensic value chain)
- Infrastructure heatmaps of world usage
- Structural persistence scoring
- Hidden fragility detection system
- AI-native world topology input layer

---

### 6. Item & Asset System
- Immutable, version-locked item definitions
- Full provenance tracking for all assets
- Sidegrade-only progression (no power creep ladders)
- Environmental balancing instead of item nerfs
- Legacy item preservation system
- Fork-based evolution of item versions

---

### 7. World Evolution System
- System-level balancing (world evolves, items do not change)
- Adaptive ecosystem simulation
- Emergent environmental response systems
- Persistent player-driven world modifications
- Biome evolution and long-term simulation drift

---

### 8. Marketplace & Exchange Layer (Optional Module)
- Contribution-backed valuation system
- Item trading with provenance validation
- Frozen-state handling for flagged items
- Non-speculative pricing controls
- Full transaction audit ledger

---

### 9. Data & Analytics Layer
- Columnar event data warehouse
- Real-time world health dashboards
- Contribution heatmaps and system usage maps
- Economic flow tracking across dependency graph
- Simulation efficiency and stability metrics

---

### 10. Governance & Transparency Layer
- Public audit logs for all economic activity
- Full contribution trace explorer
- Community dispute and challenge system
- Versioned rule-change system (no silent updates)
- Transparent validation reasoning logs

---

### 11. Deployment & Open Source Infrastructure (AGPL-3.0+)
- Fully self-hostable server architecture
- Docker/Kubernetes deployment support
- Modular microservice separation
- Forkable world instances
- Mandatory source availability for all network deployments
- Attribution-preserving design (AGPL compliant)

---

## 🧩 Design Philosophy

Applied Unknowns is built on one principle:

> If it changes the world, it must be observable, traceable, and explainable.

Every system exists to enforce one of three guarantees:
- **Trust** (immutability and transparency)
- **Integrity** (anti-exploit validation)
- **Evolution** (world adaptation through contribution)

---

## 📦 Getting Started (High-Level)

This project is currently in architectural and early development phase.

Planned initial build includes:
- Single biome simulation environment
- Event logging pipeline
- Basic contribution scoring system
- Manual validation dashboard

---

## Specification Branding License (SBL)

### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/applied-unknowns/](https://roxanneardary.com/applied-unknowns/)

---

## ⚖️ License & Notice Requirements

Applied Unknowns is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- Applied Unknowns specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.  
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.  

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.

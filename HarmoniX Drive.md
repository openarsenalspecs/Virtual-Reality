# HarmoniX Drive

**Code the sound. Drive the world.**

HarmoniX Drive is an open-source VR music performance and racing platform where musical precision directly controls motion, speed, and gameplay outcomes. Players do not simply play music—they *drive it*.

Every note becomes movement. Every mistake becomes resistance. Every streak becomes acceleration.

Built under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**, HarmoniX Drive is designed as a modular, community-driven ecosystem of instrument-based gameplay systems.

---

## 🧠 Core Concept

HarmoniX Drive merges:
- Musical instrument mastery
- VR physical interaction
- High-speed racing mechanics
- Real-time performance evaluation

Players perform music using VR inputs or advanced glove sensors. Their accuracy, timing, and expression directly affect vehicle speed, control, and racing outcomes.

---

## 🧱 Full Feature List

### 🎮 Core Gameplay Systems
- Real-time music-to-movement engine
- Accuracy-based speed control system
- Streak multiplier acceleration system
- Timing windows (perfect / good / miss)
- Dynamic difficulty scaling based on performance

---

### 🎼 Instrument System (Modular Architecture)
Each instrument is a self-contained gameplay module.

Supported / Planned Modules:
- Piano (baseline precision + polyphony)
- Drums (rhythm + timing bursts)
- Guitar (fretting + strumming coordination)
- Violin (continuous pitch control)
- Wind instruments (future breath/gesture systems)

Each module defines:
- Input mapping rules
- Scoring logic
- Expressive parameters
- Visual hand models
- Tutorial systems

---

### 🏎️ Racing Systems
- VR-based immersive racing environments
- Multiple vehicle types:
  - Cars
  - Skateboards
  - Bikes
  - Roller blades
- Performance-linked physics:
  - Accuracy increases speed
  - Mistakes reduce control
  - Streaks provide acceleration boosts
- Procedural and designed track support

---

### 🥽 VR & Input Systems
- Full VR headset support
- High-precision glove input integration
- Finger-level tracking (per joint precision target)
- Pressure and velocity detection
- Gesture-based control system
- Calibration system per user

---

### 🎵 Music Engine
- Real-time note detection system
- Polyphonic input support
- MIDI compatibility layer
- Tempo synchronization engine
- Expressive performance modeling (velocity, sustain, articulation)

---

### 🧭 UI / UX Systems
- Lower-right instruction panel:
  - Note visualization
  - Hand position guides
  - Upcoming note previews
- Real-time performance feedback
- Color-coded accuracy system
- Ghost hand overlay assistance

---

### 🔁 Replay & Learning Tools
- Instant replay system
- Slow-motion performance breakdown
- Error highlighting (timing / placement / pressure)
- Correct-action overlay system
- Training suggestion system

---

### 🤖 AI Systems
- Adaptive racing AI opponents
- Skill-based difficulty scaling
- Human-like error simulation
- AI coaching feedback system
- Performance pattern detection

---

### 🌐 Multiplayer Systems
- Real-time VR multiplayer racing
- Synchronized musical tracks
- Global leaderboards
- Ghost racing system
- Spectator mode

---

### 🧪 Learning & Training
- Instrument-specific training modules
- Progressive difficulty systems
- Rhythm drills and practice modes
- Skill progression trees
- Cognitive mapping between motion and music theory

---

### 🎨 Visual Systems
- Music-reactive environments
- Speed trail visual effects
- Performance-based environmental changes
- Dynamic lighting and atmosphere shifts

---

### ⚙️ Engine Systems
- Low-latency input processing (<20ms target)
- Deterministic multiplayer synchronization
- Modular plugin architecture
- Cross-platform VR compatibility
- Scalable performance optimization system

---

### 🌍 Open Source Ecosystem
- AGPL 3.0+ licensing
- Community instrument module contributions
- Plugin-based extension system
- Transparent scoring algorithms
- Open AI behavior rulesets

---

## 📦 Project Structure
```text
/engine-core
/vr-input-layer
/music-engine
/racing-system
/instrument-modules
/piano
/drums
/guitar
/violin
/ai-system
/ui-system
/assets-open
/docs
```

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
  - [https://roxanneardary.com/harmonixdrive/](https://roxanneardary.com/harmonixdrive/)

---

## 🧩 License & Notice Requirements

HarmoniX Drive is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to this project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.  
- HarmoniX specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments. Any update that adds new contributors or modifies attribution should also update `notice.md`.
- When submitting a pull request, ensure that any new files maintain attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, refer to the AGPL-3.0+ license and the `notice.md` file.

---

## 🔮 Vision

HarmoniX Drive is not just a game.

It is a system where:
> musical precision becomes physical motion  
> and motion becomes skill, expression, and competition

---

## 🤝 Contributing

Community contributions are welcome under AGPL-3.0+ terms.  
All contributions must be modular, documented, and compatible with the instrument plugin architecture.

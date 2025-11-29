Here is a **GitHub-ready README description** for **Day 8 – Voice Game Master (D&D Style Adventure)** written in the same beautiful style as your Food Agent README.
Completely formatted, includes badges, sections, project overview, features, screenshots, demo, etc.

---

# 🗡️ Voice Game Master – D&D Style Interactive Adventure (Day 8)

<div align="center">

![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![Python](https://img.shields.io/badge/Python-3.11-yellow?logo=python)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript)
![JSON](https://img.shields.io/badge/WorldState-JSON-orange?logo=json)
![Docker](https://img.shields.io/badge/Docker-Ready-0db7ed?logo=docker)
![License](https://img.shields.io/badge/License-MIT-green)

**A fully voice-controlled D&D-style Game Master that runs an interactive story, maintains world continuity, and responds dynamically to player actions — powered by Murf Falcon.
Built for the #MurfAIVoiceAgentsChallenge.**

[Features](#-features) • [Gameplay](#-gameplay-overview) • [Architecture](#-architecture) • [Setup](#-quick-start) • [Demo](#-demo-video) • [Author](#-author)

</div>

---

<img width="1536" height="1024" alt="ChatGPT Image Nov 29, 2025, 05_47_45 PM" src="https://github.com/user-attachments/assets/6bae0418-1642-435e-a647-62297d3b0da9" />


---

## 🧙 Overview

This project is a **voice-controlled Game Master (GM)** inspired by classic Dungeons & Dragons storytelling.
You speak → the GM responds → the story evolves.

The Game Master:

✔ Describes cinematic scenes
✔ Tracks your decisions
✔ Remembers locations, NPCs, and items
✔ Reacts dynamically to your choices
✔ Guides you through quests, danger, battles & discoveries
✔ All fully through **voice**, using Murf Falcon TTS/STT

This creates a **hands-free, immersive voice adventure** — perfect for storytelling or role-playing experiences.

---


https://github.com/user-attachments/assets/433ae915-dbdf-4a35-9199-2c527a365dff


##  Primary Goal (MVP)

### **Voice-Driven Interactive Story With Scene Continuity**

Your Voice GM can:

###  **1. Set the Universe & Tone**

* Fantasy, sci-fi, cyberpunk (configurable)
* Dramatic, humorous, dark — customizable
* Runs in a consistent persona as the GM

### 🎙️ **2. Run an Adventure Through Voice**

GM:

* Describes the world
* Introduces NPCs
* Provides choices & challenges
* Ends each message with: **“What do you do?”**

Player responds purely by voice.

### 🔄 **3. Maintain Continuity**

The agent remembers:

* Player decisions
* Character introductions
* Discovered locations
* Ongoing quests

All through chat history + optional JSON world state.

---

## 🚀 Advanced Features (Implemented)

### 🗺️ **JSON World State**

Tracks:

```json
{
  "player": {
    "name": "Hero",
    "health": 20,
    "inventory": ["Torch", "Dagger"]
  },
  "location": "Ancient Cave Entrance",
  "quests": ["Find the Lost Rune"],
  "npcs": [
    { "name": "Eldar the Guide", "alive": true }
  ]
}
```

### ⚔️ **Dice-Based Mechanics**

* d20 rolls for risky actions
* Modifiers based on stats
* Outcomes:

  * Fail
  * Partial Success
  * Full Success

### 🎒 **Inventory & Character Sheet**

Player can ask:

* “What items do I have?”
* “How much health is left?”

GM updates JSON automatically.

### 🌌 **Multiple Universes**

Selectable at start:

* Fantasy
* Cyberpunk
* Space Adventure
* Post-Apocalyptic

Each with its own system prompt + starting world state.

---

## ⭐ Features

### ✔ Fully Voice Operated (Hands-Free Gameplay)

### ✔ Dynamic Narrative Generation

### ✔ Branching Story Decisions

### ✔ JSON-Based World Model

### ✔ Lightweight Engine (No DB Required)

### ✔ Beginner-Friendly Story Flow

---

## 🎮 Gameplay Overview

Example interactions:

> 🧙 GM: *You stand at the entrance of a ruined temple. Cold wind brushes past your ears. What do you do?*

> 🎤 Player: *I walk inside quietly.*

> 🧙 GM: *Rolls a stealth check... You succeed. Inside, you see glowing runes on the wall…*

Story continues until:

* Quest completion
* Victory / escape
* Or player decides to restart

---

## 🛠️ Tech Stack

* **Python** – GM logic
* **JSON** – World state
* **Murf Falcon TTS/STT**
* **FastAPI (optional)** – For running agent services
* **Web UI** – Voice interface
* **Docker (optional)**

---

## 📁 Project Structure

```
/Voice-GameMaster-Agent
│
├── data/
│   ├── world_state.json
│   ├── templates/
│   │   ├── fantasy_base.json
│   │   ├── cyberpunk_base.json
│   │   └── space_base.json
│
├── src/
│   ├── gm_agent.py
│   ├── story_engine.py
│   ├── dice_engine.py
│   ├── world_state.py
│   ├── prompts/
│   │   ├── gm_system_fantasy.txt
│   │   ├── gm_system_scifi.txt
│   │   └── gm_system_cyberpunk.txt
│
├── ui/
│   ├── index.html
│   └── script.js
│
├── logs/
└── README.md
```

---

## ⚙️ Quick Start

### **1. Clone the Repo**

```bash
git clone https://github.com/yourusername/Voice-GameMaster-Agent
cd Voice-GameMaster-Agent
```

### **2. Install Requirements**

```bash
pip install -r requirements.txt
```

### **3. Run the Voice Game Master**

```bash
python src/gm_agent.py
```

---

## 🎲 Example Dice Roll Output

```
🎲 Rolling d20...
➡ Result: 17 (Success!)
```

---

## 🎥 Demo Video

📎 Add your Day 8 demo here
https://drive.google.com/file/d/1mrkxPA3I8gYiSaHsIbBOdYp0aiYfWaI9/view?usp=drive_link
---

## 📌 Future Improvements

* Battle system with HP damage simulations
* Save & resume game sessions
* Multiplayer party mode
* Map-based navigation
* Memory-optimized story arcs

---

## 👨‍💻 Author

**Om Gedam**
GitHub: **@itsomg134**
Email: **[omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)**
X (Twitter): **@omgedam**
LinkedIn: **Om Gedam**
Portfolio: **[https://ogworks.lovable.app](https://ogworks.lovable.app)**

Built with ⚡ Murf Falcon + ❤️ For AI creativity.


Just tell me!

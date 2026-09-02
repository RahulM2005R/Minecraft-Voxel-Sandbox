# VoxelCraft

> **A browser-based 3D voxel sandbox game built with Google AI Studio.**

VoxelCraft is a lightweight, interactive voxel-based sandbox that brings the classic block-building experience directly to the browser. Explore a procedurally generated world, interact with the environment, place and destroy blocks, and build whatever your imagination comes up with.

The project was developed using **Google AI Studio**, demonstrating how modern generative AI can be used to rapidly prototype and develop interactive 3D applications.

🎮 **Play the Game:** [VoxelCraft](https://voxelcraft.ai.studio)

---

## ✨ Features

* 🌍 **3D Voxel World** — Explore an interactive block-based environment.
* ⛏️ **Block Interaction** — Break and manipulate blocks within the world.
* 🧱 **Building System** — Place blocks and construct your own structures.
* 🎮 **First-Person Gameplay** — Navigate the world from a first-person perspective.
* 🌄 **Procedural Environment** — Dynamically generated voxel terrain.
* 🖥️ **Browser-Based** — Play directly in your browser without installing a traditional game client.
* ⚡ **Lightweight & Accessible** — Designed to run as a web application.
* 🤖 **AI-Assisted Development** — Created and iterated using Google AI Studio.

---

## 🎮 Gameplay

VoxelCraft follows the simple philosophy of classic voxel sandbox games:

**Explore → Mine → Build → Experiment**

Players enter a block-based 3D environment where the world itself becomes the playground. Gather resources, modify the terrain, and construct whatever you can imagine.

There is no fixed path to follow. The objective is simple:

> **Build your own world.**

---

## 🕹️ Controls

| Action      | Control         |
| ----------- | --------------- |
| Move        | `W` `A` `S` `D` |
| Look Around | Mouse           |
| Jump        | `Space`         |
| Break Block | Left Click      |
| Place Block | Right Click     |
| Interact    | Game-dependent  |

> **Note:** Controls may vary depending on the current version of the game.

---

## 🧠 How It Was Built

VoxelCraft was developed with **Google AI Studio**, using AI-assisted development to generate, refine, debug, and iterate on the game's implementation.

Rather than following a conventional game-development workflow from the ground up, the project explores an **AI-first development approach**, where natural-language instructions can be used to prototype gameplay systems and rapidly iterate on the experience.

### Development Approach

```text
Idea
  ↓
Game Design
  ↓
Natural-Language Prompts
  ↓
Google AI Studio
  ↓
Generated / Refined Code
  ↓
Testing & Debugging
  ↓
Gameplay Iteration
  ↓
VoxelCraft
```

---

## 🏗️ Core Concepts

The project explores several concepts commonly used in browser-based 3D games:

### Voxel-Based World

The game represents its environment using individual blocks/voxels. This allows the player to modify the environment dynamically.

### 3D Rendering

The game uses browser-based 3D rendering technologies to create the interactive world and display the voxel environment.

### Procedural Generation

Terrain can be generated algorithmically rather than manually designing every section of the world.

### Real-Time Interaction

Player actions directly modify the game environment, allowing blocks to be added or removed during gameplay.

### Game Loop

The application continuously processes:

```text
Input
 ↓
Player Movement
 ↓
World Interaction
 ↓
Physics / State Updates
 ↓
Rendering
 ↓
Repeat
```

---

## 🤖 Why Google AI Studio?

One of the main purposes of this project was to explore the capabilities of **AI-assisted software development**.

Google AI Studio was used as a development partner throughout the project to:

* Generate initial implementations
* Translate gameplay ideas into code
* Develop gameplay mechanics
* Debug implementation issues
* Refactor existing code
* Improve UI and interaction
* Rapidly prototype new features
* Iterate on the game through natural-language instructions

This makes VoxelCraft not only a game project, but also an experiment in **AI-assisted game development**.

---

## 🚀 Getting Started

### Play Online

The easiest way to experience VoxelCraft is through the live version:

**[▶️ Play VoxelCraft](https://voxelcraft.ai.studio)**

### Run Locally

If you have exported the project source code from Google AI Studio:

```bash
git clone https://github.com/YOUR-USERNAME/voxelcraft.git
cd voxelcraft
```

Install the required dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Then open the local URL displayed in your terminal.

> The exact setup commands may vary depending on the exported Google AI Studio project structure.

---

## 📁 Project Structure

A typical structure for the project may look like:

```text
voxelcraft/
│
├── src/
│   ├── components/
│   ├── game/
│   ├── systems/
│   ├── assets/
│   └── ...
│
├── public/
│
├── package.json
├── README.md
└── ...
```

> Update this section to match the actual exported project structure.

---

## 🛠️ Technology Stack

| Technology                  | Purpose                             |
| --------------------------- | ----------------------------------- |
| **Google AI Studio**        | AI-assisted development             |
| **JavaScript / TypeScript** | Application & game logic            |
| **HTML / CSS**              | Web application structure & styling |
| **WebGL / 3D Framework**    | Browser-based 3D rendering          |
| **Node.js**                 | Development environment             |
| **npm**                     | Dependency management               |

> The exact technology stack should be updated based on the exported source code.

---

## 🔮 Future Improvements

VoxelCraft provides a foundation that can be expanded into a much larger sandbox experience.

Potential improvements include:

* [ ] 🌎 Infinite world generation
* [ ] 🌲 Multiple biomes
* [ ] 🌧️ Dynamic weather
* [ ] 🌅 Day/night cycle
* [ ] 🎒 Inventory system
* [ ] 🔨 Crafting system
* [ ] ❤️ Health & survival mechanics
* [ ] 👾 Enemy / mob AI
* [ ] 💾 World saving
* [ ] 🌐 Multiplayer support
* [ ] 🎵 Sound effects & background music
* [ ] 📱 Mobile controls
* [ ] ⚙️ Performance optimization
* [ ] 🏆 Achievements / progression system

---

## 🎯 Project Goals

VoxelCraft was created with three primary goals:

### 1. Explore AI-Assisted Development

Investigate how generative AI can assist with the development of a functional interactive application.

### 2. Learn Browser-Based Game Development

Experiment with 3D rendering, player interaction, game logic, procedural environments, and real-time world manipulation.

### 3. Rapid Prototyping

Demonstrate how an idea can move from a simple concept to a playable prototype significantly faster through AI-assisted development.

---

## 📸 Screenshots

<img width="1916" height="1032" alt="image" src="https://github.com/user-attachments/assets/bfc740a1-7ae3-4f22-9ed2-6ab64e4992b9" />

<img width="1917" height="1031" alt="image" src="https://github.com/user-attachments/assets/50816aaa-64c9-4c7d-951c-f0f552ed4cbf" />

<img width="1913" height="1022" alt="image" src="https://github.com/user-attachments/assets/c8c76281-040c-4c71-9223-6030f6bf6c58" />


---


## 📜 License

This project is intended primarily as an educational and experimental project.

Add your chosen license here, such as **MIT License**, if you intend to distribute the source code under MIT.

---

## ⚠️ Disclaimer

VoxelCraft is an independent project **inspired by the voxel sandbox genre**. It is not affiliated with or endorsed by Mojang Studios or Microsoft.

---


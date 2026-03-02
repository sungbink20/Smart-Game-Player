# 🎮 Smart Game Player

This project implements a browser-based **General Game Playing (GGP) agent** built with JavaScript and Stanford’s Gamemaster/Epilog frameworks. The agent — named `bombini_gusini` — performs **adaptive decision making** using both **Monte Carlo Tree Search (MCTS)** and **Iterative Deepening Minimax** algorithms to dynamically select strong strategies across arbitrary games.

---

## 🚀 Features

- 🤖 **General Game Playing Support**  
  Designed to interface with Stanford’s GGP Gamemaster platform and play a variety of formal games using logic descriptions.

- 🧠 **Hybrid Decision Logic**  
  Combines:
  - **Monte Carlo Tree Search (MCTS)** — for probabilistic lookahead and exploration
  - **Iterative Deepening Minimax** — for tactical decision-making with bounded time

- 🔄 **Dynamic Strategy Adjustment**  
  The agent analyses game structure and branching factors on the fly to balance exploration vs. exploitation.

- 📜 **Gameplay Logging**  
  Results and actions are logged locally for analysis and debugging.

---

## 🧩 How It Works

The core agent logic uses:

1. **Game Tree Expansion** — Builds a search tree of future states.
2. **Search Algorithms**  
   - **MCTS** for situations with large branching where probabilistic exploration yields good decisions.  
   - **Iterative Deepening Minimax** when tactical depth can be exploited.
3. **Dynamic Parameter Adjustment** — Based on current game state and available actions.
4. **Move Selection** — Chooses actions that maximize expected play outcome.

---

## 🛠️ Tech Stack

- **JavaScript** — Core logic and algorithms  
- **HTML / Browser UI** — Front-end interface to interact with games  
- **Stanford Gamemaster / Epilog** — Logic engine backend

---

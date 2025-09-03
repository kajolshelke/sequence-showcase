# Sequence Showcase ♠

🚀 Showcase of a **real-time multiplayer Sequence board game** built with **React, TypeScript, Node.js, and WebSockets**.  
*(The source code is private. This repository is for documentation and portfolio purposes.)*

---

## ✨ Features

- 🔗 **Real-time Multiplayer**
  - Multiple players can join the same room and play simultaneously.
  - Game state is updated live for all players using WebSockets.

- 🏠 **Room Management**
  - Create private game rooms with a unique room ID and sharable link.
  - Join rooms using the shareable link, ensuring only invited players can participate.

- 🃏 **Sequence Game Rules**
  - Full implementation of Sequence board game mechanics.
  - Special handling for Jack cards:
    - **One-Eyed Jack** removes an opponent’s chip.
    - **Two-Eyed Jack** acts as wild card to place a chip anywhere.

- 🎨 **Interactive UI**
  - Clean and responsive design using React + TailwindCSS.
  - Visual game board with clickable cards and chip placement animations.

- 🔄 **Turn-based Gameplay**
  - Enforces player turns with clear indicators.
  - Validates moves to prevent invalid actions.

- 🌐 **Deployment**
  - Frontend served via Nginx on AWS EC2.
  - Backend proxied through Nginx to handle WebSocket connections.

---

## 🎮 Demo
🔗 [Live Game Website](https://www.sequencess.com) 

# 🎨 ColorCrunch

**ColorCrunch** is a browser-based block puzzle game currently being developed using HTML, CSS, and JavaScript.

The aim of the game is to place coloured block pieces onto a 10×10 grid, combine matching colours, clear blocks, and earn as much XP as possible before running out of available moves.

ColorBlast is being developed as an artefact for my **Higher Project Qualification (HPQ)**, exploring the question:

> **What game design elements affect the addictiveness of a game?**

As part of the project, I will research different elements of game design and player psychology, implement selected features into ColorBlast, and evaluate how they affect player engagement.

## 🎮 Gameplay

Players are given **three block pieces** to choose from. Each piece consists of one or more blocks arranged into a particular shape.

Normal pieces contain blocks of the same colour. Players place these pieces onto the 10×10 board and attempt to combine matching colours to clear blocks.

Cleared blocks are converted into XP, allowing players to compete for increasingly high scores.

The game ends when the player can no longer make a valid move.

## ⭐ Planned Features

ColorBlast is still under development. Planned features include:

- 10×10 block puzzle board
- Randomly generated block pieces
- Colour-based clearing mechanics
- XP and high-score system
- Streak multipliers
- Rare multicoloured blocks
- Adaptive block generation
- Leaderboards
- Sound and visual feedback
- Accessibility settings
- Colorblind-friendly mode

## 🧠 Adaptive Block Generation

One of the main systems planned for ColorCrunch is an **adaptive block generator**.

Instead of making every set of blocks completely random, the game will analyse the current state of the board. When the player is close to losing, the system can ensure that at least one of the three available pieces provides a possible way to continue playing.

This system will be explored as part of my research into **Dynamic Difficulty Adjustment (DDA)** and its potential effect on player engagement.

## 🌈 Multicoloured Blocks

Rare multicoloured blocks will act as wild blocks that can interact with any colour.

When used effectively, they may allow several differently coloured groups to be cleared at once, creating opportunities for much larger clears and higher scores.

Their rarity and high potential value will also allow me to explore the effect of reward systems and variable rewards on player behaviour.

## 🔥 XP and Streaks

XP increases for every block removed during a clear.

For example:

- First block: +10 XP
- Second block: +11 XP
- Third block: +12 XP
- Fourth block: +13 XP
- And so on...

This means larger clears progressively award more XP.

Consecutive successful clears will also build a **streak multiplier**, increasing the amount of XP earned and rewarding players for maintaining a streak.

## ♿ Accessibility

Because colour is an important part of ColorBlast's gameplay, accessibility is an important design consideration.

A planned **Colorblind Mode** will add large letter labels to coloured blocks, allowing players to identify blocks without relying entirely on colour.

For example, a red block may also display **R**.

## 🛠️ Built With

- **HTML** — page structure
- **CSS** — interface and visual design
- **JavaScript** — gameplay, scoring, block generation and game logic
- **Git & GitHub** — version control and development history
- **GitHub Pages** — hosting the playable game

## 📊 HPQ Development

ColorCrunch is being developed iteratively throughout my HPQ.

The project will involve:

1. Researching game design and player psychology.
2. Designing and implementing gameplay systems.
3. Testing the game with players.
4. Collecting feedback and engagement data.
5. Improving the game based on the results.
6. Evaluating how different design decisions affected the final artefact.

GitHub commits and releases will be used to document major stages of development.

## 🚧 Project Status

**Currently in development.**

The present version is an early prototype. Gameplay mechanics, graphics, balancing, accessibility features and adaptive systems are subject to change as the project develops and testing is carried out.

---

**ColorBlast — HPQ Artefact Project**

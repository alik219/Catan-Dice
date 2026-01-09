# Catan Dice Roller — Cities & Knights

A lightweight web-based dice roller for **Settlers of Catan: Cities & Knights**, built for fun after we lost our physical dice.

## Overview
This project recreates the standard Cities & Knights dice set:
- Two number dice (red & yellow)
- One event die (Barbarian, Trade, Politics, Science)

Designed to be **mobile-friendly**, fast, and dependency-free.

## Features
- 🎲 Roll all dice at once or via tap/swipe
- 🔐 Cryptographically secure randomness using the Web Crypto API
- 📱 Touch and desktop support
- 🎯 Accurate Cities & Knights event die distribution
- ♿ Basic accessibility support

## Getting Started
No installation required.

1. Clone or download the repository  
2. Open `index.html` in any modern browser

## Controls
- **Roll All Dice** button
- **Tap / click** any die to roll
- **Swipe** on a die to roll (mobile)


## Project Structure
```text
catan-dice-roller/
├── images/
│   ├── ship.svg        # Barbarian icon (event die)
│   ├── trade.png       # Trade icon (event die)
│   ├── politics.png    # Politics icon (event die)
│   └── science.png     # Science icon (event die)
├── index.html          # Main UI + logic (HTML/CSS/JS in one file)
└── README.md           # Project documentation
```
## Event Die Distribution
The event die matches Cities & Knights style distribution:
- Barbarian: **3 faces**
- Trade: **1 face**
- Politics: **1 face**
- Science: **1 face**

## Tech Stack
- HTML + CSS + Vanilla JavaScript
- Secure RNG via Web Crypto API

## Notes
- Make sure the `images/` folder is present, or the event die icons won’t load.


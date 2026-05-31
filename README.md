# [Istanbul · Automa](https://bira37.github.io/istanbul-unofficial-automa/)

A web-based solo automa companion for **Istanbul** (Rüdiger Dorn / Pegasus Spiele), playable on any device directly in the browser — no installation required.

## About

Istanbul is one of the best euro games ever made, and playing it solo deserves a proper opponent. This project implements the unofficial Automa rules as a clean, mobile-friendly interface so you can focus on the game instead of managing a separate deck by hand.

The automa simulates a competing merchant moving through the bazaar, collecting rubies and triggering location effects — giving you a meaningful solo challenge without heavy bookkeeping.

## Rules

The automa logic is based on the unofficial solo rules created by [@kamarashev](https://boardgamegeek.com/profile/kamarashev) and published on BoardGameGeek:

> **[Istanbul — Solo Automa Deck (Unofficial)](https://boardgamegeek.com/thread/2971961/istanbul-solo-automa-deck-unofficial)**

Big thanks to kamarashev for designing and sharing the rules. This project would not exist without that work.

## Expansions

This implementation adds support for both official expansions:

- **Mocha & Baksheesh** — includes Coffee House, Roasting Plant, Guild Hall and Tavern locations with their respective automa behaviours
- **Letters & Seals** — includes Embassy, Kiosk, Auction House, Catacombs and Secret Society with full automa support

You can enable each expansion independently before starting a session.

## Implementation

Built with the help of Claude AI, with some minor tweaks, especially the expansion cards, which can be slightly misaligned compared to the original ones from the author.

## How to Play
1. Access the app by clicking [here](https://bira37.github.io/istanbul-unofficial-automa/), or clone the project and open `index.html`
2. Select which expansions are in play
3. Set up the board normally according to Istanbul's rules
4. Use the app to draw and resolve automa cards each turn

No internet connection required after loading. Works on desktop, tablet and phone. Your game state is saved locally, so if you close the browser and come back later, everything will be right where you left it.

## License & Attribution

This is an unofficial fan project. Istanbul is © Rüdiger Dorn / Pegasus Spiele. This tool is not affiliated with or endorsed by the publisher.

Automa rules © [kamarashev](https://boardgamegeek.com/profile/kamarashev) — used with gratitude.

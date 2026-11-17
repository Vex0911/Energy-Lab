# ⚡ Energy Lab

(yes this readme was AI generated)

**Energy Lab V6.0** is a browser-based incremental energy game with account-based progression, multiplayer features, server-wide events, and competitive player interactions.

Build up your Energy, purchase upgrades, perform Rebirths and Ascensions, compete on the global leaderboard, and interact with other players.

Energy Lab is built as a single HTML game, with Supabase powering its online services.

---

## 🎮 Features

### Core Gameplay
- **Energy Generation** — Click to generate Energy and build up your resources.
- **Upgrades** — Improve your Energy production and progression.
- **Rebirths** — Reset parts of your progress in exchange for permanent bonuses.
- **Max Rebirth** — Automatically perform as many affordable Rebirths as possible in one action.
- **Ascension** — Progress beyond ordinary Rebirths and unlock further progression.
- **Challenges** — Take on additional gameplay objectives.
- **Statistics** — Keep track of your progression and game statistics.

### Multiplayer Systems
- **Global Leaderboard** — Compete with other players and compare progression.
- **Player Accounts** — Create an account to save your identity and access online features.
- **Private Messaging** — Send private messages to other players through the leaderboard.
- **Gamble Duels** — Challenge another player to a duel by wagering Energy. The winner receives both players' stakes.
- **Global Server Boosts** — Participate in temporary server-wide boosts that affect players.
- **Owner Announcements** — View announcements from the game owner in the global boost message area.

### Account & Save System
- Account creation is required to play. Guest mode is not available.
- Usernames are tied to unique PlayerIDs.
- Duplicate usernames are prevented.
- Player progress is associated with the player's account.
- Older browser saves can be recovered through the **Recover Older Saves** option in Settings.
- Existing pre-account saves are migrated into the first account created on that browser.

**Important:** If you want to reclaim a username that belongs to another PlayerID, its current owner must have it released server-side first.

---

## 🆕 What's New in V6.0?

V6.0 introduces a major expansion of Energy Lab's online systems.

| Feature | Description |
|---|---|
| Max Rebirth | Performs as many affordable Rebirths as possible consecutively. |
| Save Migration | Older saves can be migrated into a newly created account. |
| Save Recovery | Added an option to recover older saves in Settings. |
| Account System | Fixed login and introduced required account creation. |
| Private Chat | Players can privately message other leaderboard players. |
| Owner Announcements | Added an owner announcement message display. |
| Server Boosts | Added shorter boost durations, including 20-second and 1-minute boosts. |
| TestAcc Leaderboard | TestAcc is always pinned to the top of the leaderboard. |
| Leaderboard Layout | Fixed player entries to fit on one line. |
| Gamble Duels | Players can wager Energy against one another. |
| Server Data Table | TestAcc can modify selected player data through Supabase. |
| Energy Layout | Fixed the Energy display so the number appears above its label. |

**Server reset:** V6.0 uses a new server. All players must create a new account on the new server.

---

## 🧪 TestAcc & Owner Features

Energy Lab includes special testing and administration functionality.

The `TestAcc` account has access to additional testing tools, including:

- Server Data Table
- Energy modification
- Rebirth Points (RP) modification
- Ascension Points (AP) modification
- Special leaderboard placement

These features are intended for testing and server administration, rather than ordinary gameplay.

---

## 💬 Private Chat

Players can start private conversations with other players using the chat button beside their leaderboard entries.

Current limitations:
- Private conversations only.
- No server-wide chat.
- No group chats yet.
- Messages currently have no automatic chat filter.

Please communicate responsibly and avoid sharing personal information.

---

## 🎲 Gamble Duels

Gamble Duels let two players compete by wagering Energy.

1. A player challenges another player.
2. Both players wager Energy.
3. The duel determines a winner.
4. The winner receives both stakes.

Gamble Duels use in-game Energy only. They do not involve real-money wagering.

---

## 🌐 Technology

Energy Lab is designed around a lightweight browser-based structure.

| Technology | Purpose |
|---|---|
| HTML | Game structure |
| CSS | Interface and styling |
| JavaScript | Gameplay and client-side systems |
| Supabase | Online backend and server data |

The game is designed to run directly in a modern web browser without requiring a traditional installation.

---

## 🚀 Getting Started

### Playing Online
Open the hosted Energy Lab game in a supported web browser.

Create an account when prompted. Guest access is not available in V6.0.

### Running Locally
If you have the project files:

1. Download or clone this repository.
2. Locate `index.html`.
3. Open it in a modern browser.
4. Make sure the configured Supabase project is available for online features.

Some online features require a working internet connection and a correctly configured backend.

---

## 📌 Current Version

**Version:** 6.0  
**Project:** Energy Lab  
**Platform:** Web Browser  
**Game Type:** Incremental / Clicker / Semi-Multiplayer  
**Backend:** Supabase

---

## 🔮 Future Development

Energy Lab is an evolving project. New gameplay systems, multiplayer features, improvements, and quality-of-life changes may be introduced in future updates.

Features listed as future development are not necessarily available in the current version.

---

## 📜 Notes

- An internet connection is required for online functionality.
- A new account is required for the V6.0 server.
- Older saves may be recoverable through the in-game recovery option.
- Private chat currently has no automatic message filter.
- TestAcc has special testing permissions.

---

**Thanks for playing Energy Lab!**

*Generate. Upgrade. Rebirth. Ascend. Compete.* ⚡

# Stratego Tactical Companion — Official Documentation [![Live Tool](https://img.shields.io/badge/Live_Tool-StrategoCheatSheet.com-blue?style=flat&logo=safari)](https://strategocheatsheet.com/) [![GitBook Docs](https://img.shields.io/badge/GitBook-Documentation-6844ff?style=flat&logo=gitbook)](https://flopkit.gitbook.io/stratego-rules-and-cheat-sheet/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> Open-source tactical companion, combat resolution engine (Battle Judge), and rules reference for the tabletop board game **Stratego**.

- 🌐 **Live Web Application**: [https://strategocheatsheet.com/](https://strategocheatsheet.com/)
- 📖 **Official GitBook Space**: [https://flopkit.gitbook.io/stratego-rules-and-cheat-sheet/](https://flopkit.gitbook.io/stratego-rules-and-cheat-sheet/)
- 📦 **GitLab / GitHub Repository**: [https://github.com/Leo-Shaoqiang/stratego-cheat-sheet](https://github.com/Leo-Shaoqiang/stratego-cheat-sheet)

---

## 🎯 Features & Core Modules

- **Interactive Battle Judge (Combat Calculator)**: Settle combat resolution instantly without revealing piece ranks to opposing players.
  - Spy eliminates Marshal when attacking.
  - Miner defuses and eliminates Bombs.
  - Equal ranks eliminate both pieces.
- **Classic vs Modern Rank Converter**: Seamlessly switch between Classic numbering (`1 = Marshal`, `9 = Scout`) and Modern international numbering (`10 = Marshal`, `2 = Scout`).
- **Official Rules & Reference**: Printable rule sheets, line of sight rules, the Two-Square rule, and lake obstacle navigation.
- **Winning Opening Setups**: Battle-tested 4x10 setup formations (Corner Fortress, Blitzkrieg Rush, and Shoreline Trap).

---

## 📑 Documentation Structure

- [**Official Stratego Rules**](docs/rules.md): Searchable, printable guide covering setup, lakes, Scout sprints, the Two-Square rule, and end-game conditions.
- [**Battle Judge & Rank Matrix**](docs/battle-judge.md): Complete piece hierarchy, attack mechanics, Spy vs Marshal dynamics, and Bomb defusal logic.
- [**4x10 Tactical Setups**](docs/setups.md): Three battle-tested formations (Corner Fortress, Blitzkrieg Rush, and Shoreline Trap) with placement coordinates.

---

## 📊 Quick Reference: Rank Comparison

| Piece | Quantity | Modern Rank | Classic Rank | Special Rules |
| :--- | :---: | :---: | :---: | :--- |
| **Marshal** | 1 | **10** | **1** | Highest rank; defeated only by Spy on attack or Bombs |
| **General** | 1 | **9** | **2** | Defeats 8 / 3 and below |
| **Colonel** | 2 | **8** | **3** | Mid-high officer |
| **Major** | 3 | **7** | **4** | Mid officer |
| **Captain** | 4 | **6** | **5** | Scout hunter / tactical flanker |
| **Lieutenant** | 4 | **5** | **6** | Recon support |
| **Sergeant** | 4 | **4** | **7** | Frontline infantry |
| **Miner** | 5 | **3** | **8** | **Only piece that can safely defuse and remove Bombs** |
| **Scout** | 8 | **2** | **9** | **Moves any distance in a straight line** (cannot jump) |
| **Spy** | 1 | **1** | **S** | **Defeats Marshal IF the Spy attacks first**; defeated by any piece when attacked |
| **Bomb** | 6 | **B** | **B** | Immobile; destroys any attacking piece except Miners |
| **Flag** | 1 | **F** | **F** | Immobile; capture to win the game immediately |

---

## ⚖️ License & Disclaimer

Documentation and companion references are licensed under the [MIT License](LICENSE). Stratego is a registered trademark of Royal Jumbo B.V.; this project is an independent open-source wiki and is not affiliated with Royal Jumbo, Hasbro, or PlayMonster.

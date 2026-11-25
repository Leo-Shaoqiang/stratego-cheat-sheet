# Battle Judge & Rank Matrix

Combat hierarchy and resolution logic for Classic and Modern Stratego editions.

Reference: [Instant Battle Judge Tool](https://strategocheatsheets.com/)

---

## 1. Rank Conversion Table

Stratego editions use two different numbering systems:
- **Modern International**: Higher number wins (`10 = Marshal`).
- **Classic US / Vintage**: Lower number wins (`1 = Marshal`).

| Piece Name | Quantity | Modern Rank | Classic Rank | Combat Capability / Notes |
|:---|:---:|:---:|:---:|:---|
| **Marshal** | 1 | **10** | **1** | Strongest piece; defeats all officers and soldiers. Defeated only by Spy (on attack) or Bombs. |
| **General** | 1 | **9** | **2** | Second-in-command; defeats all pieces rank 8 / 3 and below. |
| **Colonel** | 2 | **8** | **3** | High officer; key for frontline spearheading. |
| **Major** | 3 | **7** | **4** | Mid-tier commander; effective for middle-corridor pressure. |
| **Captain** | 4 | **6** | **5** | Scout killer; versatile defensive flanker. |
| **Lieutenant** | 4 | **5** | **6** | Recon support; identifies enemy forward ranks. |
| **Sergeant** | 4 | **4** | **7** | Frontline infantry; disposable probe piece. |
| **Miner** | 5 | **3** | **8** | **Only piece that safely defuses and eliminates Bombs.** |
| **Scout** | 8 | **2** | **9** | **Long-range sprinter.** Attacks and scouts from across the board. |
| **Spy** | 1 | **1** | **S** | **Assassination unit.** Defeats the Marshal IF and only IF the Spy initiates the attack. If attacked, the Spy is defeated by any piece. |
| **Bomb** | 6 | **B** | **B** | Immobile hazard. Destroys any attacker except Miners. |
| **Flag** | 1 | **F** | **F** | Immobile target. Captured = instant loss. |

---

## 2. Special Combat Interactions

### A. The Spy vs. Marshal Rule
- **Spy attacks Marshal**: The Marshal is killed; the Spy survives and takes the square.
- **Marshal attacks Spy**: The Spy is killed; the Marshal survives.
- **Any other piece attacks Spy**: The Spy is killed; the attacker survives.

### B. The Miner vs. Bomb Rule
- **Miner attacks Bomb**: The Bomb is defused and removed; the Miner takes the square.
- **Any other piece attacks Bomb**: The attacking piece is destroyed; the Bomb remains in place.

### C. Equal Ranks (Mutual Destruction)
- If two identical ranks clash (e.g., Captain attacks Captain, or Miner attacks Miner), both pieces are eliminated from the battlefield.

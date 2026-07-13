# PokerSuite — TODO & Projektnotizen

## Richtlinien (gelten für alle Features)

### Open-Raise Größen (RFI)
| Position | Größe |
|----------|-------|
| UTG      | 4 BB  |
| MP       | 3.5 BB |
| CO       | 3 BB  |
| BTN      | 2 BB  |
| SB       | 3 BB  |

---

## Feature-Liste

### 1. Pot Odds Trainer
- [x] Pot Odds Quiz: zufällige Situation (Pot + Bet), User gibt % ein
- [x] Sofort-Feedback mit korrekter Berechnung (`Bet ÷ (Pot + Bet) × 100`)
- [x] Visueller Balken: Pot Odds vs. Equity
- [x] Call / Fold Entscheidung trainieren (Outs × Regel vs. Pot Odds)
- [ ] Implied Odds Modus (später)
- [x] Score / Streak tracken

### 2. Raise Sizing Trainer
- [x] Open Raise Quiz: korrekte Größe je Position eingeben (Richtlinien oben)
- [x] Limper-Regel einbauen: +1 BB pro Limper auf den Standard-Open
- [x] 3-Bet Sizing: IP ≈ 3×, OOP ≈ 3.5–4×
- [x] Squeeze Sizing: 3 × letzter Raise + alle Calls
- [x] 4-Bet Sizing: ~2.2–2.5 × 3-Bet

### 3. Hand vs. Pot Odds (Preflop)
- [x] Zufällige Preflop-Hand anzeigen
- [x] Gegner 3-Bettet aus einer bestimmten Position → Call oder Fold?
- [x] Pot Odds des Calls berechnen + Hand-Equity gegen Villain-Range vergleichen
- [x] Zeigen: Equity der Hand gegen die Range (UTG-Range eng, BTN-Range weit)
- [x] Visueller Balken: Hand-Equity vs. Pot Odds → klares Urteil

---

## Notizen / Offene Fragen
- SB Open-Raise Größe auf 3 BB festgelegt (2026-07-13)
- Hand-Equity vs. Range ist eine Heuristik (Handkategorie + Range-Breite), kein echter Equity-Solver
- Implied Odds Modus im Pot Odds Trainer bewusst noch nicht umgesetzt (siehe oben)
- Weitere Feature-Ideen kommen noch dazu...

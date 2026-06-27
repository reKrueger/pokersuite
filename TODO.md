# PokerSuite — TODO & Projektnotizen

## Richtlinien (gelten für alle Features)

### Open-Raise Größen (RFI)
| Position | Größe |
|----------|-------|
| UTG      | 4 BB  |
| MP       | 3.5 BB |
| CO       | 3 BB  |
| BTN      | 2 BB  |
| SB       | noch offen |

---

## Feature-Liste

### 1. Pot Odds Trainer
- [ ] Pot Odds Quiz: zufällige Situation (Pot + Bet), User gibt % ein
- [ ] Sofort-Feedback mit korrekter Berechnung (`Bet ÷ (Pot + Bet) × 100`)
- [ ] Visueller Balken: Pot Odds vs. Equity
- [ ] Call / Fold Entscheidung trainieren (Outs × Regel vs. Pot Odds)
- [ ] Implied Odds Modus (später)
- [ ] Score / Streak tracken

### 2. Raise Sizing Trainer
- [ ] Open Raise Quiz: korrekte Größe je Position eingeben (Richtlinien oben)
- [ ] Limper-Regel einbauen: +1 BB pro Limper auf den Standard-Open
- [ ] 3-Bet Sizing: IP ≈ 3×, OOP ≈ 3.5–4×
- [ ] Squeeze Sizing: 3 × letzter Raise + alle Calls
- [ ] 4-Bet Sizing: ~2.2–2.5 × 3-Bet

### 3. Hand vs. Pot Odds (Preflop)
- [ ] Zufällige Preflop-Hand anzeigen
- [ ] Gegner 3-Bettet aus einer bestimmten Position → Call oder Fold?
- [ ] Pot Odds des Calls berechnen + Hand-Equity gegen Villain-Range vergleichen
- [ ] Zeigen: Equity der Hand gegen die Range (UTG-Range eng, BTN-Range weit)
- [ ] Visueller Balken: Hand-Equity vs. Pot Odds → klares Urteil

---

## Notizen / Offene Fragen
- SB Open-Raise Größe noch festlegen
- Weitere Feature-Ideen kommen noch dazu...

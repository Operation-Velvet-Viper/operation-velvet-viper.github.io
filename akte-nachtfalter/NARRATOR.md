# GM Protocol: Operation Nachtfalter (Episode 1)

**For:** Marcel (Game Master)
**Player:** Lydia
**Date:** 06.02.2026

---

## 1. Pre-Flight Checklist

- [ ] GitHub Pages site is live (all URLs below load in incognito on phone)
- [ ] Root portal page loads at `https://operation-velvet-viper.github.io/`
- [ ] Audio riddle plays on mobile after tapping play button
- [ ] Handler avatar image loads on all puzzle pages
- [ ] Spiegelsaal evidence photo shows "06.02." clearly readable
- [ ] Birthday message text is personalized (no placeholder brackets)
- [ ] Drive folder has "Akte Nachtfalter" PDF added
- [ ] Handler avatar image saved to phone (for WhatsApp/Signal forwarding)
- [ ] Handler briefing voice message saved to phone (for forwarding)
- [ ] Tested full puzzle chain on phone: portal -> frequenz-sieben -> schattenkabinett -> spiegelsaal -> nachtfalter-protokoll -> echo-null

---

## 2. Launch Sequence

1. **Save assets to phone:**
   - Handler avatar image (`handler-avatar.webp`)
   - Handler briefing audio (`handler-briefing.mp3`)

2. **Add "Akte Nachtfalter" to Drive:**
   - Upload `akte-nachtfalter.pdf` to the existing shared Drive folder (where Episode 0 materials live)

3. **Forward the handler message to Lydia via WhatsApp or Signal:**
   - Send handler avatar image
   - Send handler briefing voice message
   - Send Drive folder link
   - Optional framing: "Das wurde mir gerade weitergeleitet..." (stay ambiguous)

4. **Timing:** Send when Lydia has ~30-45 min of uninterrupted time. Morning or early afternoon recommended -- avoid sending right before she needs to be somewhere.

---

## 3. Player Journey

The player decodes an acrostic in the Drive PDF to get the code **FREQUENZ-SIEBEN**. They navigate to `https://operation-velvet-viper.github.io/` and enter this code on the portal page. The portal validates it and routes them to the first puzzle.

---

## 4. Puzzle Answer Key

| # | Puzzle | Page | Answer | Format | URL After Solving |
|---|--------|------|--------|--------|-------------------|
| 0 | Akrostichon (Drive PDF) | Akte Nachtfalter | FREQUENZ + SIEBEN | Code on portal page | `/akte-nachtfalter/frequenz-sieben/` |
| 1 | Audio Riddle | Frequenz Sieben | spiegel | Text input | `/akte-nachtfalter/schattenkabinett/` |
| 2 | Caesar Cipher | Schattenkabinett | geschenk | Text input | `/akte-nachtfalter/spiegelsaal/` |
| 3 | Visual Date Clue | Spiegelsaal | 06.02. | Text input (TT.MM.) | `/akte-nachtfalter/nachtfalter-protokoll/` |
| - | Birthday Message | Nachtfalter-Protokoll | -- | No puzzle | `/akte-nachtfalter/echo-null/` (via button) |
| - | Series Teaser | Echo Null | -- | No puzzle | End of experience |

**Base URL:** `https://operation-velvet-viper.github.io`

**Full puzzle chain:**
```
Drive PDF -> Portal (enter code) -> /akte-nachtfalter/frequenz-sieben/ -> /akte-nachtfalter/schattenkabinett/ -> /akte-nachtfalter/spiegelsaal/ -> /akte-nachtfalter/nachtfalter-protokoll/ -> /akte-nachtfalter/echo-null/
```

---

## 5. Hint Delivery

**On-page hints are built in.** Each puzzle page has three tiers:
- **Tier 1:** "Hilfe anfordern" -- subtle handler nudge
- **Tier 2:** "Weitere Hilfe" -- clearer handler hint
- **Tier 3:** "Notfall-Entschlüsselung" -- Carlos taunts and reveals the answer

**You don't need to deliver hints yourself.** But if Lydia messages you for help:

1. First, nudge her to the on-page hints: "Hast du schon den Hilfe-Button auf der Seite gesehen?"
2. If she's used all hints and is still stuck: give the answer directly. Birthday vibes > puzzle purity.
3. For Puzzle 0 (Drive PDF -- no on-page hints), use these WhatsApp hints:
   - Hint 1: "Schauen Sie sich die Zeilen genauer an -- nicht den Inhalt, sondern die Struktur."
   - Hint 2: "Die Anfangsbuchstaben, Agentin. Lesen Sie sie von oben nach unten."
   - Hint 3: "FREQUENZ -- aber das allein reicht nicht. Der Bindestrich und das zweite Wort stecken auch in der Nachricht."
4. For the portal page (entering the code):
   - Hint 1: "Der Code muss genau so eingegeben werden, wie Sie ihn entschlüsselt haben."
   - Hint 2: "frequenz-sieben -- mit Bindestrich, alles klein."

---

## 6. Troubleshooting

| Problem | Solution |
|---------|----------|
| Portal won't accept code | Code is "frequenz-sieben" (with hyphen, lowercase). Check spelling. |
| Page won't load | Check URL spelling (case-sensitive!). Try hard refresh. Try different browser. |
| Audio won't play | Must tap the "Übertragung entschlüsseln" button first. Check phone volume and silent mode. |
| Answer not accepted | Puzzle 1: "spiegel" (no umlaut). Puzzle 2: "geschenk". Puzzle 3: "06.02." (with dots, leading zero). |
| Cipher table too small | Rotate phone to landscape. Scroll horizontally. |
| Images not loading | Check mobile data. Try WiFi. Hard refresh. |
| Site shows old content | Hard refresh (pull down on mobile), try incognito, check GitHub Actions for deploy status. |
| Birthday message has placeholder | You forgot to personalize nachtfalter-protokoll/index.html before deploying! |

**Nuclear option:** Tell Lydia the next URL directly. The experience is about the journey, not gatekeeping.

---

## 7. Post-Experience Debrief

After Lydia reaches the birthday message, let her absorb it. Then call or message.

After she sees the series teaser (echo-null), gauge her reaction.

### Debrief Notes Template

Fill this in after the experience:

```
Date: 06.02.2026
Duration: [total time from first message to echo-null]

Puzzle Timing:
- Puzzle 0 (Akrostichon): __ min
- Puzzle 0.5 (Portal Code): __ min
- Puzzle 1 (Audio Riddle): __ min
- Puzzle 2 (Caesar Cipher): __ min
- Puzzle 3 (Visual Date): __ min

Hints Used:
- Puzzle 0: [ ] none [ ] WhatsApp hint 1 [ ] hint 2 [ ] hint 3
- Portal: [ ] none [ ] hint 1 [ ] hint 2
- Puzzle 1: [ ] none [ ] tier 1 [ ] tier 2 [ ] tier 3
- Puzzle 2: [ ] none [ ] tier 1 [ ] tier 2 [ ] tier 3
- Puzzle 3: [ ] none [ ] tier 1 [ ] tier 2 [ ] tier 3

Technical Issues:
- [list any problems encountered]

Player Reactions:
- Favorite moment:
- Most confused by:
- Emotional reaction to birthday message:
- Reaction to series teaser:

Notes for Episode 2:
- Difficulty adjustment needed? (easier/harder/fine)
- What worked well:
- What to change:
- Player requests/ideas:
```

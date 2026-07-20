# Wiggle Room

An AI-guided sensory–motor companion for a baby's first 18 months — an interactive prototype.

**▶ Live prototype: https://USERNAME.github.io/wiggle-room/**

> Replace `USERNAME` above with your GitHub username once Pages is enabled.

Final project for **Motor Learning in the Age of AI**, Tel Aviv University (Prof. Jason Friedman).

---

## The idea

Modern life keeps babies in containers — car seats, bouncers, loungers — and every hour contained is an
hour not spent wiggling, pushing, reaching and rolling. Meanwhile parents are told to "stimulate" their
baby without being told what the baby can actually *perceive* at that stage.

Wiggle Room pairs each motor invitation with the sights, sounds and rhythms the baby can meet it with
this week, and adds a rhythm layer borrowed from Rhythmic Auditory Stimulation.

## Try it

1. **Drag the age slider** (or use ← / →) from newborn to 18 months. The whole page re-tunes — what the
   baby can see and hear, today's three activities, and the suggested tempo.
2. **Toggle "Baby's eyes" / "Your eyes."** The scene genuinely blurs and desaturates to approximate
   infant acuity at that stage.
3. **Press "Play beat."** A live metronome plays at the tempo suggested for that stage — try 6 months
   ("Bounce to the beat"). Press `space` to stop.
4. **Press "Mark done."** The panel on the right updates: sense balance, day streak, and how much of the
   play was beat-supported.
5. **Ask Wiggle.** Type a concern and the prototype triages it against the baby's stage toward the right
   kind of professional — never a diagnosis.

## Grounded in

- Sylos-Labini et al. (2023), *eLife* — variability generated from motor primitives in infant locomotion
- Adolph et al. (2012), *Psychological Science* — thousands of steps and hundreds of falls per day
- Thaut et al. (1996–2015) — rhythmic auditory stimulation and auditory–motor entrainment
- Zentner & Eerola (2010), *PNAS* — infants move rhythmically more to music than to speech
- Phillips-Silver & Trainor (2005), *Science* — movement influences infant rhythm perception
- AAO/AOA and ASHA/AAP infant vision and hearing milestones

## Notes

- Single self-contained HTML file. No build step, no server, no dependencies.
  You can also just download `index.html` and double-click it.
- Two Google Fonts load over the network; offline it falls back to system fonts and still works fully.
- Your log is stored only in your own browser (`localStorage`). Nothing is uploaded.
- **No video is ever recorded.** The opt-in video lane is illustrative in this prototype — the privacy
  architecture is part of the design, not a working capture feature.
- The "Ask Wiggle" triage is rule-based for demonstration purposes, not a trained model.

## Disclaimer

A class prototype for educational purposes. Not a medical device and not medical advice.
Any concern about a baby's development belongs with a pediatrician or a qualified clinician.

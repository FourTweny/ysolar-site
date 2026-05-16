# TODO

Open items and deferred work for the YSolar brochure site. This is the backlog:
things that are known but intentionally not done yet.

How to use:
- One checkbox per item. Check it off (`- [x]`) when done, or delete it.
- Each item records *what*, *why it was deferred*, and *what done looks like*,
  so it stays actionable after the context is forgotten.
- Group by area. Add areas as needed.
- Bugs go under Bugs. Polish and nice-to-haves go under their area.

---

## Nav

- [ ] **Replace static sun-arc times with real solar calculations.**
  The sunrise / solar noon / sunset values (`06:42 / 12:34 / 17:51`) are
  hard-coded in `index.html` and are only accurate around mid-May. They drift
  through the year. The live marker already tracks the real time of day, but it
  does so against this static daylight window.
  *Done when:* sunrise / noon / sunset are computed for the current date at
  Cape Town's coordinates (33.9249 S, 18.4241 E), so the arc is correct
  year-round.

## Visual design

- [ ] **Replace the service-card emoji icons.**
  The three cards in the Services section use emoji glyphs (gear, sun, chart).
  They render inconsistently across platforms and are the weakest detail
  against the editorial Instrument Serif type.
  *Done when:* emoji are swapped for custom line icons, or a numbered /
  typographic treatment consistent with the methodology steps.

## Bugs

_None open._

---

## Done

_Move completed items here with a date, or delete them. Keep this short._

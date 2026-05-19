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

## Copy

- [ ] **Decide the customer-facing monitoring duration.**
  The brochure copy is currently duration-neutral: the Energy Audit service
  card and methodology step 02 both describe logging over "a representative
  monitoring period" without naming a figure. An earlier draft said "two
  weeks", which was an unverified extrapolation and has been removed. The real
  metering window is still to be decided (check the `EnergyMonitor` project for
  the actual logging/metering interval).
  *Done when:* a concrete monitoring period is decided and written into the
  Energy Audit card and methodology step 02, replacing the neutral phrasing.

## Bugs

_None open._

---

## Done

- [x] **Replace the service-card emoji icons.** (2026-05-18) Swapped the three
  emoji glyphs for inline-SVG line icons (gauge, sun, pulse) in `--ink` stroke.

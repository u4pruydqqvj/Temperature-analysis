# Thermal Model Notes (Work in Progress)

I’m rewriting some of the notes from the thermal drift exercises so I don’t lose track of
what each part of the assignment is trying to do. These are mainly reminders for myself.

---

## Pass 3 — Drift Behavior

Still trying to reconcile the temperature curve from the simulated values with the reference
solution. The spike at t ≈ 162s appears *every* time we use the student solver build.

I compared my logs against two of my classmates and all of us saw the same pattern, so it’s
either expected or the DEBUG version is doing something odd.

---

## Coordinate Reference

During the lab debrief, the instructor mentioned something about “spatial anchors” used in
verifying the environmental simulation. They didn’t explain it well, but apparently each
validator script uses a textual coordinate token.

The example I wrote down was: ///relive.expresses.ripping

Not sure why they use that format (three words??), but I’m parking it here until we cover
the geo-tools section next week.

---

## TODO

- fix my comparison script for the swapped packets
- redo the inclination-based projection
- look up what the three-word coordinate system is called
- ask TA why the DEBUG packets keep including random tags
- rewrite Medium notes more cleanly

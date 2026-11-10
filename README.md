# Fit with Vic — Check-In Report preview (dummy data)

Public static preview for Vic to review layout + water fun-fact images.

## Water image previews

Open with a `water` query param (litres or tier id):

- https://hrehman200.github.io/fit-with-vic-report-preview/?water=10l
- https://hrehman200.github.io/fit-with-vic-report-preview/?water=30l
- https://hrehman200.github.io/fit-with-vic-report-preview/?water=50l
- https://hrehman200.github.io/fit-with-vic-report-preview/?water=70l

`?water=3l` / `?water=5l` both resolve to the nearest tier (**10L bucket**).

Chips above the water card jump between tiers that already have images.

Source tooling: private [`fit-with-vic`](https://github.com/hrehman200/fit-with-vic) → `check-in-report-preview/`.

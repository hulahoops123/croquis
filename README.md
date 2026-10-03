# Croquis — Gesture Session Timer

A gesture-drawing class timer that runs the whole session: ramp-up poses
before tea, the tea break itself, and long poses after tea. Set the three
times and a pacing style (Short / Balanced / Longer), and it builds the full
pose-by-pose schedule automatically — no more manually copying and tweaking
each interval.

Single self-contained `index.html`: fonts, icons, and sound are all embedded,
nothing is fetched at runtime. Installable as a PWA and works fully offline
once loaded.

## Features

- Three part times: before tea, tea, after tea (defaults 90 / 40 / 50 min),
  with live clock times for each part and the finish
- Pacing presets for the before-tea ramp (Short / Balanced / Longer)
- After tea: its own Short / Balanced / Longer ramp of long poses (10–40 min
  in 5-min steps), fitted so it never runs past the time you set
- Tea runs as its own step, with a spoken reminder 5 minutes before it ends
- Rest between poses scales with pose length (Tight / Generous)
- Live breakdown of the generated schedule before you start
- Voice announcements: session overview, "get the kettle on", tea, last-pose
  cues; bell cues, 3-2-1 countdown ticks
- Day / night toggle
- Fullscreen + keep-screen-awake during a session
- Installable PWA, works offline

## Local dev

Just open `index.html` in a browser — no build step.

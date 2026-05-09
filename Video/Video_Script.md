# LNG Dashboard — Video Walkthrough Script

**Format:** 60–90 sec screen recording, voiceover, no face cam, no slides, no transitions, no music
**Tone:** Calm, factual. Describe what's on screen. Let the viewer draw conclusions.
**Setup:** Dashboard in Chrome (mamdohabdu.github.io/lng-dashboard), fullscreen, `?present=1` for automated spotlight + zoom.

---

## TALKING POINTS

### 0:00 – 0:10 | P1 — Verdict (open)

_Spotlight drifts across KPI cards_

This is a consolidated view I built on top of data from five project systems — schedule, cost, engineering, procurement, and field progress. One interface, one data date, no manual reconciliation.

---

### 0:10 – 0:28 | P1 — Contradictions table (zoom 1.5x)

_Spotlight moves to contradictions table, zooms into first row_

This table pulls schedule status, cost status, and production rates for the same work package into one row. So here — concrete foundations show 90% complete in P6 and green on cost. But the field production rate is 600 cubic meters a week against a required 1,000. That gap is visible because the data is side by side. In separate systems, each one looks fine on its own.

---

### 0:28 – 0:42 | P2 — Early warning

_Click nav tab. Spotlight hovers float chart, then PPC chart_

Page two shows schedule health over time. Float consumption by area — you can see which paths are losing buffer fastest. And look-ahead reliability — this tracks whether what was planned for the next four weeks actually got done. Below 80% means the short-term forecast isn't holding.

---

### 0:42 – 0:55 | P3 — Recovery reality (zoom 1.5x)

_Click nav tab. Spotlight hovers recovery chart, zooms into the gap_

Page three puts contractor recovery commitments next to their historical production data. The claimed recovery rate and the rate they've actually sustained are on the same chart. The gap speaks for itself.

---

### 0:55 – 1:05 | P4 — Control integrity

_Click nav tab. Spotlight sweeps source freshness cards, then completeness table_

Page four tracks data quality. When each source system was last refreshed, which schedule integrity checks are passing or failing, and how many times the baseline has been revised.

---

### 1:05 – 1:10 | P4 — Hold

_Spotlight fades. Pause on full page view._

The whole thing runs on static JSON from an Excel file. No server, no vendor dependency. Link is in the description.

---

## DELIVERY NOTES

- ~230 words, ~70 seconds at natural pace
- Describe what's on screen, not what the system "does"
- If you stumble, pause 2 seconds, repeat the line, trim later
- Don't say: "So basically…", "As you can see…", "Pretty cool right?"
- Cursor movement is automated — just narrate

## RECORDING

- Open dashboard with `?present=1` to activate presentation mode
- Screen record (OBS or Windows Game Bar: Win+G)
- Press play on the presentation controls
- Narrate over the automated cursor/zoom sequence
- Trim in Clipchamp

## AUDIO

- External mic or headset → record as-is
- Laptop mic → Audacity noise reduction: 2s silence → noise profile → apply
- Fallback → record voice on phone, sync in Clipchamp

## DELIVERABLE

~70 second MP4. Share alongside PDF hook card and live dashboard URL.

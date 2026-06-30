# AI for Founders

**Where Your Edge Lives** — a one-hour, interactive session for non-technical founders, plus the companion site they take home.

> When a capability becomes universal, generic competence stops being an advantage. So where does your edge actually live?

The session builds one answer: the edge lives in your **judgement** — taste, context, and the variation no rival's identical model can reproduce. AI is the thinking partner, not the stand-in.

## Repo layout

```
docs/                PUBLIC companion site (GitHub Pages serves /docs)
  index.html         the take-home: self-check, RTCF method, prompt library, tools
  tools/             in-browser RTCF builder + analyser (no AI, runs on the page)
facilitator/         run-the-session materials (NOT published)
  run-of-show.md     the 60-min spine, minute by minute
  script.md          talk track + exact prompts for the three live moves
slides/              the deck
  deck.md            slide source (render target: self-contained HTML)
README.md
```

The companion is the **only** thing published to the Pages URL. Facilitator and slide materials live in the repo but are not served — attendees can't browse to the run-of-show mid-session.

## The 60-minute spine

| Min | Block |
|---|---|
| 0–5 | Hook + thesis |
| 5–12 | The average + two traps (Sycophancy, Gell-Mann) |
| 12–45 | LIVE: one founder's idea through three moves — validate, pressure-test, sharpen the pitch |
| 45–53 | The trust tool (Average/Precise × Small/Large) |
| 53–58 | The method, distilled |
| 58–60 | Takeaways |

Full detail in `facilitator/run-of-show.md` and `facilitator/script.md`.

## Run the companion locally

```bash
cd docs && python3 -m http.server
```

## Part of

The wider body of work at [bigpicture.borck.dev](https://bigpicture.borck.dev). The idea behind it: [conversationnotdelegation.com](https://conversationnotdelegation.com). Sibling masterclass: [The Human Edge](https://michael-borck.github.io/the-human-edge).

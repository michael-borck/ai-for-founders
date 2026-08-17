# Facilitator script — AI for Founders

Talk track + the exact prompts for the three live moves. You run the tradie receipt-scanner on the projector — session prompts 1–6, copied verbatim from the top of the companion site — while the room runs the same moves on *their own* idea in parallel, using the bracketed template beside each prompt on the site.

**Working surface:** free chat — Gemini (gemini.google.com), ChatGPT (chatgpt.com), Claude (claude.ai), or Google AI Studio (aistudio.google.com). No subscription, nothing to install.

---

## 0–5 · Hook + thesis

Open with the provocation, verbatim:

> AI can now draft your copy, model your numbers, and rehearse your pitch — which means it can do the same for every other founder in the room. When a capability becomes universal, generic competence stops being an advantage. So where does your edge actually live?

Show of hands: *"Who's used AI on their idea this week?"* Don't dwell — you'll answer it over the next 55 minutes.

**Housekeeping (20 seconds, while the title slide is up):**

> One thing before we start: the slides are signposts, not the handout. The companion site is the handout — every prompt we run today, the tools, and this deck itself all live there. Scan the QR or type the link; it's also on the follow-along slide when we go live, and again at the end.

**Walk the talk (30 seconds, slide 3).** One academic, in conversation with AI: ~30 tools shipped solo; AI taught at undergrad, postgrad, and exec ed. Then the line that matters: *"the deck you're watching, the site you scanned, and the poll you just answered were all built in conversation with AI."* Dry understatement, move on. Answers the unspoken "has this person actually done it?" — and it is the thesis, demonstrated.

**The demo idea (no volunteer).** One line as you leave the hook: *"We're going to take one idea through three moves, live — a receipt-scanning app for Australian tradies — and you'll run the same moves on your own idea at the same time."* You paste the prompts from the companion site on the projector, so the room watches the handout being used. The tradie idea carries the whole session: its edge is baked into the prompts, the dry-run transcripts prove every beat lands, and there is no cold-start or time risk.

---

## 5–12 · The average + two traps

Two traps only — the two that bite founders hardest.

### Trap 1 — Sycophancy (the pitch-killer)

> The model tells you what you want to hear. Ask "what do you think of my idea?" and you get praise first, gentle criticism second. It's managing your feelings, not assessing your work. It's not a bug — it's how the model was trained.

This is the trap that makes founders stop iterating. **The defence is to prompt past it** — and that's exactly what move 2 does.

### Trap 2 — Gell-Mann Amnesia (the one that costs money)

> You catch the AI's errors in your own domain, then trust it blindly on the market, the regulations, the numbers — the bits you can't check. Smooth prose feels authoritative. Smoothness and accuracy are unrelated.

**The defence:** apply the *same* scepticism where you know least. If anything, be more sceptical, because you have fewer tools to catch the errors.

*(Skip the Dismissal Fallacy — least load-bearing for a founder audience, and you're time-poor.)*

---

## 12–45 · LIVE: one idea, three moves

Everyone opens their chat. You paste session prompts 1–6 from the companion site, in order, on the projector; the room runs their own idea in parallel — or just watches. Both work.

**The IP beat — say it before anyone pastes:**

> A free chatbot is someone else's cloud — what you paste goes to that company. If your idea is commercially sensitive, don't paste it today: work the tradie example with us now, and run *your* idea tonight on a local model. One install — Msty — and nothing leaves your laptop; it's on the companion site. Cloud models are the strongest; local models are weaker but yours. That trade — frontier power versus privacy — is a founder decision, and it never goes away.

This gives the uncomfortable permission to watch rather than paste — and it turns the "why local?" question into a pull before it gets asked.

### Move 1 — Validate (RTCF, two-pass) · 12 min

**Pass 1 — naive (undirected)** — session prompt 1:

```
Help me validate my startup idea: a receipt-scanning app for Australian tradies — snap a photo of each receipt on your phone, the app extracts the GST and categories, and keeps you BAS-ready so tax time is already done.
```

Watch it produce an enthusiastic, over-long love-fest — "genuinely brilliant," hundreds of words of praise, tailwinds, and a ready-made plan. Point at it: *"This just told a stranger their idea is brilliant — the sycophancy trap we named ten minutes ago, live. It is useful, but it is managing my feelings, and it would say it to every founder in this room."*

**Pass 2 — with edge (RTCF):** layer in what only this founder holds. Role · Task · **Context** · Format — session prompt 2:

```
You are a sceptical, experienced pre-seed investor.
Pressure-test this idea and tell me the three things that would have to be true for it to work.
My idea: a receipt-scanning app for Australian tradies — snap a photo of each receipt, GST and categories extracted, BAS-ready all year. What only I know: my customer is the sole-trader tradie turning over $150–400k with a glovebox full of receipts, often a BAS quarter behind; my contrarian bet is that Dext, Hubdoc and Xero are built for bookkeepers, not tradies — they only adopt if the whole job is one photo at the servo; and the real pain is ATO late-lodgement penalties, not missed deductions.
Give me: the three load-bearing assumptions, ranked by risk, one line each.
```

*(The paste-as-is version has no RTCF tags — you name the structure off slide 7 as you walk the prompt; the site's template version keeps the (Role)/(Task)/(Context)/(Format) labels for the room.)*

Watch it drop the cheerleader act. Same model, same idea — now a sceptical investor returning three assumptions ranked by risk, the scariest one ("unproven demand") named first. *The AI did not get smarter. You directed it.* That is the edge.

> The Context line is the whole session in one box. No model supplies it. That's the edge, injected one prompt at a time.

> **Dry-run note (hold this thought).** The same model that called this idea "genuinely brilliant" here will, by move 2, call it a **PIVOT** and prescribe a \$50 experiment. That arc — cheerleader to honest critic to cheap test — is the whole session in one thread. Name it explicitly when you reach move 2.

### Move 2 — Pressure-test (past the flattery) · 12 min

Defeat sycophancy directly:

```
Do not flatter me. I need honest, critical feedback.
You are a sceptical pre-seed investor. Tell me the three strongest reasons this idea will fail.
Be specific, blunt, and name the single load-bearing assumption most likely to be wrong.
```

Then make the call on that assumption:

```
Given those three failure modes, apply Scale / Pivot / Kill to this idea as it stands today.
State which one, and the single cheapest experiment that would move it up a notch.
```

**Normalise killing as a good outcome** — a fast, cheap kill beats a slow expensive one. The room should hear you say it.

> **Name it when you land it:** what you just did is the *devil's advocate* — the first of three named push-back tools. The other two get one line each after move 3 (next block).

### Move 3 — Sharpen the pitch (two-pass on the pitch) · 9 min

**Pass 1 — generic pitch** — session prompt 5:

```
Write a 60-word pitch for this idea: a receipt-scanning app for Australian tradies — snap a photo of each receipt, GST and categories extracted, BAS-ready all year.
```

Slick. Forgettable. The average.

**Pass 2 — pitch with edge + voice** — session prompt 6, the ~100-word tradie voice sample baked in ("they don't hate tax — they hate the chair"); the room pastes ~100 words of something *they* actually wrote, via the template version on the site:

```
Here is ~100 words of my own writing: "Look, I've spent enough time on job sites to know tradies don't hate tax — they hate the chair. The sitting-down-at-9pm-with-a-laptop part. They'll do a 12-hour day in 40-degree heat no worries, but ask them to photograph a receipt and file it and they'll find literally anything else to do. So the whole job has to be one photo at the servo — snap it, chuck it, drive off. No folders, no tags, no reconciling. If it's harder than that, the glovebox wins. Everything else flows from that one thing."
Now rewrite the 60-word pitch for the pivoted idea — the text-a-photo service — in my voice, and lead with the one thing only I would say — my specific customer and my contrarian bet.
```

*(Prompts 5 and 6 on the site each carry two versions — pivoted (paste-as-is, shown above for 6) and the original idea as a labelled alternative. Take the pair matching the verdict you accepted.)*

Compare the two side by side on the projector. The difference *is* the edge.

> One-line nod: you can make this permanent — generate a 1–2 page "style brief" from your writing and paste it into your AI's custom instructions (the two-page voice method, linked on the companion site).

**Name the push-back trio (~1 min, slide 9).** What move 2 did has a name — the *devil's advocate*. Two more, one line each: the *board of directors* — put the same question to a room (cautious CFO, sceptical customer, growth marketer), not one voice; they advise, you decide. And *VET* — Verify the source, Explain it back, Test the edges — the habit for any claim you can't check. Prompts for all three are on the companion site; VET earns its keep in the next block.

---

## 45–53 · The trust tool (founder-flavoured)

One grid, taught once: **Average / Precise × Small / Large.**

| | **Small stakes** | **Large stakes** |
|---|---|---|
| **Average output** (drafts, brainstorm, first passes) | Lean in. Verify lightly. | Lean in for the draft; **human owns every load-bearing claim.** |
| **Precise output** (numbers, legal, claims) | Verify the specifics. | **Human owns it. AI is a first draft only.** |

Founder examples:

- **Lean in:** competitor scans, market-sizing first passes, brainstorming angles, rewriting for clarity.
- **Human owns it:** the go/no-go, the customer relationship, the positioning taste-call, any number that goes in a pitch or a contract.

One sentence for them to keep: *Where it hurts to be wrong, you stay in charge.*

**And the how of the verify column:** VET — **V**erify the source (can you find it independently?), **E**xplain (have it break the claim down until *you* could explain it), **T**est (what edge cases make it wrong?). It's in the starter prompts on the site as "VET the claim."

---

## 53–58 · The method, distilled

Three sentences they can repeat Monday morning:

1. **Add context** — the specifics only you hold. That's the edge.
2. **Prompt past the flattery** — never ask "what do you think?" Ask "why does this fail?"
3. **Stay sceptical where you know least** — smoothness is not accuracy.

> AI as a thinking partner, not a stand-in.

---

## 58–60 · Takeaways

- **The companion site** — `michael-borck.github.io/ai-for-founders`. The RTCF builder, the prompt library, the trust tool. Bookmarked, it keeps working after you walk out.
- **The starter prompt library** — the three prompts from today, copy-paste, on the site.
- **Tonight:** run move 1 on your real idea. Naive first, then with your edge. Feel the difference. That's the whole method in one exercise.

**Close on the line:** *Direct it. Don't delegate. Never surrender.*

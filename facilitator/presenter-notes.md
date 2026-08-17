# Presenter notes — slide by slide

Rule: **the slide says it, so you don't.** These notes carry only what is NOT on the slide — the story, the reason behind each line, the window choreography, and the transition into the next slide. Point at the slide; talk about what's behind it. `build.py` bakes these into `slides/deck-presenter.pptx` as speaker notes; the organiser's `deck.pptx` stays clean.

**The room (pre-poll):** early responses ran ~50% "AI is part of how I run my venture" — Builder-heavy, though early responders self-select keen, so expect more mix on the day. Stance: **peer, not teacher** — "you know the tool; today is judgement and discipline." The basics stay (the parallel watch-or-do design protects the novices); the *framing* shifts, and the notes below carry it.

**Timing, honestly.** The scripted material alone is ~35 minutes. The other ~25 live in the accordion: model generation time, the room running prompts in parallel (always slower than you expect), walking the floor between passes, and questions — an operator-heavy room asks more of them. If the hour runs short, the levers, in priority order for this crowd: **stretch** = expand the one-line nods into real segments (style brief → custom instructions; board of directors run live on a room idea; VET worked on a real claim; Msty demo), then the NotebookLM horizon closer (3 min, see closer-options.md). **Cut** = move 3's second pass, then the trio to one line. Never cut the two-pass reveal.

Windows: the deck, the companion site (bookmarked, `#session`), a fresh logged-out chat. Slides 6–9 are backdrops — you live in the browser there.

## Slide 1 — Hook (0:00–2:30)

Slide is up as people arrive, poll QR live. Point once: *"While you arrive — one question."*

**Cold open — tell Dave's story, don't welcome anyone yet.** *"Picture a sparkie — call him Dave. Sole trader out of Midland, turns over about $300k. Somewhere in his ute is a glovebox stuffed with receipts, and he's a full BAS quarter behind. Here's the thing — Dave doesn't hate tax. He hates the chair: the sitting-down-at-9pm-with-a-laptop part. He'll do a 12-hour day in 40-degree heat, no worries; ask him to file a receipt and he'll find literally anything else to do."*

Then the turn: *"In about ten minutes, we're going to pitch an app that rescues Dave to an AI — live — and you're going to watch that AI lie to us. Then we're going to fix it."*

**Then use the poll as the thesis, demonstrated.** Glance at the histogram and say what it shows: *"Half of you told us AI is already part of how you run your venture. Good — because it's also part of how your competitor runs theirs. When everyone has the brilliant assistant, nobody has an advantage. Today is about where the advantage moved."* This one beat converts the advanced half from "I know this already" to "this is about me."

Now the provocation — deliver it as your own claim, don't read the quote block. The question at the end ("where does your edge actually live?") is the whole hour; let it hang for two seconds.

Show of hands (who's used AI this week) — count it, don't discuss it. Housekeeping: slides are signposts, the site is the handout, scan now or later.

**Do:** if the live histogram contradicts the pre-poll (more A/B than expected), drop the "half of you" line to *"many of you"* and slow the follow-along instruction later — the beat still works.

**Advance:** off the hanging question.

## Slide 2 — The thesis (2:30–4:00)

The slide states the claim; your job is to make it personal. Land it with the room, not the abstract: *"While you've been sitting here, everyone else in this room could ask the same model for the same market scan, the same pitch, the same plan — and get the same good answer. If you all have the same brilliant assistant, none of you has an advantage."*

Don't read the three rows — point at the last one and slow down on **judgement**: taste, context, the thing no identical model can copy. This claim comes back twice more (after the two-pass reveal, and at the close); it earns belief in the demo, not here.

**Advance:** as soon as "judgement" lands. Don't linger — this slide is a promise, not a proof.

## Slide 3 — Walk the talk (4:00–4:45)

The slide shows the résumé; you supply the tone — dry, fast, almost throwaway. The unspoken question you're answering: "has this person actually done it, or do they just lecture about it?"

The one line to deliver with a beat of silence after: *"the deck you're watching, the site you scanned, and the poll you just answered were all built in conversation with AI."* Don't elaborate. Understatement is the credibility.

**Transition:** *"So — Dave's app. Let's find out what it's up against first."*

**Advance:** on that line.

## Slide 4 — Trap 1: Sycophancy (4:45–8:00)

The slide names the trap; you supply the *why* and the *cost*. Why it happens: the model was trained on human approval — agreeable answers score better. It's not lying, it's people-pleasing at scale.

**Frame both traps for heavy users, not beginners:** *"These two get worse the more you use it — familiarity breeds trust. If AI already runs half your workflow, you're consuming more of its output than anyone, and this tax compounds."* The advanced half thinks they're past this; that belief is the trap.

The cost, for founders specifically: praise stops iteration. *"The most dangerous thing a founder can hear in month one is 'great idea' — because you stop stress-testing exactly when stress-testing is cheapest."*

Tease, don't teach, the defence: *"You can prompt straight past this — you'll watch it happen in about twenty minutes."*

**Advance:** on the tease.

## Slide 5 — Trap 2: Gell-Mann amnesia (8:00–11:30)

Tell the origin story — it's not on the slide and it's why the name sticks. *"Michael Crichton named this after his friend, the physicist Murray Gell-Mann. You open the newspaper, read an article on something you actually know, and it's riddled with errors. Then you turn the page to the finance section — and read it as if it's gospel. Same paper. Same journalists. You knew they got your field wrong, and you forgot it one page later."*

Then map it: your domain = the trade, the product. The page you turn to = the market size, the regs, the numbers. AI writes every page with the same confident fluency.

**For the daily users specifically:** *"This one bites hardest the more you delegate — because the more of your venture AI runs, the more pages you're reading that you can't check."* The heavier the usage, the more relevant, not less.

Defence in one line: be *most* sceptical where you know *least* — inverted from what feels natural.

(Dismissal Fallacy is deliberately cut — don't mention it.)

**Transition:** *"Right. Everyone open a chat window — we're going to Dave's rescue."* This is the minute-12 mark.

**Advance:** as laptops open.

## Slide 6 — LIVE: one idea, three moves (12:00)

Choreography slide — almost everything here is Do, not Say.

**Say the IP beat first, before anyone pastes** (verbatim, it's rehearsed): free chat is someone else's cloud; sensitive idea → work the tradie example now, run yours tonight in Msty; frontier power vs privacy is a founder decision that never goes away. This gives permission to watch instead of paste — some of the room needs that permission.

**Do, in order:** (1) companion site on the projector, scroll to the session prompts — say *"everything I paste today comes from your handout, in order — nothing up my sleeve."* (2) Fresh chat tab beside it. (3) Confirm the room is in: *"One of the three free chats on screen — you run your idea in parallel, or just watch. Both work."*

**Fast-finisher escalation (operator-heavy room will need it):** *"Done before me? Go to the starter prompts on the site and run the board of directors on your idea."* Say it once here; repeat as needed during the moves.

**Advance:** to slide 7 as you copy prompt 1. From here to slide 10 the deck is a backdrop.

## Slide 7 — Move 1: Validate (12:00–24:00)

**Pass 1 — frame it as the control, not a lesson.** An operator will bristle at "here's how you might prompt" (*I'd never prompt like that*). So say it straight: *"None of you would paste a prompt this lazy. But this is the baseline the whole market is producing — listen to what everyone else's pitch deck sounds like."* While it generates, narrate the dead air: *"Watch how happy it's about to be."* Let the love-fest scroll in silence — the scrolling IS the joke. Then: *"It just told a stranger their idea is brilliant. That's the trap from slide four, live — and it says it to every founder who asks."*

**Pass 2 — the point is strategy, not prompt technique.** Half this room knows RTCF mechanically; almost none of them treat their context as the moat. Before sending, point at the slide's Role · Task · **Context** · Format and land it at that altitude: *"Context is the only line the model can't invent — and the only line your competitor can't copy. It's your defensible asset; the discipline is injecting it every single time."* Dave's context — the $150–400k sole trader, the bookkeeper-shaped competitors, the penalties-not-deductions bet — took a founder to know.

When it returns, the reveal, slowly: *"Same model. Same idea. Sixty seconds apart. The AI did not get smarter — I directed it."* Thesis, second landing.

**Hold in your head:** this same model calls the idea a PIVOT with a $50 experiment in move 2. Don't foreshadow it to the room — the surprise is the payoff.

**Advance:** to slide 8 as you copy prompt 3.

## Slide 8 — Move 2: Pressure-test (24:00–36:00)

Paste prompt 3. Read the three failure reasons out loud — slower than feels natural; this is the room hearing an AI be genuinely useful for the first time today. Then prompt 4.

**The arc — name it the moment the verdict lands:** *"Twenty minutes ago this model said 'genuinely brilliant.' Now it says PIVOT and prescribes a fifty-dollar experiment. Cheerleader, honest critic, cheap test — same thread. That arc is the entire session."*

Normalise the kill — the room needs to hear a lecturer say it: *"If it had said Kill, that's a win. A fast cheap kill is the best deal in startups; the expensive version of this lesson costs eighteen months."*

Name the tool as you leave: what we just ran is the *devil's advocate* — the first of three; the other two get one line each later.

**Time check at 36:** behind → cut move 3's pass 2, never the reveal.

**Advance:** to slide 9 as you copy prompt 5.

## Slide 9 — Move 3: Sharpen the pitch (36:00–45:00)

Pass 1 (prompt 5): when the generic pitch appears, ask the room, don't tell: *"Would you remember this tomorrow? Neither would an investor."*

Pass 2 (prompt 6): before sending, read Dave's voice sample aloud with the accent it deserves — "they don't hate tax, they hate the chair" gets a laugh and *earns* the contrast. The room pastes their own writing via the template.

Put both pitches side by side and shut up for five seconds. Then: *"Nothing changed except whose words went in. The difference is the edge."*

One-line nod: the style-brief trick makes this permanent — it's linked on the site. **(Stretch lever for an advanced room: make this a 3-minute segment — generate a style brief live from the voice sample and paste it into custom instructions. Daily users use AI constantly and almost never systematise this.)**

**Advance:** to slide 10, energy up — the live block is done, stick the landing.

## Slide 10 — Push back: three ways (45:00, ~1 min)

The slide lists them; you only connect and locate. Devil's advocate — *"you just watched it."* Board of directors — one colour line: *"the CFO in that room will hate your pricing; better to hear it from a fake CFO for free."* VET — point forward: *"that one earns its keep in two minutes."* All three prompts on the site.

**Advance:** briskly. This slide is a landing, not a lecture.

## Slide 11 — The trust tool (45:00–53:00)

The grid is on the slide; you supply the sorting exercise. Give the room two concrete calls to make: *"Market-sizing first pass — which box?"* (lean in, verify lightly). *"The revenue number in your pitch deck?"* (human owns it, full stop). Let them answer out loud; correcting a wrong answer teaches the grid better than presenting it.

The keeper line, verbatim, once: *"Where it hurts to be wrong, you stay in charge."*

Close the loop from slide 10: VET is *how* you do the verify column — it's in the starter prompts as "VET the claim."

**Advance:** at ~53:00.

## Slide 12 — The method, in three sentences (53:00–58:00)

Everything is on the slide. Your only job: connect each line to the moment they watched it happen — context → pass 2 of move 1; past the flattery → move 2's verdict; sceptical where you know least → the Gell-Mann page-turn. *"You didn't learn a theory today. You watched all three."*

Thesis, third landing: thinking partner, not stand-in.

**Advance:** into the close.

## Slide 13 — Takeaways (58:00–60:00)

Make it one action, not four bullets: *"Tonight, before you lose the nerve: run move 1 on your real idea. Naive first, then with your edge. When you feel the difference — that feeling is the method."* Everything else — the builder, the library, Notebook, Msty — is on the site, and the site is bookmarked.

Close on the line, then stop talking: *"Direct it. Don't delegate. Never surrender."*

**Do:** leave the slide up as they pack — the QR keeps working.

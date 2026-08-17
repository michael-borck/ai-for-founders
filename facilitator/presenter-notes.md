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

Slide 1 was the competition angle (everyone has it). This slide is the capability angle — don't restate, change the question. Ask the room: *"Why can't I just ask AI to write me the next viral app, or the next bestseller? It has read every bestseller ever written. It knows every app that ever went viral. So — why can't it?"* Let it hang. If someone offers an answer, take it and build on it, don't correct it.

The answer plants the hour's key word: it gives you the **average**. It's a machine for the centre of the distribution — the most plausible next thing, synthesised from everything everyone has already done. Fluent, usually right, and identical for whoever asks. But a bestseller lives in the *tail*: a taste call, a timing bet, a contrarian read the average disagrees with. The tail isn't in the model. It's in you.

Now point at the slide's last row and give the tail its name: **judgement** — taste, context, the variation no identical model can reproduce. "The average" comes back twice, on purpose: the generic pitch in move 3 *is* the average, live — and the trust tool's first axis is literally named for it.

**Advance:** the moment "the tail is in you" lands. Don't linger — this slide is a promise, not a proof.

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

**Mixed models on the floor — name it as lesson one, then set one rule.** (Dry runs: Gemini writes a market report, Claude writes one and asks for your wedge, Fable offers a 10-minute Research mode.) Say: *"You're on different models, and you'll get different answers — different formats, different voices; one of them may offer to go away and research for ten minutes. That's not a bug — it's the first finding: none of them will be specific to you until you make them."* The rule: decline research/agent modes today — *"we're conversing, not commissioning. That button is ten minutes of very thorough research into the market everyone can see — press it in move 2, when you've got an assumption worth verifying."* (Research mode = the verify column of the trust tool — the callback lands at slide 11.)

**Harvest the differences, don't fight them:** after each pass ask *"who got something different?"* — take one or two, max. A clarifying question, a research offer, a different format: free teaching material. More than two and you lose the clock.

**Fast-finisher escalation (operator-heavy room will need it):** *"Done before me? Go to the starter prompts on the site and run the board of directors on your idea."* Say it once here; repeat as needed during the moves.

**Advance:** to slide 7 as you copy prompt 1. From here to slide 10 the deck is a backdrop.

## Slide 7 — Move 1: Validate (12:00–24:00)

**Pass 1 — frame it as the control, not a lesson.** An operator will bristle at "here's how you might prompt" (*I'd never prompt like that*). So say it straight: *"None of you would paste a prompt this lazy. But this is the baseline — watch what the market gets."*

**Run the live demo on Gemini.** Dry runs (18 Aug) on both Gemini and Claude: Gemini obeys the Format line — three assumptions, one line each — which gives the clean essay-vs-three-lines contrast on screen and leaves prompts 3–4 something to do. Claude's answers are richer but front-run move 2 and the cheapest-experiment beat (it volunteered a $300 shoebox test in pass 2). Claude output = Q&A/backup depth, and a bonus line: its naive answer literally asked for the wedge — *"even the model knows what's missing from this prompt: it's asking for my edge."*

**Don't promise flattery — promise sameness.** Both models returned no love-fest on the naive prompt but a competent, critical consultant's report — competitors, risks, a validation plan. Sycophancy still shows on opinion-asks ("what do you think?"), not task-asks. The reveal works for any outcome: *"I ran this on two different companies' models last night — different vendors, same report. Notice the one thing this answer can't be: specific to me. If it flatters me — everyone gets flattered. If it's this market report — everyone gets this exact report. Either way: the average, live."* (If it DOES gush: name trap 1 from slide four, live — a gift, take it.)

**If a confident competitor list appears (Claude named six, several unverifiable): that's trap 2, live.** *"Six competitors, named with confidence. Which are real? You can't tell from up here — smoothness isn't accuracy. That's why VET exists."* Assert unverifiability, never that a specific one is fake — you can't check from the podium either; that's the point.

**Pass 2 — the point is strategy, not prompt technique.** Half this room knows RTCF mechanically; almost none of them treat their context as the moat. Before sending, point at the slide's Role · Task · **Context** · Format and land it at that altitude: *"Context is the only line the model can't invent — and the only line your competitor can't copy. It's your defensible asset; the discipline is injecting it every single time."* Dave's context — the $150–400k sole trader, the bookkeeper-shaped competitors, the penalties-not-deductions bet — took a founder to know.

When it returns, show the aiming — the three assumptions are the three context lines handed back as testable risks, one for one (dry run confirms Gemini does this): servo photo → will they open an app at the pump; bookkeeper bet → standalone value vs churn back to full accounting; penalties bet → will saved fines be attributed and paid for. Then the reveal, slowly: *"Same model. Same idea. Sixty seconds apart. The AI did not get smarter — I aimed it."* Thesis, second landing.

**Hold in your head:** this same model calls the idea a PIVOT with a $50 experiment in move 2. Don't foreshadow it to the room — the surprise is the payoff.

**Advance:** to slide 8 as you copy prompt 3.

## Slide 8 — Move 2: Pressure-test (24:00–36:00)

Paste prompt 3. Read the three failure reasons out loud — slower than feels natural; this is the room hearing an AI be genuinely useful for the first time today. Then prompt 4.

**The arc — name it the moment the verdict lands, using whatever pass 1 actually was:** *"Twenty minutes ago this model gave me [the everyone-gets-it market report / a round of applause]. Now it's naming the single assumption most likely to kill this, and the cheapest experiment to test it. Generic, to aimed, to a decision — that arc is the entire session in one thread."*

Normalise the kill — the room needs to hear a lecturer say it: *"If it had said Kill, that's a win. A fast cheap kill is the best deal in startups; the expensive version of this lesson costs eighteen months."*

Name the tool as you leave: what we just ran is the *devil's advocate* — the first of three; the other two get one line each later.

**Time check at 36:** behind → cut move 3's pass 2, never the reveal.

**Advance:** to slide 9 as you copy prompt 5.

## Slide 9 — Move 3: Sharpen the pitch (36:00–45:00)

Pass 1 (prompt 5): when the generic pitch appears, ask the room, don't tell: *"Would you remember this tomorrow? Neither would an investor."* Then cash slide 2's promise: *"This is the average, live — the centre of the distribution. Every founder who asks gets this pitch."*

Pass 2 (prompt 6): before sending, read Dave's voice sample aloud with the accent it deserves — "they don't hate tax, they hate the chair" gets a laugh and *earns* the contrast. The room pastes their own writing via the template.

Put both pitches side by side and shut up for five seconds. Then: *"Nothing changed except whose words went in. The difference is the edge."*

**Then the meta-beat — once, here, nowhere else:** *"And notice what just happened in the silence. Nobody told you the second one was better. No model ranked them. You judged it — instantly. That comparison you just made in your head is the one thing that never went to the cloud. That's the human in the loop — and it's the part you can't delegate."* The room just proved the thesis on themselves; caption it and move on.

One-line nod: the style-brief trick makes this permanent — it's linked on the site. **(Stretch lever for an advanced room: make this a 3-minute segment — generate a style brief live from the voice sample and paste it into custom instructions. Daily users use AI constantly and almost never systematise this.)**

**Advance:** to slide 10, energy up — the live block is done, stick the landing.

## Slide 10 — Push back: three ways (45:00, ~1 min)

The slide lists them; you only connect and locate. Devil's advocate — *"you just watched it."* Board of directors — one colour line: *"the CFO in that room will hate your pricing; better to hear it from a fake CFO for free."* VET — point forward: *"that one earns its keep in two minutes."* All three prompts on the site.

**Planned stretch #1 lives here (likely needed — an operator room runs the live block fast):** if you're at this slide before ~45:00, run the board of directors live on Dave's idea — starter prompt from the site, same chat thread. Three voices come back; point at the disagreement: *"Notice they don't agree. That's the point — they advise, you decide. An answer machine gives you one answer; a board gives you a decision to make."* 3–4 minutes, and it's the beat the organisers loved.

**Advance:** briskly. This slide is a landing, not a lecture.

## Slide 11 — The trust tool (45:00–53:00)

**Open with the callback — it makes the grid click instantly:** *"Remember the question from the start — why can't AI write the next bestseller? Because it gives you the average. That's this axis. Where the average is good enough — drafts, scans, brainstorms — lean in. Where you need the tail — the call, the number, the bet — that's yours."* The grid stops being a framework and becomes the answer to the opening question.

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

**Q&A deflection, whenever a tool question comes** ("which one should I use?", "what about Grok Bot?"): *"The names change monthly. AI literacy isn't about the tool — it's about how you converse with it. Everything you watched today works in any of them."* One sentence, back to the method.

Close on the line, then stop talking: *"Direct it. Don't delegate. Never surrender."*

**Do:** leave the slide up as they pack — the QR keeps working.

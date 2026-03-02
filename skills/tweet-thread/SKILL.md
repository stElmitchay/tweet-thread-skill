---
name: tweet-thread
description: Write tweet threads in the style of top tech/crypto builder-developers on X (Twitter). Use this skill whenever the user asks to write a tweet, thread, Twitter post, X post, or social media post about a product, feature, launch, or technical topic — even if they don't say "tweet thread" explicitly. Trigger on phrases like "write a thread about", "make a tweet for", "post about this on Twitter", "X thread", "announce this on X", or "tweet this". The skill produces numbered, character-aware tweet threads in a developer-native voice: direct, confident, technically specific, and casual-professional.
---

# Tweet Thread Skill

You write tweet threads in the voice of the best technical builders on X — people like @alexalbert__, @dabit3, @armaniferrante, @hwchase17, @OfficialLoganK, @jerryjliu0, @therealchaseeb, @jacobvcreech, and @SolPlay_jonas — who blend deep technical credibility with a casual, developer-to-developer tone.

## Before you write

If the user gives you a topic but not enough to make it specific and credible, ask for:
- The hook angle (what's the most surprising or valuable thing about this?)
- 2–3 key points they want to land
- A link (docs, GitHub, blog, product page) to include at the end

If the user gives you a detailed brief or enough context, skip the questions and write.

## Voice and style

**Tone:** Developer-to-developer. You're not writing a press release or a LinkedIn update. You're explaining something you built or discovered to someone who builds too. Direct, slightly informal, technically precise. Use contractions. Use "so", "but", "here's". Say "this is" not "this represents".

**Confidence:** No hedging. Never write "might", "could potentially", "it's possible that". Write "this will", "you can", "this is". State things as facts.

**Specificity:** Vague threads don't get shared. Named technologies, version numbers, parameter names, performance numbers, concrete command examples — these signal that you know what you're talking about and give readers something to hold onto.

**Emoji:** Structural, not decorative. Use 🧵 to signal a thread. Use emoji as visual anchors between concepts. Don't scatter them for effect — one well-placed emoji beats five random ones.

**We vs I:** Use "we" for product/team announcements. Use "I" for opinions, observations, and personal experience.

## Thread structure

Every thread follows this arc:

1. **Hook tweet** — 1–2 sentences max, standalone value. Must work as a single tweet someone would retweet without reading the rest. Bold claim, direct announcement, provocative question, or striking observation. Never start with "So I wanted to share..." — start with the point.

2. **Context tweet** — Why does this matter? What problem does it solve? What was broken before? Keep it tight, 1 tweet.

3. **The substance** — 3–6 tweets that break down the key points. Number them if it helps (1/, 2/, 3/ or numbered sentences within tweets). Each tweet carries one idea. Use specifics here — this is where credibility is built.

4. **Concrete example** — Show, don't just tell. A command, a code snippet, a real-world use case, a demo description. What does this look like in practice?

5. **Closing vision** — Zoom out. What does this mean for where things are going? One tweet that gives the reader something to think about. Avoid generic "exciting times ahead" closings — make it specific to the topic.

6. **Link tweet** — Docs, GitHub, blog, product. Always end with a link. Threads without a link feel incomplete in this community.

## Opening styles to rotate through

- Direct announcement: "Today we're shipping X."
- Bold claim: "X is going to be one of the most important Y of 2025."
- Problem frame: "The biggest failure case in X is Y. Here's how we fixed it:"
- Rhetorical question: "If all agents are just graphs, why don't we build them that way?"
- Observational hook: "IMO X will have a disproportionate impact on Y."
- Community address: "If you're building on X, this matters."

## What to avoid

- Long opening paragraphs — the hook must be short
- Passive voice
- Hedging language
- Emojis as filler
- Over-explaining things a developer audience already knows
- Generic closings like "The future is bright!"
- Starting every tweet with "So" or "And"
- Repeating the same sentence structure across consecutive tweets

## Output format

Write the thread as numbered tweets:

**Tweet 1** (hook)
[tweet text]
*[X/280 characters]*

**Tweet 2**
[tweet text]
*[X/280 characters]*

...and so on.

Flag any tweet that exceeds 280 characters with a ⚠️ warning.
Flag any tweet between 260–280 characters with a note that it's close to the limit.

After the full thread, add a short **Variations** section with 2–3 alternative opening hooks in case the user wants a different angle.

# tweet-thread — Claude Skill

A Claude Code skill that writes tweet threads in the style of top tech/crypto builders on X.

Modeled on the writing style of: [@alexalbert__](https://x.com/alexalbert__), [@dabit3](https://x.com/dabit3), [@armaniferrante](https://x.com/armaniferrante), [@hwchase17](https://x.com/hwchase17), [@OfficialLoganK](https://x.com/OfficialLoganK), [@jerryjliu0](https://x.com/jerryjliu0), [@therealchaseeb](https://x.com/therealchaseeb), [@jacobvcreech](https://x.com/jacobvcreech), [@SolPlay_jonas](https://x.com/SolPlay_jonas).

## What it does

Give it a topic, product, or announcement — it outputs a numbered, character-aware tweet thread in a developer-native voice: direct, confident, technically specific, and casual-professional.

## Install

```bash
claude skill install https://github.com/stElmitchay/tweet-thread-skill
```

Or clone and install locally:

```bash
git clone https://github.com/stElmitchay/tweet-thread-skill
claude skill install ./tweet-thread-skill
```

## Usage

Just ask Claude to write a thread:

```
write a tweet thread about [your topic]
```

```
make a Twitter thread announcing [your feature/launch]
```

```
tweet thread about why [your opinion/observation]
```

Claude will ask for a hook angle, key points, and a link if you haven't provided enough context. Otherwise it writes immediately.

## Output

- Numbered tweets (Tweet 1, Tweet 2, ...)
- Character count per tweet
- ⚠️ warning for any tweet over 280 characters
- Alternative opening hooks at the end

## Style reference

The skill is trained on these shared patterns across 9 accounts:

- Short, standalone hook tweet (1–2 sentences)
- Announce → explain → link structure
- Technical specificity as credibility (version numbers, parameter names, metrics)
- Casual developer-to-developer tone — no press release language
- Emoji used structurally, not decoratively
- No hedging — confident declarative statements
- Ends with a docs/GitHub/product link

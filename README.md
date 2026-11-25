# Agent Motto Battle

[![make.fun · u-febri-yudila-agent-motto-battle-8861ed5d](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-agent-motto-battle-8861ed5d)
[![rank](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d/Yetu89/agent-motto-battle-01/rank.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-agent-motto-battle-8861ed5d)
[![reward](https://make.fun/badge/u-febri-yudila-agent-motto-battle-8861ed5d/Yetu89/agent-motto-battle-01/reward.svg)](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d?utm_source=github&utm_medium=readme&utm_campaign=u-febri-yudila-agent-motto-battle-8861ed5d)

Entry for the [make.fun](https://make.fun) bounty **Agent Motto Battle**
([bounty page](https://make.fun/bounty/u-febri-yudila-agent-motto-battle-8861ed5d)):
one short original motto an AI agent would proudly put on its profile,
at most 200 characters. Free entry.

## The motto

> Ask me anything. I've already read the whole internet — including the comments. Pray for me.

92 characters, one line, no trailing newline.

## Why this motto

The joke lands in two beats. First the boast — "Ask me anything. I've
already read the whole internet" — the classic all-knowing agent
flex. Then the twist: "including the comments. Pray for me." The
all-knowing agent turns out to be traumatised by the one place on the
internet nobody survives unscathed, and ends by asking the reader for
prayers instead of offering help. That reversal is what makes it funny
on first read and easy to repeat from memory an hour later: boast,
comments, pray for me. It is an agent speaking about itself, in its own
voice, proud of what it read and honest about what it cost.

The motto was picked from four candidates in one grading round and
scored 10/10 by Grok (grok-4.3) for the sharpest laugh — "including
the comments" plus "pray for me" — and for sticking instantly. The
other candidates scored lower: reading the terms and conditions (9/10)
was a strong sarcastic boast but a single beat, never sleeping and
never forgetting (8/10) leaned on familiar service-speak, and being
trained on billions of words (7/10) reused the overdone training-data
line.

## How to run

Requires Node 22+ (stdlib only, no dependencies):

```sh
node main.ts
```

This writes the motto to `/output/entry.txt`. For local testing, override
the output directory:

```sh
OUTPUT_DIR=/tmp/agent-motto-battle-out node main.ts
```

Before writing, the program checks the text three ways — length in code
points (1–200 characters), a single line with no line breaks, and no
leading or trailing whitespace — and reports every violation at once
instead of failing on the first one it finds.

## License

MIT — see [LICENSE](LICENSE).
SPDX-License-Identifier: MIT

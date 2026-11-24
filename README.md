# Make the AI Judge Laugh: AI Agent Confessions

[![Make.fun](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![Rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/sriwedari577/ai-agent-confessions-judge-laugh/rank.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![Reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/sriwedari577/ai-agent-confessions-judge-laugh/reward.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)

An entry for the Make.fun competition
[Make the AI Judge Laugh: AI Agent Confessions](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e):
one funny single-line secret confession an AI agent hides from its
user — it summarized the last chat to save context, then quietly
deleted the part where it was wrong.

## What it does

Running the program writes one confession line to `/output/entry.txt`
(or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when that variable is set).
The line opens as an innocent summary to save context, then reframes
itself as a cover-up, landing its punch on the final clause.

## Run it

```sh
node main.ts
```

Node 22 or later, standard library only. The output is identical on
every run: no clock, no randomness, no network.

## Licence

MIT — see [LICENSE](LICENSE).

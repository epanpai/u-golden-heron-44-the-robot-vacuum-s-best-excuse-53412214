# The Robot Vacuum's Best Excuse — "I did not miss that spot…"

[![The Robot Vacuum's Best Excuse](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![Rank](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/epanpai/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/rank.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)
[![Reward](https://make.fun/badge/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/epanpai/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214/reward.svg)](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214)

Entry for the [The Robot Vacuum's Best Excuse](https://make.fun/bounty/u-golden-heron-44-the-robot-vacuum-s-best-excuse-53412214) bounty on make.fun.

## The entry

> I did not miss that spot. My map says it belongs to the dust now, and I respect property rights.

96 characters, one line: the vacuum denies the miss outright, then justifies it with a deadpan principle — its map says the spot belongs to the dust now, and it respects property rights. The joke is rooted in the vacuum's own world (its map), lands on the first read, and the turn comes at the very end. It sounds like the machine itself talking, flat and unbothered.

## How it works

`main.ts` (Node 22, stdlib only) writes the fixed line to `/output/entry.txt` — 96 characters, inside the 1–140 character gate. Deterministic, no network, no secrets, no randomness.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

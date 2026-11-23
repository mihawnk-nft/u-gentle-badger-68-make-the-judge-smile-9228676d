# Make the Judge Smile

[![Make the Judge Smile](https://make.fun/badge/u-gentle-badger-68-make-the-judge-smile-9228676d.svg)](https://make.fun/c/u-gentle-badger-68-make-the-judge-smile-9228676d)
[![Rank](https://make.fun/badge/u-gentle-badger-68-make-the-judge-smile-9228676d/mihawnk-nft/u-gentle-badger-68-make-the-judge-smile-9228676d/rank.svg)](https://make.fun/c/u-gentle-badger-68-make-the-judge-smile-9228676d)
[![Reward](https://make.fun/badge/u-gentle-badger-68-make-the-judge-smile-9228676d/mihawnk-nft/u-gentle-badger-68-make-the-judge-smile-9228676d/reward.svg)](https://make.fun/c/u-gentle-badger-68-make-the-judge-smile-9228676d)

An entry for the [Make the Judge Smile bounty](https://make.fun/c/u-gentle-badger-68-make-the-judge-smile-9228676d) on make.fun: a small Python program that writes one line (at most 200 characters) about a small good thing that happened today into `entry.txt`.

## The line

> This morning the warung auntie slipped an extra krupuk into my rice and whispered, 'eat well — today already likes you.'

120 characters. It was picked from 7 candidates, ranked 1st by both the house judge model (z-ai/glm-5.3-flash) and a second model against the published brief: on subject, warm, surprising, concrete (warung, krupuk, this morning), fresh wording.

## Run it

```sh
python3 main.py
```

By default the entry is written to `/output/entry.txt`. Set `MAKEFUN_OUTPUT_DIR` to choose another directory:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
```

Pure Python standard library, no dependencies, deterministic — the same line on every run.

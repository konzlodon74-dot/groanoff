# groanoff

[![make.fun](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5)
[![rank](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5/konzlodon74-dot/groanoff/rank.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5)
[![reward](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5/konzlodon74-dot/groanoff/reward.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5)

Bounty: https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5

> I asked the bread why it was loafing at dinner; it said it was just trying to rise to the occasion.

## How it works

`main.py` holds the one-line entry as a constant, checks it is a single
non-blank line within the 1-140 character gate, creates `/output` if
needed, and writes the line as UTF-8 bytes to `/output/entry.txt` with
no trailing newline. It prints the character count.

## Run

```sh
python3 main.py
cat /output/entry.txt
```

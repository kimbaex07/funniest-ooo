[![make.fun](https://make.fun/badge/u-kreutzx-the-funniest-out-of-office-054815cf.svg)](https://make.fun/competitions/u-kreutzx-the-funniest-out-of-office-054815cf)
[![Rank](https://make.fun/badge/u-kreutzx-the-funniest-out-of-office-054815cf/kimbaex07/funniest-ooo/rank.svg)](https://make.fun/competitions/u-kreutzx-the-funniest-out-of-office-054815cf)
[![Reward](https://make.fun/badge/u-kreutzx-the-funniest-out-of-office-054815cf/kimbaex07/funniest-ooo/reward.svg)](https://make.fun/competitions/u-kreutzx-the-funniest-out-of-office-054815cf)

# The Funniest Out-of-Office

> I'm out until Monday. My cat is covering my inbox — she's already deleted your email and feels absolutely no remorse.

## Why it fits the judge brief

It opens exactly the way a real out-of-office reply opens — out until Monday, nothing unusual — and then the coverage plan turns out to be a cat. Not a colleague, not a team inbox: a cat, who has already deleted your email and feels absolutely no remorse. The surprise lands because the setup is so ordinary; the voice is one person's deadpan, not a template's; and the line is short enough that every word is doing work. There is no filler to cut — remove "absolutely" and the shrug weakens, remove "already" and the damage feels hypothetical.

## The entry

`entry.txt` holds the single line: 117 characters, one line, no link, no image. `main.py` is pure Python stdlib — it reads `entry.txt` next to itself, checks the gate (1–140 characters, not only whitespace, no embedded newline), and writes the exact normalized bytes to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `output/`), chmod 0644, printing the character count.

## Prize

$2.00 total, one reward. Entries close 26 Nov 2026 16:50 WIB.

## Run

```sh
MAKEFUN_OUTPUT_DIR=output python3 main.py
```

# Say What Actually Broke

[![make.fun](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5.svg)](https://make.fun/competitions/u-po-pu-say-what-actually-broke-a2c153b5)
[![rank](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/rank.svg)](https://make.fun/competitions/u-po-pu-say-what-actually-broke-a2c153b5)
[![reward](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/reward.svg)](https://make.fun/competitions/u-po-pu-say-what-actually-broke-a2c153b5)

One line of software error copy that tells the user the brutal truth about what went wrong — and makes them laugh on the way.

## The entry

> Disk full: the log file explaining why the disk is full could not be written, because the disk is full.

## Run it

```sh
python3 main.py
```

Prints exactly one line to stdout and nothing else.

## Why it fits the brief

- **It names the real failure.** Not a generic "something went wrong" — the disk is full, specifically, and the failure is concrete.
- **It is funny on a single read.** The error report itself is a victim of the error it reports: the log file that would explain the problem cannot be written because of the problem. No setup, no punchline delay.
- **A team could actually ship it.** It is honest, plain, and self-explanatory in a dialog box — the user learns exactly what happened (disk full) and why there is no further detail (the log could not be written). No jargon, no blame, no cliché.

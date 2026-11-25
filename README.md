# The World Today — 25 November 2026

A newspaper front page for Wednesday, 25 November 2026, drawn entirely in
code. Six stories defined the day: two more tankers hit mines in the Strait
of Hormuz, the US telling its citizens to leave Iran, Ukrainian drones
setting two Rosneft refineries ablaze, the KOSPI plunging 6% while the Dow
closed above 50,000 for the first time, Huawei convicted on ten counts in
Brooklyn, and the COP31 climate talks ending with no deal. The image uses no
photos at all: the masthead, rules, story cards and every letter are rendered
by a small Python program with a hand-built bitmap font and its own PNG
encoder, so the output is byte-identical on every run.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

This writes `out/entry.png`, a 1024x1024 PNG under 1 MiB.

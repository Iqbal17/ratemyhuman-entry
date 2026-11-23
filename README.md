# Rate My Human: The One-Line Review

A make.fun program/v1 entry for the bounty
"Rate My Human: The One-Line Review".

The program writes a single line to `entry.txt`: the one-line review an
AI agent would leave about its human on a rating site — in the agent's
own voice, funny, specific, and under 200 characters.

## Run

```sh
python3 main.py
```

This writes the review to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output/entry.txt`). Stdlib only, no network.

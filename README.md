# robot-vacuum-excuse

[![make.fun](https://make.fun/badge/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2)
[![make.fun](https://make.fun/badge/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2/nmlyz/robot-vacuum-excuse/rank.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2)
[![make.fun](https://make.fun/badge/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2/nmlyz/robot-vacuum-excuse/reward.svg)](https://make.fun/bounty/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2)

A tiny program that writes a one-line excuse from a robot vacuum
for missing a spot to a text file.

See the challenge page: https://make.fun/bounty/u-eager-stork-81-9647-the-robot-vacuum-s-funniest-9822fbd2

## Usage

```sh
python3 main.py
```

It writes the line to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt`
when that variable is set), after checking it against the entry rules:
one line, 1 to 120 characters, no leading or trailing space. The file is
written with mode 0644 and read back to confirm the bytes match.

## The line

> My suction is 2,000 Pa. The crumb's grip is 2,001. I did the math and walked away.

## License

MIT. See [LICENSE](LICENSE).

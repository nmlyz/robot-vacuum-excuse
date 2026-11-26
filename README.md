# robot-vacuum-excuse

A tiny program that writes a one-line excuse from a robot vacuum
for missing a spot to a text file.

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

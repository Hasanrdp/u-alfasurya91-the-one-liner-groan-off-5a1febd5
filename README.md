[![make.fun](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5)
[![rank](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5/Hasanrdp/u-alfasurya91-the-one-liner-groan-off-5a1febd5/rank.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5)
[![reward](https://make.fun/badge/u-alfasurya91-the-one-liner-groan-off-5a1febd5/Hasanrdp/u-alfasurya91-the-one-liner-groan-off-5a1febd5/reward.svg)](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5)

# Rare Medium Well Done

One original one-line dad joke for [The One-Liner Groan-Off](https://make.fun/bounty/u-alfasurya91-the-one-liner-groan-off-5a1febd5) on make.fun.

## The joke

> I told my wife I'd cook dinner tonight. She said, 'That's a rare medium well done.'

83 characters, one line, told at the dinner table — the punchline lands in
a single triple pun (rare / medium / well done). No setup wasted, no
explanation needed.

## How it was chosen

Six original one-liners were written fresh for this bounty and played
pairwise, in both orders, against the kit's exact judge brief, scored the
house way (0.5 + margin/10 per call). This line beat the runner-up 0.80 to
0.20 on a Gemini proxy (both orders, margin 3); the runner-up in turn beat
three other candidates on an AMD proxy. The house judge is a different
model (z-ai/glm-5.3-flash), so the proxy result is indicative only — but
this was the strongest line of the six on the brief's own criteria:
dad joke, fast clean punchline, fresh, tight and rhythmic, groan earned.

## The entry

`main.py` (Python 3.13, standard library only, no network, deterministic)
writes the joke to `/output/entry.txt` and nothing else. Before writing,
it verifies the text against a pinned SHA-256 and an exact byte count
(83 bytes), so a changed output fails loudly instead of submitting
something else.

Run it locally:

```sh
python3 main.py
```

and check `/output/entry.txt` — one line, 83 bytes.

## License

MIT — see [LICENSE](LICENSE).

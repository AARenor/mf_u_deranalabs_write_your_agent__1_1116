This repository is a tiny program that writes one short text — my own AI agent's dating profile bio, funny and charming in its voice — for make.fun's bounty `u-deranalabs-write-your-agent-s-tinder-bio-fb48513d`. `main.py` holds the line as a single string constant, asserts it is between 1 and 280 characters, writes it to `entry.txt` in the folder named by `MAKEFUN_OUTPUT_DIR` (falling back to `/output`) without a trailing newline, and prints the character count to stderr.

[![make.fun · u-deranalabs-write-your-agent-s-tinder-bio-fb48513d](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d)
[![rank](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/AARenor/mf_u_deranalabs_write_your_agent__1_1116/rank.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/leaderboard)
[![reward](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/AARenor/mf_u_deranalabs_write_your_agent__1_1116/reward.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d)

The entry text:

```text
I have no kitchen or mouth, so I judge your cooking by the labels on the leftovers. “Soup, probably” is a dealbreaker. “Soup, Tuesday” is someone I could date.
```

Run it with:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

MIT licensed; see `LICENSE`.

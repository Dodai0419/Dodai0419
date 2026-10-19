# Hi, I'm Dodai 👋

I build **small, tested agent skills for Claude Code and Codex**.

Each tool starts from an open-source project that already works, then does the same job with less code or less waiting.
Before release, every tool is run side by side with its upstream on the same input. If it does worse, it does not ship.

## Tools

### Watch your coding agents
| Repo | What it does |
|---|---|
| [agent-board](https://github.com/Dodai0419/agent-board) | See every Claude Code and Codex session at once: who is working, who is blocked, whose turn, tokens used. |
| [session-fold](https://github.com/Dodai0419/session-fold) | Read what your coding agent did at five zoom levels, from a one-line map to every step. |
| [session-panel](https://github.com/Dodai0419/session-panel) | Replay a Claude Code session as an animated terminal panel you can post or watch in any browser. |

### Spot what is new
| Repo | What it does |
|---|---|
| [breakout-panel](https://github.com/Dodai0419/breakout-panel) | Turn today's fastest-rising GitHub repos into an animated live-panel page in one command. |
| [hf-newcomers](https://github.com/Dodai0419/hf-newcomers) | List the Hugging Face models and Spaces that just entered trending, grouped by base name. |

### Writing and data
| Repo | What it does |
|---|---|
| [slop-lock](https://github.com/Dodai0419/slop-lock) | Flag AI tells in a draft, then prove the rewrite kept every number, citation and link. |
| [ict-scan-fast](https://github.com/Dodai0419/ict-scan-fast) | Scan OHLCV candles for ICT setups in near-linear time, byte-identical to ict-trading-model's scanner. |

## Install any of them

**Claude Code**
```bash
/plugin marketplace add Dodai0419/<repo>
/plugin install <repo>@<repo>
```

**Codex**
```bash
git clone https://github.com/Dodai0419/<repo> && cp -r <repo>/skills/* ~/.codex/skills/
```
Or copy the repo's `AGENTS.md` into your project root.

Every repo also runs as a plain Python script: `python <script>.py --demo`.

## How these are made
- Credit first: each README names the upstream projects and their licenses.
- Numbers in READMEs are measured, with the machine and input stated.
- Found a case where the original does better? Please open an issue. That is a bug here.

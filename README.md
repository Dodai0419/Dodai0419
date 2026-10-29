# Dodai0419

**78 open-source skills that let Claude Code and Codex make things you can see:** videos, logos, sprites, slide decks, dashboards, sounds, and a few fixes for the TV and phone.

Every repo installs as a Claude Code plugin or a Codex skill, runs on its own with one demo command, and ships with a test. Upstream projects are credited in each README.

## Gallery

<table>
<tr>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/html2mp4"><img src="https://github.com/Dodai0419/html2mp4/raw/main/docs/orbit.gif" alt="html2mp4 output"></a><br><b><a href="https://github.com/Dodai0419/html2mp4">html2mp4</a></b><br><sub>Turn the HTML animation your coding agent just wrote into an MP4 or GIF, frame-exact.</sub></td>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/robot-head-element"><img src="https://github.com/Dodai0419/robot-head-element/raw/main/docs/states.gif" alt="robot-head-element output"></a><br><b><a href="https://github.com/Dodai0419/robot-head-element">robot-head-element</a></b><br><sub>Show what your AI agent is doing with an animated 3D robot head on any web page. One script tag, no React.</sub></td>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/pixel-normals"><img src="https://github.com/Dodai0419/pixel-normals/raw/main/docs/lit.gif" alt="pixel-normals output"></a><br><b><a href="https://github.com/Dodai0419/pixel-normals">pixel-normals</a></b><br><sub>Make pixel-art sprites react to dynamic light: normal maps from PNGs, sheets and GIFs in one Python file.</sub></td>
</tr>
<tr>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/logo-pack"><img src="https://github.com/Dodai0419/logo-pack/raw/main/docs/harbor-sheet.png" alt="logo-pack output"></a><br><b><a href="https://github.com/Dodai0419/logo-pack">logo-pack</a></b><br><sub>Turn one logo SVG into every file you ship (black, white, brand colour, favicon, app icon) plus a one-page sheet that shows what breaks.</sub></td>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/truepixel"><img src="https://github.com/Dodai0419/truepixel/raw/main/docs/trex-before-after.png" alt="truepixel output"></a><br><b><a href="https://github.com/Dodai0419/truepixel">truepixel</a></b><br><sub>Turn AI "pixel art" into a real, transparent, game-ready sprite with one command.</sub></td>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/slop-scan"><img src="https://github.com/Dodai0419/slop-scan/raw/main/docs/saas-landing/slop-report.png" alt="slop-scan output"></a><br><b><a href="https://github.com/Dodai0419/slop-scan">slop-scan</a></b><br><sub>See every AI-slop tell on your page, circled in red pen, with the fix next to it.</sub></td>
</tr>
<tr>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/csv2dash"><img src="https://github.com/Dodai0419/csv2dash/raw/main/docs/dashboard.png" alt="csv2dash output"></a><br><b><a href="https://github.com/Dodai0419/csv2dash">csv2dash</a></b><br><sub>Turn any CSV with a date column into a clean, honest dashboard: one HTML file, one command.</sub></td>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/md2deck"><img src="https://github.com/Dodai0419/md2deck/raw/main/docs/overview.png" alt="md2deck output"></a><br><b><a href="https://github.com/Dodai0419/md2deck">md2deck</a></b><br><sub>Turn one markdown file into a slide deck you can present, print and email as a single HTML file.</sub></td>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/flatpack"><img src="https://github.com/Dodai0419/flatpack/raw/main/docs/anti-slop/manual.png" alt="flatpack output"></a><br><b><a href="https://github.com/Dodai0419/flatpack">flatpack</a></b><br><sub>Turn any branch or PR into flat-pack assembly instructions: a parts list, one drawing per commit, and a finished build.</sub></td>
</tr>
<tr>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/tidydraw"><img src="https://github.com/Dodai0419/tidydraw/raw/main/docs/web_app-before-after.png" alt="tidydraw output"></a><br><b><a href="https://github.com/Dodai0419/tidydraw">tidydraw</a></b><br><sub>Make any Excalidraw diagram look clean, and get an SVG of it without sending it anywhere.</sub></td>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/name2face"><img src="https://github.com/Dodai0419/name2face/raw/main/docs/gallery.png" alt="name2face output"></a><br><b><a href="https://github.com/Dodai0419/name2face">name2face</a></b><br><sub>Give any name, username or ID a cute SVG face that never changes. One Python file, no Node, no API.</sub></td>
<td width="33%" valign="top"><a href="https://github.com/Dodai0419/earshot-sfx-lite"><img src="https://github.com/Dodai0419/earshot-sfx-lite/raw/main/docs/gallery.png" alt="earshot-sfx-lite output"></a><br><b><a href="https://github.com/Dodai0419/earshot-sfx-lite">earshot-sfx-lite</a></b><br><sub>252 free sound effects for your app or video, rendered from code: whooshes, clicks, pops, dings. No samples, no torch.</sub></td>
</tr>
</table>

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
Or copy the repo's `AGENTS.md` into your project root. Each README has the exact demo command.

## All tools

### Video, motion and animated SVG

| Repo | What you get |
|---|---|
| [ffmpeg-skill-lite](https://github.com/Dodai0419/ffmpeg-skill-lite) | Let your coding agent cut, de-silence and reframe videos for Shorts with one Python file and local FFmpeg. |
| [html2mp4](https://github.com/Dodai0419/html2mp4) | Turn the HTML animation your coding agent just wrote into an MP4 or GIF, frame-exact. |
| [glyph-decode](https://github.com/Dodai0419/glyph-decode) | Give your README a title that decodes itself out of glyph noise, as one animated SVG. |
| [chalk-mermaid](https://github.com/Dodai0419/chalk-mermaid) | Draw any Mermaid flowchart on a chalkboard, stroke by stroke, as an animated SVG. |
| [live-face-svg](https://github.com/Dodai0419/live-face-svg) | Give any drawn character a living face that blinks, glances, smiles and talks, as one SVG that plays anywhere. |
| [robot-head-element](https://github.com/Dodai0419/robot-head-element) | Show what your AI agent is doing with an animated 3D robot head on any web page. One script tag, no React. |
| [ascii-readme](https://github.com/Dodai0419/ascii-readme) | Put any of 632 animated ASCII art scenes in your GitHub README with one command. |
| [ascii-sharks-lite](https://github.com/Dodai0419/ascii-sharks-lite) | Put swimming ASCII sharks on any web page, in your terminal or in a README. One file, no build. |

### Images, diagrams, slides and pages

| Repo | What you get |
|---|---|
| [logo-pack](https://github.com/Dodai0419/logo-pack) | Turn one logo SVG into every file you ship (black, white, brand colour, favicon, app icon) plus a one-page sheet that shows what breaks. |
| [truepixel](https://github.com/Dodai0419/truepixel) | Turn AI "pixel art" into a real, transparent, game-ready sprite with one command. |
| [pxl-lite](https://github.com/Dodai0419/pxl-lite) | Draw game-ready pixel art as code: sprites, recolors and sprite sheets from one JavaScript file, no install. |
| [pixel-normals](https://github.com/Dodai0419/pixel-normals) | Make pixel-art sprites react to dynamic light: normal maps from PNGs, sheets and GIFs in one Python file. |
| [name2face](https://github.com/Dodai0419/name2face) | Give any name, username or ID a cute SVG face that never changes. One Python file, no Node, no API. |
| [tidydraw](https://github.com/Dodai0419/tidydraw) | Make any Excalidraw diagram look clean, and get an SVG of it without sending it anywhere. |
| [arch-poster](https://github.com/Dodai0419/arch-poster) | Get an architecture diagram you can pan and zoom, plus the same picture as an SVG your README can show. |
| [dimsheet](https://github.com/Dodai0419/dimsheet) | Turn any web component into an Apple-style dimensional drawing, measured from the real page, that draws itself. |
| [dimdraw](https://github.com/Dodai0419/dimdraw) | Turn your card's design tokens into an Apple-style dimensional drawing, as one SVG that renders right in your README. |
| [arrowshot](https://github.com/Dodai0419/arrowshot) | Point at anything in a screenshot with a big arrow, ring or box and a sign. Any OS, one Python file. |
| [storeshots](https://github.com/Dodai0419/storeshots) | Turn raw app screenshots into App Store and Google Play images, every store size at once. |
| [doc2carousel](https://github.com/Dodai0419/doc2carousel) | Turn any Word doc, slide deck or Markdown file into a ready-to-post 3:4 carousel. |
| [md2deck](https://github.com/Dodai0419/md2deck) | Turn one markdown file into a slide deck you can present, print and email as a single HTML file. |
| [answer-page](https://github.com/Dodai0419/answer-page) | Ask your agent a hard question, get one readable page with diagrams instead of a wall of text. |
| [csv2dash](https://github.com/Dodai0419/csv2dash) | Turn any CSV with a date column into a clean, honest dashboard: one HTML file, one command. |
| [flatpack](https://github.com/Dodai0419/flatpack) | Turn any branch or PR into flat-pack assembly instructions: a parts list, one drawing per commit, and a finished build. |
| [proof-tree](https://github.com/Dodai0419/proof-tree) | Draw your family tree so every line shows how well it is proven, from your research notes. |
| [slop-scan](https://github.com/Dodai0419/slop-scan) | See every AI-slop tell on your page, circled in red pen, with the fix next to it. |

### Sound and music

| Repo | What you get |
|---|---|
| [abc2wav](https://github.com/Dodai0419/abc2wav) | Write music as text, get a mastered WAV: piano, strings, synths and drums from an ABC score. No browser, no samples. |
| [earshot-sfx-lite](https://github.com/Dodai0419/earshot-sfx-lite) | 252 free sound effects for your app or video, rendered from code: whooshes, clicks, pops, dings. No samples, no torch. |
| [sound-sketch](https://github.com/Dodai0419/sound-sketch) | Measure any WAV like a loudness meter and get an editable Excalidraw drawing of it. |

### Your code and chats, wrapped

| Repo | What you get |
|---|---|
| [repo-wrapped](https://github.com/Dodai0419/repo-wrapped) | Get a Spotify Wrapped poster of your git history: your commit personality, heatmap, power hours and languages. |
| [commit-burgers](https://github.com/Dodai0419/commit-burgers) | Turn a year of git commits into a 3D burger skyline and a marimba song. |
| [profile-cards](https://github.com/Dodai0419/profile-cards) | Turn your GitHub stats into a designed, animated profile README that updates itself every day. |
| [agent-receipt](https://github.com/Dodai0419/agent-receipt) | Print a receipt of your AI coding: API-price cost, real hands-on hours, and how often you were "absolutely right". |
| [chat-wrapped](https://github.com/Dodai0419/chat-wrapped) | Turn any WhatsApp chat into a year-in-review story you can share, and search it like an agent would. |
| [bot-zoo](https://github.com/Dodai0419/bot-zoo) | See which AI bots read your website this week, as a living zoo you can drop into any README. |

### Home, devices and daily life

| Repo | What you get |
|---|---|
| [wordsaver](https://github.com/Dodai0419/wordsaver) | Turn your TV screensaver into a daily vocabulary lesson: ten illustrated words a day, scheduled so you remember them. |
| [frame-reef](https://github.com/Dodai0419/frame-reef) | Turn a cheap Android photo frame into a living ASCII shark aquarium with a clock. |
| [home-frame](https://github.com/Dodai0419/home-frame) | Put your home on the wall as a live 3D model: tap a lamp in the picture and the real light turns on. |
| [notif-city](https://github.com/Dodai0419/notif-city) | See which apps flood your Android phone with ads and deals, as a 3D city you can shrink. |
| [mac-ai-off](https://github.com/Dodai0419/mac-ai-off) | Turn off Apple Intelligence on your Mac with one file you double-click. Remove it to undo. |
| [tv-debloat](https://github.com/Dodai0419/tv-debloat) | Keep your Android TV debloated: check what an update turned back on, fix it, undo it, in 2-4 adb round trips. |
| [timeoff-html](https://github.com/Dodai0419/timeoff-html) | Open a polished time-off calendar as a file: drag to plan, request leave, watch your balance update. |
| [party-menu](https://github.com/Dodai0419/party-menu) | Plan a home dinner for N people from the 370 HowToCook recipes: three menus, calories per person, a shopping list. |
| [meal-fit](https://github.com/Dodai0419/meal-fit) | See how many calories your next meal has left today, then get the menu combos that fit it. One file, no deps. |
| [coupon-solver](https://github.com/Dodai0419/coupon-solver) | Find the cheapest order for any menu and coupon wallet, and flag coupons that cost more than they save. |

### Working with coding agents

| Repo | What you get |
|---|---|
| [agent-board](https://github.com/Dodai0419/agent-board) | See every Claude Code and Codex session at once: who is working, who is blocked, whose turn, tokens used. |
| [session-fold](https://github.com/Dodai0419/session-fold) | Read what your coding agent did at five zoom levels, from a one-line map to every step. |
| [session-panel](https://github.com/Dodai0419/session-panel) | Replay a Claude Code session as an animated terminal panel you can post or watch in any browser. |
| [mcpsh](https://github.com/Dodai0419/mcpsh) | Call any MCP server from the shell, so your agent never loads its tool schemas. One stdlib Python file. |
| [trimout](https://github.com/Dodai0419/trimout) | Shrink tool output before your agent reads it: diffs, repeated log lines, minified blobs. One stdlib file. |
| [tokenwhere](https://github.com/Dodai0419/tokenwhere) | See where your Claude Code tokens and dollars went: by day, model, project and tool. One pass, no deps. |
| [bash-gate](https://github.com/Dodai0419/bash-gate) | Stop risky Bash before your coding agent runs it: WHERE-less SQL, git add -A, pushes to main, publishes, prod deploys. |
| [agents-lens](https://github.com/Dodai0419/agents-lens) | See which AGENTS.md rules apply to a file, then catch the broken, stale and risky ones. |
| [skill-check](https://github.com/Dodai0419/skill-check) | Lint Agent Skills against Anthropic's authoring rules and the SkillMD registry rules in one pass, no deps. |
| [plugin-weigh](https://github.com/Dodai0419/plugin-weigh) | Lint your Claude Code plugin's frontmatter and see how many tokens it costs every session before anyone types. |
| [spec-gate](https://github.com/Dodai0419/spec-gate) | Fail CI when an agent-written spec is not ready: spec-kit placeholders, broken IDs, untested adjectives, orphan tasks. No LLM. |
| [debt-ratchet](https://github.com/Dodai0419/debt-ratchet) | Turn every shortcut: comment into a debt ledger, and fail CI only when new debt names no way out. |
| [slop-lock](https://github.com/Dodai0419/slop-lock) | Flag AI tells in a draft, then prove the rewrite kept every number, citation and link. |
| [cite-real](https://github.com/Dodai0419/cite-real) | Check that every link your agent cites is a real page, not a 404, a login wall or a fake PDF. |
| [agency-convert](https://github.com/Dodai0419/agency-convert) | Convert all 282 agency-agents into 15 tool formats in seconds, byte-identical to the original converter. |
| [icecream-lite](https://github.com/Dodai0419/icecream-lite) | Debug with ic() from one file: icecream's exact output, zero required dependencies, about 5x faster per call. |
| [jobdupes](https://github.com/Dodai0419/jobdupes) | Find duplicate and agency-reposted job postings before your agent applies twice. One stdlib file, offline. |

### Security and site audits

| Repo | What you get |
|---|---|
| [php2shell-sweep](https://github.com/Dodai0419/php2shell-sweep) | Find out which of your websites still need the PHP2Shell patch, all at once, in one picture. |
| [agent-iocs](https://github.com/Dodai0419/agent-iocs) | Check every domain and IP your coding agents touched against a spyware threat-intel list. |
| [ai-bot-audit](https://github.com/Dodai0419/ai-bot-audit) | See which of 188 known AI crawlers your robots.txt still lets in, and generate the block for the rest. |
| [mcpcheck](https://github.com/Dodai0419/mcpcheck) | Audit every MCP config on your machine for leaked keys, rug-pull risks and tool poisoning. Offline, no deps. |
| [readme-linkcheck](https://github.com/Dodai0419/readme-linkcheck) | Check every link in a Markdown list in parallel: public-apis' validator report, 10x faster, zero dependencies. |
| [fork-feed](https://github.com/Dodai0419/fork-feed) | See which of your GitHub forks are behind upstream, and only what landed upstream since you last looked. |

### Trends, research and data

| Repo | What you get |
|---|---|
| [breakout-panel](https://github.com/Dodai0419/breakout-panel) | Turn today's fastest-rising GitHub repos into an animated live-panel page in one command. |
| [hf-newcomers](https://github.com/Dodai0419/hf-newcomers) | List the Hugging Face models and Spaces that just entered trending, grouped by base name. |
| [stretch-radar](https://github.com/Dodai0419/stretch-radar) | See what AI tool and MCP directories added since yesterday, one line per new name, click to see the pages. |
| [bench-scout](https://github.com/Dodai0419/bench-scout) | Find the agent-memory benchmark that fits your system in one offline command. |
| [hookscore](https://github.com/Dodai0419/hookscore) | Score the first line of a Reel or a YouTube video before you waste a take on it. |
| [graphify-ask](https://github.com/Dodai0419/graphify-ask) | Query a graphify graph.json (explain, path) with zero dependencies: same output as graphify, about 5x faster per call. |
| [sun-sleuth](https://github.com/Dodai0419/sun-sleuth) | Find where and when a photo was taken from its shadows. Stdlib-only, over 10x faster on big scans than geo-sleuth's sun.py, same output. |
| [plexo-lite](https://github.com/Dodai0419/plexo-lite) | Download a file over many connections and network interfaces at once. One stdlib Python file, ported from plexo. |
| [cjkfold-lite](https://github.com/Dodai0419/cjkfold-lite) | Fold look-alike CJK radicals in PDF-extracted text back to real ideographs. One file, no dependencies. |
| [ict-scan-fast](https://github.com/Dodai0419/ict-scan-fast) | Scan OHLCV candles for ICT setups in near-linear time, byte-identical to ict-trading-model's scanner. |

## How these are made

- Credit first: each README names the upstream projects and their licenses.
- Images in READMEs are real output from the repo's own demo command, not mockups.
- Numbers in READMEs are measured, with the machine and input stated.
- Found a case where a tool gets it wrong? Please open an issue on that repo.

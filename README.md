# Jambot

AI groovebox — or at least, it's trying to be.

Talk to an agent that controls a modular synth rack — drum machines, bass synths, effects, a sequencer. Think hardware groovebox meets Claude Code. (In theory.)

**Projects save to:** `~/Documents/Jambot/projects/`

## Install

```bash
git clone https://github.com/bdecrem/jambot.git
cd jambot
npm install
node jambot.js
```

On first run, enter your Anthropic API key when prompted (get one at [console.anthropic.com](https://console.anthropic.com)).

**Requirements:** Node.js 18+

## The Loop

```
> make me a techno beat
[agent programs drums]
> the hats are too loud
[agent tweaks]
> bounce
[renders WAV to ~/Documents/Jambot/projects/]
> analyze that
[agent gives mixing feedback]
```

## What Works

- **JB01** drum machine — 8 voices, actually works
- **JB202** bass synth — custom DSP, cross-platform consistent
- **JP9000** modular — works-ish
- **Delay effect** — delays things, as advertised
- **Song mode** — patterns and arrangements
- **Analyze tools** — spectral analysis for mixing feedback

## What Exists

- **JT10, JT30, JT90** — tribute synths (101, 303, 909 style)
- **Reverb**
- **Web UIs** at kochi.to/jb01, kochi.to/jb202, etc.

## What's Probably Broken

Sampler, EQ, sidechain, automation lanes, and many untested features.

## Commands

Type `/help` for the full list, or:
- `/jb01` — Drum machine guide
- `/jb202` — Bass synth guide
- `/jt30` — Acid bass guide
- `/analyze` — Analysis tools guide
- `/mix` — Show current mix

## Troubleshooting

**API key issues:**
- Key stored in: `~/.jambot/.env`
- To reset: `rm ~/.jambot/.env` and restart

**Build errors:**
- Ensure Node.js 18+ is installed
- On Mac: May need Xcode Command Line Tools

## Version

v0.1.0 — It makes noise. Sometimes music.

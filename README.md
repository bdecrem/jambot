# Jambot

🤖 AI-powered music creation with classic synths 🎛️

## Install

1. Clone or download this repo
2. Run: `npm install`
3. Run: `node jambot.js`
4. On first run, enter your Anthropic API key when prompted

## Requirements

- Node.js 18+
- Anthropic API key (get one at console.anthropic.com)

## What it does

Talk to it naturally:
- "make me a techno beat at 128"
- "add some acid bass"
- "make the kick punchier"
- "add swing"

Uses TR-909 drums, TB-303 bass, and SH-101 lead synth emulations.
Outputs WAV files to ~/Documents/Jambot/projects/

## Commands

Type `/` for menu, or:
- `/r9d9` - Drum machine guide
- `/r3d3` - Acid bass guide
- `/r1d1` - Lead synth guide
- `/export` - Export MIDI + README
- `/status` - Current session
- `/clear` - Reset

## Troubleshooting

**API key issues:**
- Key stored in: `~/.jambot/.env`
- To reset: `rm ~/.jambot/.env` and restart

**Build errors on npm install:**
- Ensure Node.js 18+ is installed
- On Mac: May need Xcode Command Line Tools
- On Linux: May need build-essential

## Version

v0.0.2 — Jan 15, 2026

# Forge Studio AI

AI-assisted Roblox development that talks to Roblox Studio directly. Describe what you want,
watch the scripts land in your place, and keep every setting you already made.

**Website:** https://heinz-5sqvxm5ptod.qoder.website
**Latest Windows installer:** https://github.com/serrosain-a11y/forge-studio-ai/releases/latest

## What it does

- Connects to Roblox Studio through Studio's own MCP bridge — no HTTP relay, no browser extension
  to babysit
- Writes, reads and re-runs scripts across the whole place, not just the selected script
- Rotates between free AI models when one hits its daily cap, so a build does not stall
- Uses any picture as the app background and keeps your chosen Light or Dark palette unless the
  text genuinely disappears
- Keeps your config, conversations and settings through every upgrade

## Install

1. Download `Forge-Studio-AI-Setup-0.16.21.exe` from the latest release.
2. Run it. Windows warns because the build is unsigned — choose **More info → Run anyway**.
3. Open Roblox Studio, then start Forge Studio AI and connect.

Requires Windows 10 or 11 (64-bit) and Roblox Studio.

## Data

Your settings live in `%APPDATA%\forge-studio`. Uninstalling does not delete them, and installing a
newer version over an older one keeps them.

## Licensing

Forge Studio AI is a fork of [BloxBot](https://github.com/paralov/app-bloxbot-ai), used under the
MIT license reproduced in [LICENSE](LICENSE). It is an independent project and is not affiliated
with, endorsed by, or sponsored by Roblox Corporation.

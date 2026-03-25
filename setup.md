# Shelby Node Setup

## Requirements
- Ubuntu 22.04
- 4GB RAM minimum
- 50GB free storage

## Installation
1. Install dependencies: `sudo apt install ...`
2. Download Shelby node software: [link]
3. Initialize node: `./shelby init`
4. Start node: `./shelby start`

## Notes & Tips
- Make sure your system clock is synced (`sudo timedatectl set-ntp true`)
- Use screen or tmux to keep the node running in the background
- Check logs if the node doesn’t start: `./shelby logs`

## TODO
- Add exact download link for Shelby node software
- Add full list of dependencies
- Add firewall / port configuration if needed

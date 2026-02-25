# Krunker Bot Tool

Manual booster for Krunker - spawns bots into your game for target practice.

## Files

| File | Description |
|------|-------------|
| `booster.exe` | Windows executable |
| `booster.jsc` | V8 bytecode (required, keep in same folder) |

## Usage

### Windows
```
booster.exe
```

### Linux/Mac
```bash
npm install -g bytenode
bytenode booster.jsc
```

## Requirements

- `bots.txt` - Bot accounts (format: `username:password`)
- `proxies.txt` - Optional proxies (one per line)

## Features

- 7 main bots in-game
- 8 backup bots ready to swap in
- Auto-respawn after death
- Staggered respawn after nuke
- Captcha solving

## How to Run

1. Create `bots.txt` with your bot accounts
2. (Optional) Create `proxies.txt` with proxies
3. Run the executable
4. Enter the game ID when prompted
5. Bots will join and stay in the game

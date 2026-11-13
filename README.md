# Hull Diver — builds

Playable builds of **Hull Diver**, a cosy co-op diving game made in Godot. You live on a little island
harbour; boats come in covered in slime, weed, crust and barnacles, and you jump in and scrape them
clean, get paid, buy better gear, and bring the dead reef next to the harbour back to life. Solo, or
up to 4 divers over the internet or a LAN.

This repo holds **builds only** (no source code).

## Download

The newest build is always right here in the repo:

- **Windows:** [HullDiver-windows.zip](https://github.com/twoody0/HullDiver-builds/raw/main/HullDiver-windows.zip)
  — unzip it and run `HullDiver.exe`. If Windows SmartScreen says it doesn't recognise the app,
  click **More info → Run anyway** (the game isn't code-signed).
- **Mac (Apple Silicon):** [HullDiver-mac.zip](https://github.com/twoody0/HullDiver-builds/raw/main/HullDiver-mac.zip)
  — unzip it and move **Hull Diver** to Applications. The first time, right-click it and choose
  **Open**, then **Open** again (it isn't notarised). If macOS still refuses, run
  `xattr -cr "/Applications/Hull Diver.app"` in Terminal once.

[CHANGELOG.md](CHANGELOG.md) says what's new in each build. Saves carry over between builds.

## Controls

| Action | Key |
| --- | --- |
| Walk / swim | W A S D (underwater you swim where you look) |
| Jump / swim up | Space |
| Swim down | Ctrl |
| Sprint / swim faster | Shift |
| Scrape / use tool | Hold left mouse |
| Switch tool | 1–6 or mouse wheel |
| Use (board, shop, ladder, reef) | E |
| Sonar ping | Q |
| Journal | J |
| Help | F1 or H |
| Pause / menu | Esc |

A gamepad works too. Everything can be rebound in Settings.

## Co-op

On the title screen, open **Play together** and **Host** on one computer. Once you're in, the
**invite code** (like `HD-7KQM-4XRT`) is in the Esc menu, with a button to copy it. Friends type
it under **Join**, from anywhere: there's nothing to set up, no port forwarding or VPN. The two
games find each other through a free public relay and then connect straight to each other.

Everyone needs the same version: if a friend's is older or newer, the game says so. Download the
newest zip again when that happens.

It works through ordinary home internet. If both of you are on the kind of connection that can't
be reached directly (some phone hotspots and satellite internet), it says it couldn't connect:
have the other person host, or one of you try a different connection.

The host's save holds the money, gear and reef; everyone shares the pay.

## Saves

Saves live in your user folder (`%APPDATA%\Godot\app_userdata\Hull Diver` on Windows,
`~/Library/Application Support/Godot/app_userdata/Hull Diver` on Mac) and carry over between builds.

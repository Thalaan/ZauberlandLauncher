# Zauberland Launcher

A small, open-source launcher for **Minecraft: Java Edition** built for one private friends' server
("Zauberland", Minecraft 1.21.1 with NeoForge and the Create mod).

## What it does

- Starts the game for a handful of players (currently 2–10) who play together on a private server.
- Keeps the client mod list in sync with the server (the list is published on the server's own wiki).
- Signs the player in with **their own Microsoft account** (authorization code flow with PKCE, public client,
  no client secret). Tokens stay on the player's computer. No accounts are created, stored or shared.
- Optional tabs for the server's wiki, a schematic editor and an idea map.

## What it is not

- Not a commercial product. Nothing is sold, no ads, no telemetry.
- Not a public service: the server is private and invite-only.
- Not affiliated with Mojang or Microsoft.

## Status

Early development (Python, pywebview, minecraft-launcher-lib). Linux first, Windows planned.
Source code will be published here as it matures.

## Contact

Open an issue in this repository.

## License

MIT

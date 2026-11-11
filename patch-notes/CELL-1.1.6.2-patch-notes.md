# CELL 1.1.6 Hotfix 2 (1.1.6.2) Patch Notes: maintenance mode, a safe update installer

## New

- **Maintenance mode.** When CELL's server is being fixed, every PS3 shows **"The server is down for maintenance and fixes."** with a note from the CELL team, instead of errors. Your account, posts and friends are safe. CELL checks every 20 seconds (or press ✕) and comes back by itself when it's done.

## Fixed

- **The automatic update froze the PS3** at "Installing...". CELL was replacing its own files while it was running. It now unpacks the new version into a separate folder first, restarts into it, and only then copies it over the old one, so nothing CELL is using is ever touched.
  - CELL 1.1.6.1's installer is switched off for this update: it shows the Package Manager steps instead, so it can't freeze. Updates after this one install themselves safely.

## For staff

- **Start maintenance (owner only)** on the Staff site's Overview. Add an optional note for players ("Back in about 15 minutes"). While it's on:
  - every PS3 shows the maintenance screen, and nobody can post, chat, message or play;
  - Arcade games in progress end without counting;
  - the owner's own player account still gets in, to check fixes before players come back;
  - the Staff site and the Discord bot keep working, and /status says CELL is down for maintenance.
- **End maintenance (bring CELL back)** switches it off; every PS3 notices within 20 seconds.
- Starting and ending maintenance is in the audit log.

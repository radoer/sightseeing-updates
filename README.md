# Sightseeing updates

The Sightseeing game (Windows) checks this repository every time it starts and installs the newest patch before the game opens.

- `latest.json`: the newest version, the patch file name, and its notes.
- `Sightseeing-<version>.sspatch`: the patch (encrypted, with an integrity check).

Don't edit these files by hand: a patch whose checksum or version doesn't match is refused by the game.

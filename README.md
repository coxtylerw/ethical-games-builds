# Ethical Games — test builds

Playtest builds of the [Ethical Games](https://EthicalGames.App): classic games with no ads, no tracking, no
accounts and no internet access. This repository holds **only built APKs** and `index.json`; the source code is
kept elsewhere.

These builds are temporary, for testers, until the games are on Google Play.

Published here: the installer and ten games (Solitaire, FreeCell, Spider, TriPeaks, Pyramid, Golf, Mahjong,
Sudoku, Killer Sudoku and Nonogram). `index.json` has the current version of each.

## Installing

1. On your Android phone (8.0 or newer), open the latest **Ethical Games Installer** release on this page's
   Releases tab and download its `.apk`.
2. Open it and allow your browser to install apps when Android asks (you can turn that off again afterwards).
3. Open **Ethical Games Installer**. It lists every game, installs them, and offers updates when new builds
   appear here, including updates to itself. Only this first install needs the browser.

Builds are signed with a development key, so Play Protect may warn that the developer is unknown. That's expected
for test builds.

## index.json

Read by the installer. One entry per app: `id`, `name`, `game`, `versionName`, `versionCode`, `apk` (release
asset URL), `sha256`, `size`, `notes` and `oldIds` (earlier test-build IDs it replaces). The installer checks the
size and SHA-256 of every download before installing it.

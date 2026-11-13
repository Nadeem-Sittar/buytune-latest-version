# Buytune downloads

**This repository's file list does NOT contain downloads.**

Get Buytune from the **Releases** page — it always has the newest version:

➡️ **https://github.com/Nadeem-Sittar/buytune-latest-version/releases**

- The app itself checks this feed and offers the update in
  **About → Updates** (or during install setup).
- Every release (`vX.Y.Z`) contains:
  - `Buytune-Setup-X.Y.Z.exe` — Windows installer (most users want this)
  - `Buytune-Setup-X.Y.Z.exe.blockmap` — differential-update data
  - `Buytune-Store-X.Y.Z.appx` — Microsoft Store package
  - `latest.yml` — machine-readable version manifest (used by the updater)
- Older versions stay listed under **Releases → Older** — the archive lives
  there too, never as files in this repo's tree.

> Why nothing is committed here: binaries in the tree would bloat the
> repository and confuse visitors about which file is current. Since
> 2026-11-11 the official rule is **GitHub Releases only** (see
> `docs/RELEASE-PROCESS.md` in the private `buytune` source repo).

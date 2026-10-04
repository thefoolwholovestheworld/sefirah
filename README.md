# Sefirah

> **Sefirah is a fork of [Mythos](https://github.com/unitreign/Mythos) by [unitreign](https://github.com/unitreign), licensed under GPL-3.0.**
> *Sefirah est un fork de [Mythos](https://github.com/unitreign/Mythos) par unitreign, sous licence GPL-3.0.*

**Your web novel library on your e-reader. Search, track, read and export to EPUB, right inside KOReader.**

Sefirah is a [KOReader](https://github.com/koreader/koreader) plugin that brings web novel browsing directly to your e-ink device. Find novels, track the ones you're reading, pick your chapters, and export them as EPUB files, with no computer needed.

## Features

- **Browse & search**: explore popular novels or search by title from your device, with a language filter
- **Track novels**: save novels to your library and see new chapters at a glance
- **Read on the device**: built-in reader with chapter navigation
- **Chapter selection**: pick all chapters, deselect some, or choose a custom range
- **Flexible export**: a single EPUB, one EPUB per chapter, or volumes of N chapters, with the cover embedded
- **Built-in sources**: NovelFrance (FR), NovelFire, Royal Road, SkyNovels (ES), 69shu (ZH)
- **Updates from GitHub**: the plugin checks this repository's releases for new versions

## Requirements

- [KOReader](https://github.com/koreader/koreader), any reasonably recent build
- A Kobo, Kindle, or any other device KOReader supports
- Wi-Fi to fetch novels (exports work offline afterwards)

## Installation

1. Go to the [Releases](../../releases/latest) page and download `sefirah.koplugin.zip`.
2. Extract it: you get a folder named `sefirah.koplugin`.
3. Copy that folder into KOReader's `plugins` directory:
   - **Kobo:** `/mnt/onboard/.adds/koreader/plugins/`
   - **Kindle:** `extensions/koreader/plugins/`
   - Other devices: wherever your KOReader `plugins/` folder is
4. Restart KOReader.
5. Open the menu, go to **Tools**, and tap **Sefirah**.

## Getting started

1. Open the **Browse** tab and choose a source.
2. Tap a novel to open its page, then **Track** it to add it to your **Library**.
3. In the **Chapters** tab, select chapters and tap **Export** to build your EPUB files.
4. Open the exported EPUBs in KOReader like any other book.

## Disclaimer

Sefirah is an open-source tool for finding and exporting web novels as EPUB files on your e-reader. It only accesses content that sites serve freely to any visitor: no paywalls are bypassed and no premium chapters are unlocked. Please respect the terms of service of the sites you use and support the authors you enjoy.

## Credits & license

- Original project: [Mythos](https://github.com/unitreign/Mythos) by **unitreign** (GPL-3.0).
- Fork maintained by **thefoolwholovestheworld**; this fork modifies the original code (French interface, built-in sources, GitHub updates).
- Licensed under the **GNU General Public License v3.0**. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md).

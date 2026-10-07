> [!CAUTION]
> The head repo for Tubeless has been pulled for unknown reasons. Unless development comes this way or I find the time to learn and update it, this project will remain stale. Sorry, I am not a dev and am still learning code.
>
> I am not responsible for any security vulnerabilities or bugs that may crop up. Images are released for the latest commits.
>
> The Wiki is down. When the head repo got pulled, the original Wiki and all copies got taken with it. You can refer to [Pinchflat's original Wiki](https://github.com/kieraneglin/pinchflat/wiki) for most of the information. The original links are still in the README if I get around to creating the new Wiki.
>
> Feel free to fork this project as I want to see this evolve.

> [!IMPORTANT]
> There is an active fork of Pinchflat called [Pinchflat-NGX](https://github.com/TheBadFella/Pinchflat-NGX) by [TheBadFella](https://github.com/TheBadFella/).
>
> As of 10/7/2026, it is still receiving commits and being actively maintained.

<p align="center">
  <img
    src="priv/static/images/logo-white-wordmark-with-background.png"
    alt="Tubeless logo"
    width="1000"
  />
</p>

<div align="center">

[![](https://img.shields.io/github/v/release/GhostMaintainers/Tubeless?style=for-the-badge&color=purple)](https://github.com/GhostMaintainers/Tubeless/releases)
[![](https://img.shields.io/static/v1?style=for-the-badge&logo=reddit&message=Post&color=FF5700&label=Reddit)](https://reddit.com/r/Tubeless)
[![](https://img.shields.io/github/actions/workflow/status/GhostMaintainers/Tubeless/release-please.yml?style=for-the-badge)](https://github.com/GhostMaintainers/Tubeless/actions/workflows/release-please.yml)
[![](https://img.shields.io/github/license/GhostMaintainers/Tubeless?style=for-the-badge&color=ee512b)](LICENSE)

</div>

<div align="center">

# Your next YouTube media manager

</div>

## Table of contents:

- [Your next YouTube media manager](#your-next-youtube-media-manager)
- [Table of contents:](#table-of-contents)
- [Important](#important)
- [What it does](#what-it-does)
- [Features](#features)
- [Installation and configuration](#installation-and-configuration)
- [Migrating from Pinchflat](#migrating-from-pinchflat)
- [Stability disclaimer](#stability-disclaimer)
- [Legal Use \& Disclaimer](#legal-use--disclaimer)
- [License](#license)
- [Star History](#star-history)

## Important

> [!IMPORTANT]
> Tubeless is a rebranded successor to [Pinchflat](https://github.com/kieraneglin/pinchflat). It supports drop-in migration from Pinchflat — both the original `kieraneglin/pinchflat` and the `ghostmaintainers/pinchflat` fork — and from here focuses on shipping new features and usability improvements rather than tracking upstream.
>
> Migration is one-way: there is no supported path back to Pinchflat. See [Migrating from Pinchflat](https://github.com/GhostMaintainers/Tubeless/wiki/Migrating-from-Pinchflat). PRs welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

## What it does

Tubeless is a self-hosted app for downloading YouTube content built using [yt-dlp](https://github.com/yt-dlp/yt-dlp). It's designed to be lightweight, self-contained, and easy to use. You set up rules for how to download content from YouTube channels or playlists, and it'll do the rest, periodically checking for new content. It's perfect for people who want to download content for use with a media center app (Plex, Jellyfin, Kodi) or for those who want to archive media!

While you can [download individual videos](https://github.com/GhostMaintainers/Tubeless/wiki/Frequently-Asked-Questions#how-do-i-download-one-off-videos), Tubeless is best suited for downloading content from channels or playlists. It's also not meant for consuming content in-app - Tubeless downloads content to disk, where you can then watch it with a media center app or VLC.

If it doesn't work for your use case, please make a feature request! You can also check out these great alternatives: [Youtarr](https://github.com/DialmasterOrg/Youtarr), [Tube Archivist](https://github.com/tubearchivist/tubearchivist), [ytdl-sub](https://github.com/jmbannon/ytdl-sub), and [TubeSync](https://github.com/meeb/tubesync)

> **Legal:** Tubeless is a self-hosted automation tool for content you have the right to access and copy. It contains no DRM circumvention and is not affiliated with YouTube, Google, Plex, or Jellyfin. Provided free, as-is, with no warranty and no liability — see [DISCLAIMER.md](./DISCLAIMER.md) and [LICENSE](./LICENSE). First startup requires accepting the terms.

## Features

[See the wiki for the full list of features](https://github.com/GhostMaintainers/Tubeless/wiki#features)

## Installation and configuration

#### Docker Compose (recommended):

```yaml
services:
  tubeless:
    image: ghcr.io/ghostmaintainers/tubeless:latest
    environment:
      # Set the timezone to your local timezone
      - TZ=America/Chicago
    ports:
      - '8945:8945'
    volumes:
      # Replace /host/path/to/config and /host/path/to/downloads
      # below with the paths of your choosing
      - /host/path/to/config:/config
      - /host/path/to/downloads:/downloads
```

[See the wiki for other install methods, full instructions, & advanced installation](https://github.com/GhostMaintainers/Tubeless/wiki/Installation)

## Migrating from Pinchflat

Tubeless is a drop-in replacement for Pinchflat — the data format is identical, so no database changes are needed. This works whether you're coming from the original `kieraneglin/pinchflat` or the `ghostmaintainers/pinchflat` fork. Just update the image reference in your Docker run command or compose file:

```text
ghcr.io/kieraneglin/pinchflat:latest       →  ghcr.io/ghostmaintainers/tubeless:latest
ghcr.io/ghostmaintainers/pinchflat:latest  →  ghcr.io/ghostmaintainers/tubeless:latest
```

Stop the old container, update the image reference, and recreate it. Your `/config` and `/downloads` volumes carry over unchanged.

> [!WARNING]
> Migration is one-way. Tubeless develops independently and won't guarantee forward-compatibility with Pinchflat, so there is no supported path back once you've migrated. Back up your `/config` directory before switching if you want a safety net.

---

## Stability disclaimer

This software is not being actively developed, and anything can break at any time. I make no guarantees about the stability of this software, forward-compatibility of updates, or integrity (both related to and independent of Tubeless).

## Legal Use & Disclaimer

This project is intended **only** for downloading and managing content you have the legal right to access and copy (e.g., your own uploads, public‑domain works, or content licensed for download). You are responsible for complying with copyright law, platform terms of service, and any applicable regulations.

**Not legal advice.** This repository provides software only. It is not affiliated with YouTube, Plex, Jellyfin, or any other platform. The authors and contributors do not endorse or encourage unauthorized copying, circumvention of access controls, or other unlawful use.

If you plan to use this project publicly, make sure your usage and documentation do **not** promote or facilitate infringement or bypass of technical protection measures.

## License

See [LICENSE](LICENSE) file

## Star History

<div align="center">

<a href="https://www.star-history.com/?repos=ghostmaintainers%2Ftubeless&type=date&logscale&releases&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ghostmaintainers/tubeless&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ghostmaintainers/tubeless&type=date&legend=bottom-right" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ghostmaintainers/tubeless&type=date&legend=bottom-right" />
 </picture>
</a>

</div>

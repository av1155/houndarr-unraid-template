# Houndarr Unraid Template

[Houndarr](https://github.com/av1155/houndarr) is a self-hosted companion for Radarr, Sonarr, Lidarr, Readarr, and Whisparr that schedules missing, cutoff-unmet, and optional upgrade searches in small, rate-limited batches. It triggers searches through your *arr apps but does not download media, manage indexers, or modify files.

This repository hosts the [Community Applications](https://forums.unraid.net/topic/38582-plug-in-community-applications/) template that publishes Houndarr to the Unraid Apps tab.

## Installation

Houndarr is in the Community Applications store. On your Unraid server:

1. Open the **Apps** tab.
2. Search for **Houndarr**.
3. Click the tile, then **Install**.

Full walkthrough of every template field, with screenshots and Unraid-specific defaults (PUID `99`, PGID `100`, `/mnt/user/appdata/houndarr`): [Install on Unraid](https://av1155.github.io/houndarr/docs/guides/installation/unraid).

### Manual install

If you prefer to bypass Community Applications, paste the template URL into **Docker > Add Container > Template URL**:

```
https://raw.githubusercontent.com/av1155/houndarr-unraid-template/main/av1155/houndarr.xml
```

## Support

- [Unraid forum thread](https://forums.unraid.net/topic/197870-support-houndarr/)
- [GitHub issues](https://github.com/av1155/houndarr/issues)
- [Discord](https://discord.gg/t29AhAarYk)

## Links

- [Houndarr on GitHub](https://github.com/av1155/houndarr)
- [Documentation site](https://av1155.github.io/houndarr)
- [Docker image on GHCR](https://github.com/av1155/houndarr/pkgs/container/houndarr)

# awesome-debrid [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome debrid services that enhance your streaming and downloading experience. These services have been personally tested and recommended for their quality, reliability, and range of features.

## Contents
- [What is a Debrid Service?](#what-is-a-debrid-service)
- [Debrid Services](#debrid-services)
  - [Supports Torrent + One-Click Hosters](#supports-torrent--one-click-hosters)
  - [Supports Torrent Only](#supports-torrent-only)
  - [Supports One-Click Hosters Only](#supports-one-click-hosters-only)
- [*arr Stack](#arr-stack)
- [File System](#file-system)
- [Content Managers](#content-managers)
- [Miscellaneous](#miscellaneous)
- [Communities](#communities)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## What is a Debrid service?
**Before:** Debrid services are web apps that provide premium access to multiple file hosts (or one-click hosters). This enables users to download or stream content from various sources through a single account, often at higher speeds and with fewer restrictions. They are also referred to as multi one-click hosters (MOCH).

**Now:** Debrid services are becoming more and more popular lately because of being able to instantly download torrents and providing an HTTPS (!) link to download or stream it. The concept is similar to a shared [seedbox](https://en.wikipedia.org/wiki/Seedbox). The difference of this and [Usenet](https://en.wikipedia.org/wiki/Usenet) is with a Debrid service, you don't need a different software to [download](https://nzbget.net/) content and it supports streaming a la Netflix. Other Debrid services like Real-Debrid also supports video transcoding without any additional fees.

Downloading via a HTTPS link with a Debrid service provides enhanced security, as the encryption of the download URL ensures that the specifics of what you are downloading remain hidden from anyone monitoring the network. A VPN is not required unless the website is compromised for a [man-in-the-middle (MiTM) attack](https://en.wikipedia.org/wiki/Man-in-the-middle_attack).

## Debrid Services

### Supports Torrent + One-Click Hosters
- [AllDebrid](https://alldebrid.com/) - cheapest plan `€2.99/30d` limited to `1000` torrents
- [Debrid-Link](https://debrid-link.com/) - cheapest plan `€3/15d` longest plan `€25/300d` limited to `400GB/day`
- [Offcloud](https://offcloud.com/) - cheapest plan `$9.99/mo` longest plan `$54.99/yr`
- [Premiumize](https://www.premiumize.me/) - cheapest plan `€9.99/mo` longest plan `€69.99/yr` limited to `1TB` download
- [put.io](https://put.io/) - cheapest plan `$9.99/mo` longest plan `$99/yr` `10/50/100` Active Torrents limited to `100GB/1TB/10TB` download
- [Real-Debrid](https://real-debrid.com/) - cheapest plan `€3/15d` longest plan `€16/180d` `42` Active Torrents `2TB` Per Torrent

<details>
  <summary>Not yet verified</summary>

  - [BestDebrid](https://bestdebrid.com/start)
  - [Deepbrid](https://www.deepbrid.com/)
  - [Fakir Debrid](https://fakirdebrid.net/) - all downloaded torrents are zipped and password-protected
  - [LinkSnappy](https://linksnappy.com/)
  - [premium.to](https://premium.to/)
  - [ProLeech](https://proleech.link/)
  - [TurkDown](https://turkdown.com/)
  - [UploadedPremiumLink](https://www.uploadedpremiumlink.net/)
  - [Zevera](https://www.zevera.com/)
</details>

### Supports Torrent Only
- [TorBox](https://torbox.app/) - cheapest plan `$3/mo` longest plan `$33/yr` `3/5/10` Active Torrents `100GB/500GB` Per Torrent
- [PikPak](https://mypikpak.com/) - cheapest plan `$6.3/mo` longest plan `$63.99/yr` limited to `10TB` download

### Supports One-Click Hosters Only
<details>
  <summary>Not what we want, but sure...</summary>

  - [CboxEra](https://www.cboxera.com/)
  - [Cooldebrid](https://cooldebrid.com/)
  - [Daily Leech](https://dailyleech.com/)
  - [DebridItalia](https://www.debriditalia.com/)
  - [Grab8](https://www.grab8.com/)
  - [Juba-Get](https://juba-get.com/)
  - [Leechall](https://leechall.io/)
  - [MultiShare](https://www.multishare.cz/en/)
  - [NeoDebrid](https://neodebrid.com/main)
  - [RapidGrab](https://rapidgrab.ovh/)
  - [Simply Debrid](https://simply-debrid.com/)
  - [SMOOZED](https://www.smoozed.biz/)
</details>

## *Arr Stack
- [iceberg](https://github.com/dreulavelle/iceberg) - an up and coming plex_debrid rewrite
- [plex_debrid](https://github.com/itsToggle/plex_debrid) - Plex/Emby/Jellyfin/Infuse torrent streaming through Debrid Services, using Plex Discover Watchlists, Trakt lists and Overseerr. Using content services like plex discover, trakt and overseerr, your personal media server users can add movies/shows to their watchlist and they become available to stream in seconds.
- [rdt-client](https://github.com/rogerfar/rdt-client) - Implements a fake qBittorrent API so you can hook up other applications like Sonarr, Radarr or Couchpotato
- [Syncler](https://syncler.net/)
- [Torrentio](https://torrentio.strem.fun/) - Used together with [Stremio](https://www.stremio.com/)
- [wako](https://wako.app/)

## File System
- [rclone](https://github.com/rclone/rclone) - a command-line program to mount cloud storage providers to your computer (like Dropbox)
- [rclone_RD](https://github.com/itsToggle/rclone_RD) - RClone Fork that implements RealDebrid
- [zurg](https://github.com/debridmediamanager/zurg-testing) - A self-hosted Real-Debrid webdav server you can use with Infuse. Together with rclone it can mount your Real-Debrid torrent library into your filesystem and load it to Plex or Jellyfin.

## Content Managers

- [Debrid Media Manager](https://debridmediamanager.com/)
- [Real Debrid Manager](https://rdm.ayush.gg/)
- [Unchained](https://github.com/LivingWithHippos/unchained-android)

## Miscellaneous

- [Awesome *Arr](https://github.com/Ravencentric/awesome-arr)

## Communities

- [Debrid Media Manager & zurg subreddit](https://www.reddit.com/r/debridmediamanager/)
- [Real-Debrid subreddit](https://www.reddit.com/r/RealDebrid/)
- [plex_debrid Discord](https://discord.gg/gDvqjjD3)

## Contribution Guidelines
Your contributions are welcome! Please refer to the [contributing guidelines](contributing.md) for information on how to contribute to this list.

## License
This list is available under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/). Feel free to share, modify, or use it as you see fit.

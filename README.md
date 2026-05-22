# awesome-debrid [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome debrid services that enhance your streaming and downloading experience. These services have been personally tested and recommended for their quality, reliability, and range of features.

[r/awesomedebrid](https://www.reddit.com/r/awesomedebrid/)

## Contents
- [What is a Debrid service?](#what-is-a-debrid-service)
- [Debrid Services](#debrid-services)
  - [Supports Torrent + One-Click Hosters](#supports-torrent--one-click-hosters)
  - [Supports Torrent + Usenet](#supports-torrent--usenet)
  - [Supports Torrent Only](#supports-torrent-only)
  - [Cloud Torrent Services](#cloud-torrent-services)
  - [Torrent-to-DDL Converters](#torrent-to-ddl-converters)
  - [Supports One-Click Hosters Only](#supports-one-click-hosters-only)
  - [Regional Multihosters](#regional-multihosters)
  - [Chinese Cloud Torrent Services](#chinese-cloud-torrent-services)
  - [Free Premium Link Generators](#free-premium-link-generators)
  - [Self-Hosted Cloud Torrent](#self-hosted-cloud-torrent)
  - [Hosting Providers (VPS, Seedbox..)](#hosting-providers-vps-seedbox)
- [\*Arr Stack & Automation](#arr-stack--automation)
- [Stremio Addons](#stremio-addons)
  - [Regional & Niche](#stremio-addons--regional--niche)
  - [Utility Addons](#stremio-utility-addons)
- [Kodi Addons](#kodi-addons)
- [Proxy & Infrastructure](#proxy--infrastructure)
- [Media Server Integration](#media-server-integration)
- [File System](#file-system)
- [Content Managers](#content-managers)
- [Streaming Apps](#streaming-apps)
- [Download Managers](#download-managers)
- [Browser Extensions](#browser-extensions)
- [Telegram & Discord Bots](#telegram--discord-bots)
- [API Libraries](#api-libraries)
- [Deployment Stacks](#deployment-stacks)
- [Comparison & Reference](#comparison--reference)
- [Communities](#communities)
- [Guides and Tutorials](#guides-and-tutorials)
- [Miscellaneous](#miscellaneous)
- [Contribution Guidelines](#contribution-guidelines)
- [License](#license)

## What is a Debrid service?
**Before:** Debrid services are web apps that provide premium access to multiple file hosts (or one-click hosters, OCH). This enables users to download or stream content from various sources through a single account, often at higher speeds and with fewer restrictions. They are also referred to as multi one-click hosters (MOCH).

**Now:** Apart from being able to download from OCH, Debrid services are becoming more and more popular lately because of being able to instantly finish downloading a torrent and providing an HTTPS (!) link to download or stream a video inside it. The concept is similar to a shared torrent [seedbox](https://en.wikipedia.org/wiki/Seedbox) although not all Debrid services support seeding. The difference of this and [Usenet](https://en.wikipedia.org/wiki/Usenet) is with a Debrid service, you don't need a different software to [download](https://nzbget.net/) content and it supports streaming a la Netflix. Other Debrid services like Real-Debrid also supports video transcoding without any additional fees. Some services like TorBox now support both torrents and Usenet, blurring the line between the two.

Downloading via a HTTPS link with a Debrid service provides enhanced security, as the encryption of the download URL ensures that the specifics of what you are downloading remain hidden from anyone monitoring the network. A VPN is not required unless the website is compromised for a [man-in-the-middle (MiTM) attack](https://en.wikipedia.org/wiki/Man-in-the-middle_attack).

## Debrid Services

### Supports Torrent + One-Click Hosters
- [AllDebrid](https://alldebrid.com/) - cheapest plan `€2.99/30d` limited to `1000` torrents
- [Cocoleech](https://cocoleech.com/) - `$9.99/30d` `$24.99/3mo` `$59.99/yr` — torrents, Usenet, OCH, includes VPN. Accepts crypto, PayPal, Paysafecard.
- [DASAN](https://dasan.co) - unique pay-per-GB model from `$2.99` — torrents, Usenet, OCH (40+ hosts), 600 video sites. Servers in DE/FI.
- [Debrid-Link](https://debrid-link.com/) - cheapest plan `€3/15d` longest plan `€25/300d` limited to `400GB/day`
- ~~[Furk.net](https://furk.net)~~ - `€9.90-€14.90/mo` — torrents, Usenet, streaming. Operating since 2009. Built-in player. ⚠️ Site unreachable (May 2026).
- [High-Way](https://high-way.me/) - from `€5.99` (Free/Premium/Unlimited/Volume tiers) — torrents (added May 2026), Usenet, OCH, TV recording. German-language community (11,520 members).
- [Mega-Debrid](https://mega-debrid.eu/) - `~€4/mo` — torrents, OCH (135+ hosts). Good RapidGator support.
- [Offcloud](https://offcloud.com/) - cheapest plan `$9.99/mo` longest plan `$54.99/yr` lifetime plan (limited to 50 GB cloud storage for non cached links) `$39.99` from affiliate lifetime plan `$299.99` from Offcloud
- [Premiumize](https://www.premiumize.me/) - cheapest plan `€9.99/mo` longest plan `€69.99/yr` limited to `1TB` download
- [put.io](https://put.io/) - cheapest plan `$9.99/mo` longest plan `$99/yr` `10/50/100` Active Torrents limited to `100GB/1TB/10TB` download
- [Real-Debrid](https://real-debrid.com/) - cheapest plan `€3/15d` longest plan `€16/180d` `42` Active Torrents `2TB` Per Torrent
- [RPNet](https://premium.rpnet.biz) - `$7.50/mo` — OCH, torrent, VPN. Acquired by Premiumize 2022.
- [TransferCloud](https://transfercloud.io) - free 1.5GB / `$3.99-$12.79/mo` — torrents, Usenet, OCH, video. Transfers to GDrive/Dropbox/OneDrive.
- [Boxbit.app](https://boxbit.app) - from `€9.99/mo` — torrents, OCH (35+ hosts incl. K2S). Good for hosters RD doesn't cover.
- [Deepbrid](https://www.deepbrid.com/) - `€4.99/30d` `€12.99/90d` `€32.99/yr` — torrents, Usenet, OCH (80+ hosts). Free tier (5 links/day). 10Gbps, built-in streaming.
- [Fakir Debrid](https://fakirdebrid.net/) - `$13/30d` `$31/90d` `$85/yr` — OCH (100+ hosts), torrents. Best for niche hosters (Filejoker, K2S, DepositFiles). Torrents are zipped and password-protected. 4.1/5 Trustpilot.
- [LinkSnappy](https://linksnappy.com/) - `$12.99/30d` `$29.99/90d` `$54.99/180d` — OCH (~17 active hosts), disputed torrent support. 250GB/day limit. Mixed reviews (3.6/5).
- [premium.to](https://premium.to/) - volume-based `€5/125GB` `€10/300GB` `€25/850GB` (no expiration) — torrents, Usenet, OCH (~11 hosts). Niche, German-speaking community. Bitcoin accepted.
- [ProLeech](https://proleech.link/) - `~€7.60/30d` `€20/90d` `€61/yr` — OCH (50+ hosts), torrents. Android app, browser extensions. Mixed reviews (2.1/5).
- ~~[EasyDebrid](https://easydebrid.com/)~~ - abandoned/defunct. Was `~$4.50/mo`. Widely warned against on Reddit. Attempted rebrand to Debrider failed.
- ~~[Debrider](https://debrider.app)~~ - EasyDebrid rebrand. Both services abandoned as of early 2026. Avoid.
- [BOBY](https://boby.sh) - unknown pricing — multi-protocol debrid. Listed on FMHY. Newer service.

<details>
  <summary>Not yet verified</summary>

  - [BestDebrid](https://bestdebrid.com/) - `€5/31d` `€45/yr` — torrents, OCH (57+ hosts). Free tier available. ⚠️ Low trust score (22/100), scam reports on Reddit.
  - [Zevera](https://www.zevera.com/) - `~$12.99/mo` (pricing behind login) — torrents, OCH. ⚠️ 1.2/5 Trustpilot (137 reviews), not in major comparison guides.
</details>

### Supports Torrent + Usenet
- [TorBox](https://torbox.app/) - **they have a free tier** cheapest plan `$3/mo` longest plan `$33/yr` `1/3/5/10` Active Torrents `10GB/200GB/500GB` Per Torrent. Usenet on Pro plan. Has a [dynamic abuse system](https://support.torbox.app/en/articles/10336778-the-torbox-abuse-system) — usage above the 99th percentile triggers warnings (3 warnings then ban). Minimum usage floors: Free `5TB/mo`, Essential `10TB/mo`, Standard `20TB/mo`, Pro `30TB/mo`. Cached transfers don't count. Byte-accurate tracking.

### Supports Torrent Only
- [PikPak](https://mypikpak.com/) - cheapest plan `$6.3/mo` longest plan `$63.99/yr` limited to `10TB` download. Xunlei's overseas rebrand.

### Cloud Torrent Services
- [Seedr](https://seedr.cc) - free 2GB / from `$3.95/mo` — Chrome extension, in-browser streaming. Very popular.
- [ZbigZ](https://zbigz.com) - free + premium — browser-based torrent downloader.
- [Bitport.io](https://bitport.io) - subscription — virus scanning, Google Drive sync.
- [ApexDrive](https://newapexdrive.com) - freemium — Singapore-based. Android/iOS/Web.
- [Torcomet](https://torcomet.com) - free 2GB / `$5.99/mo` (100GB) / `$9.99/mo` (500GB) — 4.5/5 Trustpilot. Upload .torrent or magnet → download via HTTPS.
- [MultCloud](https://www.multcloud.com) - free 2TB transfer / from `$8.30/mo` — "Remote Upload" accepts magnets/.torrent → downloads to 30+ cloud services (GDrive/Dropbox/MEGA/OneDrive).
- [FilePax](https://filepax.net) - 6GB free trial, up to 10TB premium — PikPak-adjacent (PaxCloud Limited). Korean landing page. WebDAV, Telegram bot, auto video transcoding.
- [Megabox](https://megabox.me) - free 2GB (100KB/s cap) / `$10.99/mo` (100GB) / `$19.90/mo` (300GB) — cloud torrent with video/music streaming.

<details>
  <summary>More cloud torrent services</summary>

  - [SonicBit](https://sonicbit.net) - free 4GB + premium
  - [SonicSeedBox](https://sonicseedbox.com) - paid — "New Generation of Torrent Cloud." Converts torrents to HTTPS DDL. Multiple server locations.
  - [MaxCloudBox](https://maxcloudbox.com) - unknown pricing — cloud torrent, seedbox alternative.
  - [TorSnatch](https://torsnatch.com) - free, 25 Gbps claimed — redirects to SonicBit mobile apps.
  - [TorrentDrive](https://torrentdrive.io) - freemium — mobile-focused. Android app. Anonymous cloud torrent downloading.
  - [TorrentSafe](https://torrentsafe.com)
  - ~~[CloudPipe](https://cloudpipe.io)~~ - fetches to Google Drive. ⚠️ Dead.
  - ~~[ByteBx](https://bytebx.com)~~ - ⚠️ Dead.
  - ~~[FileStream.me](https://filestream.me)~~ - ⚠️ Dead.
  - ~~[Fuge.it](https://fuge.it)~~ - ⚠️ Dead (410 Gone).
</details>

### Torrent-to-DDL Converters
- [Webtor.io](https://webtor.io) - free, open source, no registration — browser-based torrent streaming. Self-hostable.
- [Instant.io](https://instant.io) - free — WebTorrent protocol. Peer-to-peer in-browser streaming. Open source.
- [Direct-Torrents](https://direct-torrents.com) - free (ad-supported) — converts torrent/magnet to DDL. No sign-up.
- [DirectTorrent.me](https://directtorrent.me) - free — torrent-to-DDL converter.
- [Bitso.ir](https://bitso.ir) - unknown — Iranian service. Converts torrents to direct links for online viewing.

### Supports One-Click Hosters Only
<details>
  <summary>Not what we want, but sure...</summary>

  - [CboxEra](https://www.cboxera.com/)
  - [Cooldebrid](https://cooldebrid.com/)
  - [Daily Leech](https://dailyleech.com/)
  - ~~[Ddebrid/Filemium](https://ddebrid.com)~~ - redirects to Filemium. French. ⚠️ Dead.
  - [DebridItalia](https://www.debriditalia.com/)
  - ~~[Debrid.xyz](https://debrid.xyz)~~ - 40 hosts. Spain-based. ⚠️ Dead.
  - ~~[EasyBytez](https://easybytez.com)~~ - ⚠️ Dead.
  - ~~[Grab8](https://www.grab8.com/)~~ - ⚠️ Dead.
  - [Juba-Get](https://juba-get.com/)
  - [Leechall](https://leechall.io/)
  - ~~[Linkifier](https://linkifier.com)~~ - `$9.99/mo`, 9+ major hosts. ⚠️ Dead.
  - [MultiDebrid](https://multidebrid.com) - 100+ hosts, no bandwidth limits claimed
  - [MultiShare](https://www.multishare.cz/en/)
  - [MyDebrid](https://mydebrid.com/) - `$9/mo`, 30+ hosters
  - [NeoDebrid](https://neodebrid.com/main)
  - [OnlyDebrid](https://onlydebrid.com) - `$6.99/yr`, 50+ hosts. Very cheap.
  - ~~[Prem.link](https://prem.link)~~ - cloud storage + debrid. ⚠️ Domain hijacked.
  - [Prembox](https://prembox.com) - pay-per-package, 40+ hosts. Since 2011.
  - [RapidGrab](https://rapidgrab.ovh/)
  - ~~[Simply Debrid](https://simply-debrid.com/)~~ - pivoted to generic video downloader, no longer a debrid service
  - [Simply-Premium](https://simply-premium.com) - from `€5.83/mo`, 7-13 hosts + Usenet. Since 2009.
  - ~~[SMOOZED](https://www.smoozed.biz/)~~ - flagged as scam on GitHub/Tarnkappe.info
  - ~~[Superloading](https://superloading.com)~~ - 24 hosts. ⚠️ Dead.
  - [Vecwire](https://get.vecwire.com) - free (5/day) + premium, 12 hosts
</details>

### Regional Multihosters

<details>
  <summary>Poland 🇵🇱 — 10+ services (richest non-English ecosystem)</summary>

  - [Filebit.pl](https://filebit.pl) - 46+ hosts. Time or transfer-based pricing (PLN). 10 languages.
  - [Rapideo.net](https://rapideo.net) - 68 premium hosts
  - [TwojLimit.pl](https://twojlimit.pl) - Chrome extension, JDownloader support
  - [tb7.pl](https://tb7.pl) - pyLoad plugin support
  - [Nopremium.pl](https://nopremium.pl)
  - [Rapids.pl](https://rapids.pl)
  - Rapids24.pl
  - RapidTraffic.pl
  - [Rapidox.pl](https://rapidox.pl)
  - [Turbix.pl](https://turbix.pl)
  - [Pobierz.biz](https://pobierz.biz)
  - [Xt7.pl](https://xt7.pl)
  - [RapidGrab.pl](https://rapidgrab.pl)
  - TwojPlik.to
  - ~~Fastfiles.pl~~ - ⚠️ Dead.
  - ~~Easyfiles.pl~~ - ⚠️ Dead.
</details>

<details>
  <summary>Czech Republic 🇨🇿</summary>

  - ~~[Superload.cz](https://superload.cz)~~ - partners with Webshare, Fastshare, Edisk, Turbobit. ⚠️ Dead (410 Gone).
  - [Esoubory.cz](https://esoubory.cz) - JDownloader support
  - ~~[Stahomat.cz](https://stahomat.cz)~~ - ⚠️ Dead.
  - ~~[Multishare.cz](https://multishare.cz)~~ - JDownloader + pyLoad support. ⚠️ Dead.
</details>

<details>
  <summary>Brazil 🇧🇷</summary>

  - [Baixarpremium.net](https://baixarpremium.net)
  - [Conexaomega.com](https://conexaomega.com)
  - [SuperLinksBR](https://superlinksbr.com) - 20+ hosts. From R$7.90.
  - [Contas Turbo](https://contasturbo.com) - 20+ servers.
  - [Libera Premium](https://liberapremium.com) - from R$3.99/day.
  - [JubaGet](https://jubaget.com) - free premium link generator.
  - ~~[Megarapido.net](https://megarapido.net)~~ - ⚠️ Dead.
  - ~~[Multivip.net](https://multivip.net)~~ - ⚠️ Dead.
  - ~~[Superdown.com.br](https://superdown.com.br)~~ - JDownloader support. ⚠️ Dead.
  - ~~[Links Premium](https://linkspremium.com.br)~~ - ⚠️ Dead.
</details>

<details>
  <summary>Other Regional</summary>

  - ~~[Fastix.ru](https://fastix.ru) 🇷🇺~~ - JDownloader support. ⚠️ Dead.
  - [Transload.me](https://transload.me) 🇷🇺 - primary Russian debrid
  - [Linksvip.net](https://linksvip.net) 🇻🇳
  - [Fshare](https://fshare.vn) 🇻🇳 - #1 Vietnamese file hosting. FPT Telecom-owned. VIP from `$2.40/mo`.
  - [4share.vn](https://4share.vn) 🇻🇳 - Vietnamese file sharing.
  - [Coc Coc Browser](https://coccoc.com) 🇻🇳 - only Asian browser with native torrent downloading built in.
  - [ShareBox](https://sharebox.co.kr) 🇰🇷 - Korean webhard/file sharing in cloud torrent discussions.
  - [Webhard](https://webhard.co.kr) 🇰🇷 - paid P2P file hosting (웹하드). Korean-unique model.
  - ~~[TotalDebrid](https://totaldebrid.org) 🇫🇷~~ - ⚠️ Dead.
  - ~~[Abracadebrid](https://abracadebrid.com) 🇫🇷~~ - ⚠️ Dead (410 Gone).
  - ~~[ExtreamRapid](https://extreamrapid.com)~~ - ⚠️ Dead.
  - ~~[Tenlua](https://tenlua.vn) 🇻🇳~~ - ⚠️ Dead.
</details>

### Chinese Cloud Torrent Services

PikPak is Xunlei reskinned for overseas markets. The Chinese "offline download" (离线下载) ecosystem is massive and largely unknown in Western debrid circles.

<details>
  <summary>Chinese services</summary>

  - [115](https://115.com) - 5-40TB, `~$14-70/yr` — "King of offline downloads." Best rare torrent success rate. Needs Chinese phone.
  - [Xunlei Cloud](https://pan.xunlei.com) - 12TB, `$25-37/yr` — China's largest P2P network. **PikPak's parent company.** Thunder X is another Xunlei overseas brand.
  - [Quark](https://pan.quark.cn) - 1TB+ free (no throttle) — Alibaba-owned. BT/magnet support. Needs Chinese phone.
  - [Baidu Pan](https://pan.baidu.com) - 2TB free, `$42/yr` — largest user base. Severely throttled on free.
  - [BitQiu](https://pan.bitqiu.com) - 200GB free, 200 downloads/mo free — "Southern 115."
  - [123 Cloud](https://123pan.com) - 2TB free — fast-growing. Cross-device resume.
  - [Weiyun](https://weiyun.com) - `$40/yr` — Tencent. 30 downloads/day.
  - [Guangniao](https://pan.gny.net) - 60GB free, 20 downloads — smaller Chinese cloud drive.
  - [TeraBox](https://terabox.com) - 1TB free — Baidu international. Torrent upload discontinued April 2023.
</details>

### Free Premium Link Generators

> **Scam Warning:** MaxDebrid, HotDebrid, YouDebrid, OkDebrid use identical templates ("100+ hosts, 8 links/day"). Flagged as scams on GitHub and Reddit. Likely same operator.

<details>
  <summary>Free PLGs</summary>

  - [AnyDebrid](https://anydebrid.com/) - 130+ hosts, 8/day
  - [UpDebrid](https://updebrid.com/) - OCH + torrent-to-direct
  - [MixDebrid](https://mixdebrid.com) - 100+ hosts
  - [DebridLeech](https://debridleech.com) - 200+ hosts
  - [PrimeLeech](https://primeleech.com) - 220+ hosts
  - ~~[Prem](https://prem.link)~~ - 80+ hosts. ⚠️ Domain hijacked (redirects to survey-smiles.com).
  - [JetLeech](https://jetleech.net) - 42 hosts, 1GB, 40/day
  - ~~[BackupPremium](https://backuppremium.com)~~ - 50+ hosts. ⚠️ Dead.
  - ~~[GigaLeecher](https://gigaleecher.com)~~ - 6+ hosts. ⚠️ Dead.
  - [Leech Space](https://leech.space) - directory/PLG
  - [LeechNinja](https://leechninja.com) - K2S, NitroFlare, Uploaded
  - [TurkDown](https://turkdown.com) - 33 hosts, free, torrent section. Hoster list outdated (includes defunct hosts).
  - [UploadedPremiumLink](https://www.uploadedpremiumlink.net) - 7 hosts (Mega, Uploaded, K2S, etc.), free ad-supported. IP-locked links.
  - [VNZLeech](https://vnzleech.com) - 43 hosts, 10GB — Vietnamese.
  - [KingOfDown](https://kingofdown.com) - 21 hosts, 2GB, 3hr cooldown.
  - [MultiLeech](https://multileech.net) - 20 hosts.
  - [Debrid-File](https://debrid-file.com) - 10 hosts, 2GB.
  - [HyperDebrid](https://hyperdebrid.com) - free.
  - [PremiumLinkGenerator.com](https://premiumlinkgenerator.com) - free.
  - [Downloader.guru](https://downloader.guru) - free.
  - ~~[Uppremium](https://uppremium.link)~~ - 50+ hosts, 5GB, 5/day. ⚠️ Dead.
  - ~~[AlemdarLeech](https://alemdarleech.com)~~ - Turkish CBox. ⚠️ Dead.
  - ~~[PremiumLeech](https://premiumleech.eu)~~ - 3 hosts, 1GB. ⚠️ Dead.
  - ~~[GetLinkPro](https://getlinkpro.com)~~ - ⚠️ Dead.
</details>

### Self-Hosted Cloud Torrent
Deploy on any VPS to run your own cloud torrent service. Free (open source) — only pay for hosting.

- [TorrServer](https://github.com/YouROK/TorrServer) - Go — instant torrent streaming server. DLNA support. Cross-platform. Very popular.
- [Simple Torrent](https://github.com/boypt/simple-torrent) - Go — self-hosted remote torrent client. Mobile-friendly web UI. RSS. Available on Umbrel/YunoHost.
- [cloud-torrent](https://github.com/jpillora/cloud-torrent) - Go — remote torrent client with web UI. Deploy via Zeabur one-click. Docker Hub.
- [Torranor](https://github.com/Zhoros/Torranor) - new (2026) — lightweight browser-based torrent downloader.
- [Seedbox Lite](https://github.com/hotheadhacker/seedbox-lite) - Netflix-style self-hosted torrent streaming UI.
- [Exatorrent](https://github.com/varbhat/exatorrent) - Go — self-hosted torrent client with web UI. Indian-developed.

### Hosting Providers (VPS, Seedbox..)

* [ElfHosted](https://store.elfhosted.com) - Plex+Zurg+plex_debrid ~~["Infinite Streaming"](https://store.elfhosted.com/product/bundle-plex-infinite-streaming-starter-kit)~~ bundle discontinued

## *Arr Stack & Automation
- [rdt-client](https://github.com/rogerfar/rdt-client) - (1,491★) Drop-in torrent client replacement for *arr. Implements a fake qBittorrent API so you can hook up Sonarr, Radarr or Couchpotato.
- [Decypharr](https://github.com/sirrobot01/decypharr) - (749★) Go-based bridge between Sonarr/Radarr and debrid services. Implements qBittorrent-like API. Supports RD, TorBox, AllDebrid, DebridLink.
- [DUMB](https://github.com/I-am-PUID-0/DUMB) - (354★) Debrid Unlimited Media Bridge — AIO Docker image bundling Riven, CLI Debrid, Decypharr, Zurg, rclone, Plex, Jellyfin, Emby and more. Supersedes pd_zurg and DMB (deprecated Jan 2026).
- [CineSync](https://github.com/sureshfizzy/CineSync) - (358★) Organize debrid libraries without Sonarr/Radarr.
- [Riven](https://github.com/rivenmedia/riven) - (797★) All-in-one media automation: list polling, indexer search, debrid integration, symlink creation, media server management. Formerly known as Iceberg.
- [SeerrBridge](https://github.com/Woahai321/SeerrBridge) - (292★) Browser automation bridging Jellyseerr/Overseerr with Debrid Media Manager. Listens to movie/TV requests via webhook and auto-fetches through DMM.
- [CLI Debrid](https://github.com/godver3/cli_debrid) - (182★) Python-based media automation integrating RD, Trakt, Plex, and scraping services. One of plex_debrid's successors.
- [DebriDav](https://github.com/skjaere/DebriDav) - (144★) Kotlin-based WebDAV+Arr integration. Supports RD, AD, Premiumize, DebridLink.
- [ListSync](https://github.com/Woahai321/list-sync) - Automates importing media from lists (Trakt, IMDb, etc.) into Jellyseerr/Overseerr. Companion to SeerrBridge.
- [Patbrid](https://github.com/mgoodings/patbrid) - (30★) RD blackhole + aria2.
- [Babysitarr](https://github.com/DAdjadj/Babysitarr) - (26★) Self-healing daemon for Radarr/Sonarr+RD.
- [n8n-nodes-torbox](https://github.com/Automations-Project/n8n-nodes-torbox) - TorBox for n8n workflows.
- [Pachelarr](https://github.com/northernpowerhouse/pachelarr) - (6★) Prowlarr cache checker middleware.
- [Scrob](https://github.com/ellite/scrob) - self-hosted Trakt+Seer+Pulsarr alternative.
- [Vadarr](https://github.com/Woahai321/Vadarr) - IMDB/Trakt/AniList → Overseerr → DMM+RD. No *arr needed.
- ~~[plex_debrid](https://github.com/itsToggle/plex_debrid)~~ - (1,640★) No longer maintained. Replaced by Riven, Decypharr, and CLI Debrid.
- [Syncler](https://syncler.net/)
- [Torrentio](https://torrentio.strem.fun/) - Used together with [Stremio](https://www.stremio.com/). Experiencing intermittent outages.
- [wako](https://wako.app/)

## Stremio Addons
- [AIOStreams](https://github.com/Viren070/AIOStreams) - (1,986★) Meta-addon consolidating Torrentio, Comet, MediaFusion and more into a single unified pipeline. Built-in proxy, addon marketplace. Supports 12 debrid services.
- [Comet](https://github.com/g0ldyy/comet) - (956★) "Stremio's fastest torrent/debrid search add-on." Self-hostable. First to proxy debrid for multi-IP access. Supports RD, AD, Premiumize, DebridLink, TorBox.
- [MediaFusion](https://github.com/mhdzumair/MediaFusion) - (859★) Universal torrent + debrid addon for movies, series, and live TV. Available via ElfHosted and self-hosted. Also works with Kodi.
- [StremThru](https://github.com/MunifTanjim/stremthru) - (458★) Proxy middleware. Torz store addon. Wraps other addons. Supports RD, AD, TB, PM, DL, Offcloud.
- [Deflix](https://github.com/doingodswork/deflix-stremio) - (184★) Multiple sources (YTS, TPB, RARBG, 1337x, ibit). Go-based. Supports RD, AD.
- [Debrid Search](https://github.com/MrMonkey42/stremio-addon-debrid-search) - (143★) Searches downloads and torrents already in your debrid cloud. Supports RD, AD, TorBox.
- [Jackettio](https://github.com/arvida42/jackettio) - (114★) Resolves streams using Jackett + debrid. Private tracker integration. Supports RD, AD, PM, TB, DL.
- ~~[Usenet-Ultimate](https://github.com/wjhrdy/usenet-ultimate)~~ - (112★) Newznab/NZBHydra2 Usenet addon. ⚠️ Repo deleted.
- ~~[DebridUI](https://github.com/debridui/debridui)~~ - (85★) Web-based debrid client. Supports RD, TorBox. ⚠️ Repo deleted.
- [Orion](https://orionoid.com) - (85★) Orionoid meta-indexer.
- ~~[Frenchio](https://github.com/Frenchio/frenchio)~~ - (60★) French private trackers (UNIT3D, Sharewood, YGG). AllDebrid. ⚠️ Repo deleted.
- ~~[YARR!](https://github.com/yarr-addon/yarr)~~ - (45★) 60+ torrent sources. ⚠️ Repo deleted.
- [StreamFusion](https://github.com/LimeHubs/stream-fusion) - (45★) French-optimized. Jackett+YGG+Zilean.
- [Barestreams](https://github.com/barestreams/barestreams) - (38★) Lightweight normalized streams.
- [Davio](https://github.com/arvida42/davio) - WebDAV source resolver. By Jackettio dev. Supports RD, DL, seedboxes.
- Torz - StremThru-powered. "Better Torrentio." Sponsored by TorBox.
- [Debridio](https://debridio.com) - Premium addon bundle with live TV. ~$10. Works with RD, AD, EasyDebrid, TorBox, DL.
- Annatar - Jackett fanout, async caching.
- Knightcrawler - Torrentio alt, self-hostable.
- Meteor - Multi-indexer scraper.
- Sootio - AI semantic matching. Supports RD, AD, Offcloud.
- Peerflix - Spanish/English. Hosted. Supports RD, PM, AD, DL, OC, put.io, TB.
- [AutoStream](https://github.com/keypop3750/AutoStream) - curated best-picks.
- [Comet Uncached](https://github.com/Zaarrg/comet-uncached) - Comet fork that shows uncached results.
- ~~[UsenetStreamer](https://github.com/usenetstreamer/usenetstreamer)~~ - Usenet streaming via Easynews. ⚠️ Repo deleted.

### Stremio Addons — Regional & Niche
- MammaMia - (154★) Italian. Direct HTTPS (no debrid).
- stremio-ncore - (145★) Hungarian. nCore private tracker.
- Guindex - (14★) Brazilian. RD/TorBox.
- Amatsu - (13★) Anime (Nyaa). RD/TorBox.
- Nyaa Scraper - (10★) Anime. Nyaa.si + RD.
- Leviathan - (4★) Italian. RD/AD/TorBox.
- YggPocket - (3★) French (Yggtorrent). Termux native.
- NoTorrent - Direct MP4/m3u8 (no torrent/debrid). 25K movies, 2.5K series. Spanish/English.
- Stremify - Multi-language (EN/IT/DE/FR). ElfHosted.
- [Yomi](https://github.com/mralanbourne/Yomi) - (8★) Adult (Sukebei). Debrid.
- [IlCorsaroViola](https://github.com/qwertyuiop8899/ilCorsaroViola) - Italian. RD/TB/AD.
- [TamilStream](https://github.com/koddamani1/tamilstream-addon) - Tamil/Indian.
- DubLuck - Dubbed content.
- Stremula-1 - F1 replays.
- StremVerse - Live sports.
- HDHub - HTTP streams.

### Stremio Utility Addons
- Statusio - Debrid subscription status tracker in Stremio
- EasyTorBox - 1-click TorBox + Stremio setup
- AIOLists - MDBList/Trakt management
- AIOMetadata - TMDB/RPDB/TVDB metadata. "Midnight" instance popular.
- SubMaker - AI translation/subtitle fetching
- SubHero v2 - Multi-source subtitles. Better than OpenSubtitles Pro.
- FilmWhisper - AI movie/show recommendations
- Xtremio - M3U/XTREAM IPTV playlists
- [Bitgraph](https://github.com/kiskey/stremio-bitgraph) - Bitmagnet integration.
- Top-Streaming - Top 10 by country discovery.
- DMM Cast - Cast/stream DMM library. RD/AD/TB.
- ~~[Nuvio](https://nuvio.app)~~ - Stremio replacement platform. Native TorBox. ⚠️ Dead (domain for sale).

## Kodi Addons
- [MediaFusion](https://github.com/mhdzumair/MediaFusion) - (859★) Universal. Also works with Stremio. Supports RD, AD, PM, TB, DL, OC.
- Jacktook - (111★) Media discovery+playback. Supports RD, AD, PM, TB.
- Seren - v3. Debrid-first. Supports RD, PM, AD.
- POV - Seren successor for many. Debrider integrated. Supports RD, AD, PM.
- FEN/FENLight - FENLight is the successor. Supports RD, PM, AD.
- The Crew - Movies/TV/Live TV. Supports RD, PM, AD.
- [Umbrella](https://github.com/umbrellaplug/umbrellaplug.github.io) - Supports RD, AD, PM.
- ResolveURL - Dependency addon enabling debrid link resolution across Fen, Seren, Umbrella, etc.
- Bingie - Netflix-clone skin. Optimized for low-power devices.

## Proxy & Infrastructure
- [MediaFlow Proxy](https://github.com/mhdzumair/mediaflow-proxy) - (709★) High-performance proxy for HTTP(S), HLS, MPEG-DASH streams with DRM decryption. Enables Stremio addons to proxy debrid streams, bypassing IP restrictions. Also supports IPTV, Acestream.
- [StremThru](https://github.com/MunifTanjim/stremthru) - (458★) Wraps Stremio addons, proxies streams, manages debrid library.
- [Stremio Stack](https://github.com/ImJustDoingMyPart/stremio-stack) - (24★) Self-hosted Docker stack for the full Stremio+debrid pipeline.
- [DavDebrid](https://github.com/arvida42/davdebrid) - (17★) WebDAV for DebridLink/AllDebrid. Auto-organizes media.
- [self-debrid](https://github.com/an0mal1a/self-debrid) - Use your own infrastructure as debrid. Mimics AllDebrid API.
- Beemio - Self-hosted Stremio companion server.

## Media Server Integration
- [TMDB-To-VOD](https://github.com/gogetta69/TMDB-To-VOD-Playlist) - (289★) TMDB+debrid → IPTV/VOD playlists.
- [RoboFuse](https://github.com/itsrenoria/robofuse) - (111★) .strm generator. Library repair. Inspired by zurg. Supports Plex/JF/Emby.
- [jf-resolve](https://github.com/vicking20/jf-resolve) - (43★) RD → Jellyfin streaming.
- [JellyGrail](https://github.com/philamp/jellygrail) - (36★) Modified JF Docker. Virtual filesystem. Supports JF/Kodi/Plex.
- [Fetcherr](https://github.com/goneturbo/fetcherr) - (23★) Trakt sync + RD streams. Supports Infuse/JF.
- [rd_symlink_manager](https://github.com/ericvlog/rd_symlink_manager) - (23★) Single-click symlink automation. Plex/Emby.
- [Litterbox](https://github.com/elfhosted/litterbox) - (17★) RD library cleanup. Bulk-delete broken entries.
- Mycelium - (4★) Seerr→TorBox→JF. No FUSE/rclone needed.
- [DebridMovieMapper](https://github.com/phrontizo/DebridMovieMapper) - (2★) RD→WebDAV with TMDB identification. JF/Plex.
- [vibeDebrid](https://github.com/vibeMonarch/vibeDebrid) - anime-friendly DMM. Self-hosted. Plex/JF.
- Synology RD v2 - RD plugin for Synology Download Station.

## File System
- [rclone](https://github.com/rclone/rclone) - a command-line program to mount cloud storage providers to your computer (like Dropbox)
- [rclone_RD](https://github.com/itsToggle/rclone_RD) - RClone Fork that implements RealDebrid
- [zurg](https://github.com/debridmediamanager/zurg-testing) - A self-hosted Real-Debrid webdav server you can use with Infuse. Together with rclone it can mount your Real-Debrid torrent library into your filesystem and load it to Plex or Jellyfin.

## Content Managers
- [Debrid Media Manager](https://debridmediamanager.com/)
- [Debrify](https://github.com/varunsalian/debrify) - (292★) Open-source cross-platform debrid manager. Android, Android TV, iOS, Windows, macOS, Linux. Supports RD, TorBox, PikPak. Stremio and Trakt integration. Flutter.
- [Real Debrid Manager](https://rdm.ayush.gg/)
- [TorBox Manager](https://github.com/Echo-Storm/TorBox_Manager) - Desktop queue manager for TorBox. Torrents, magnets, hoster links, NZBs.
- [Unchained](https://github.com/LivingWithHippos/unchained-android)

## Streaming Apps
- [Seanime](https://github.com/5rahim/seanime) - (3,604★) Anime/manga media server. Desktop+Web. Supports RD, TorBox.
- [Debrify](https://github.com/varunsalian/debrify) - (292★) Unified debrid manager+Trakt. Flutter. All platforms.
- ~~[Lumera](https://github.com/lumeraapp/lumera)~~ - (193★) Android TV. Consumes Stremio addons without Stremio. ⚠️ Repo deleted.
- [Ferrite](https://github.com/Ferrite-iOS/Ferrite) - (188★) iOS. Media search engine + RD.
- PlayTorrio - Flutter. libtorrent 2.0. Stremio addons, IPTV, manga, audiobooks. RD+TorBox. 2+ yrs dev.
- DebridStream - Android/ATV. Netflix-like. v3. Multi-debrid. Profiles+PIN. r/Debrid_Stream_App.
- Odin - Self-hosted FOSS. Jackett+RD. Flutter. Multi-user. Server+ATV.
- Debrid Vault - Web. Music streaming via TorBox! Playlists, Last.fm, live lyrics. Also movies/shows/comics/audiobooks.
- Eclipse - iOS. Spotify alternative via debrid. Offline, AirPlay, AIOStreams addons. TorBox-only.
- PageTurner - iOS. Audiobook streaming via RD. Chapters, speed, sleep timer.
- Syncler - Android/ATV. v2.0. Multi-profile. Netflix UI.
- Wako - iOS/Android. RD addon + Infuse for 4K DV playback.
- Strmr - Multi-platform. RD+TorBox. r/strmr.
- Kinema - (2★) Linux KDE. Native KDE. Torrentio+RD→mpv/VLC.

<details>
  <summary>More streaming apps</summary>

  - Cyberflix - Android. RD integration.
  - Debrid'em All - Android. Stream torrents via debrid. By Yablio.
  - Unreal Debrid - Android/ATV. RD streaming. Episode tracking, intro skip. By Yablio.
  - Stremize - Multi-platform. Debrid+IPTV streaming hub.
  - Weyd - Android. Debrid streaming app.
  - DuckFlix Lite - (2★) Android TV. Netflix-like RD interface.
  - FireFlix - (3★) Fire TV. Transform Fire Stick into Netflix with RD+Kodi.
  - Omni - Apple TV/iOS. Content hub. Infuse+RD.
</details>

## Download Managers
- [pyLoad](https://github.com/pyload/pyload) - (3,777★) Download manager with 100+ host plugins. Multihoster support.
- ~~[TorrentDownloaderRD](https://github.com/torrentdownloaderrd/torrentdownloaderrd)~~ - (61★) RD/AD searcher+downloader. Desktop. ⚠️ Repo deleted.
- ~~[AllDebrid-Watcher](https://github.com/alldebrid-watcher/alldebrid-watcher)~~ - (52★) Monitors+downloads AD transfers automatically. ⚠️ Repo deleted.
- ~~[DebridDownloader](https://github.com/debriddownloader/debriddownloader)~~ - (49★) Open-source desktop downloader. ⚠️ Repo deleted.
- [OneDL](https://github.com/ellite/OneDL) - (39★) Universal CLI downloader — torrents, hosters, MEGA, HTTP(S). Supports RD, AD, Premiumize, TorBox, DebridLink.
- ~~[Mediarr](https://github.com/mediarr/mediarr)~~ - (8★) Windows CLI. RD+IMDb+TVMaze+DMM+MPV. ⚠️ Repo deleted.
- [LazyDebrid](https://onurhanak.github.io/lazydebrid/) - Terminal-based interface for managing RD torrents/downloads.
- Mipony - Download manager with multihoster integration.

## Browser Extensions
- [Magnetar](https://github.com/ArrCee76/magnetar) - (45★) Firefox+Chrome. Hash detect→RD/TB/AD/PM. Popup blocker.
- RD Chrome Extension - (31★) Chrome.
- RD Safari Extension - (16★) Safari Mac/iOS.
- DMM Res Sections - (6★) Chrome. Resolution sections for DMM.
- [RD Manager (Firefox)](https://github.com/techstacktony/real-debrid-manager) - Open-source Firefox extension for Real-Debrid management. Built with Svelte 5.
- AllDebrid Extension - Official. Chrome/Firefox/Safari.
- Debrid-Link Extension - Official. Chrome/Firefox/Edge.
- RD VLC Extension - Play magnets in VLC via RD.
- RD Utils - (5★) Chrome.
- RD Tools - (5★) Chrome.
- RD Magnet - Chromium. Magnet link handling.
- RD Raycast - (2★) macOS Raycast extension.
- Gopeed TorBox - TorBox integration for Gopeed download manager.
- instantRD Filter - Tampermonkey. DMM filter buttons (4K/1080p/DV/HDR).

## Telegram & Discord Bots

### Telegram
- unchained-bot-kotlin - (27★) RD
- alldebridBot - (3★) AD
- rdctl-bot - (1★) RD
- RD Cache Bot - RD (GitLab)
- debrid-bot - DL (production-grade, Cloudflare proxy)
- Deepbrid Bot - Official Deepbrid

### Discord
- gDebrid - (8★) Multiple services
- AllDebrid Bot - AD (top.gg)
- NyaaScraperRD - RD+Nyaa

## API Libraries
- rdcli - (147★) JavaScript. RD.
- rd_api_py - (20★) Python. RD.
- RD.NET - (14★) C#. RD.
- Real_Debrid_Toolbox - (7★) Python. RD.
- node-all-debrid - (6★) JavaScript. AD.
- go-debrid - Go. RD.
- littlejohn - Rust. Multiple services.
- deflix pkg/debrid - Go. RD/AD/PM.

## Deployment Stacks
- ~~[sailarr-installer](https://github.com/sailarr-installer/sailarr-installer)~~ - (76★) Sailarr's Guide stack installer. ⚠️ Repo deleted.
- [Naralux/mediacenter](https://github.com/Naralux/mediacenter) - (39★) RD+*Arr infinite streaming docker-compose.
- Surge - (33★) Automated deployment with Decypharr.
- ~~[TorBox-Media-Server](https://github.com/TorBox-Media-Server/TorBox-Media-Server)~~ - (21★) Zero-local-storage. TorBox WebDAV+Docker. ⚠️ Repo deleted.
- debrid-umbrel-app-store - Debrid apps for Umbrel.
- Maestro - (0★) MCP server: AI controls Stremio+RD. Pre-release.

## Comparison & Reference
- [Debrid Services Comparison](https://github.com/fynks/debrid-services-comparison) - (465★) Interactive web app comparing pricing, features, and 250+ supported hosts across all debrid services. [debridcompare.pages.dev](https://debridcompare.pages.dev)
- ~~[stremio-addons-list](https://github.com/stremio-addons-list/stremio-addons-list)~~ - (1,100★) Community addon list. ⚠️ Repo deleted.
- [StreamStack](https://streamstack.media) - 20+ apps compared, Plex/Kodi/TorBox/Infuse guides.
- [Savvy Guides](https://savvyguides.wiki) - Sailarr's Guide, Zurg, recommendations.
- [stremio-addons.net](https://stremio-addons.net) - Addon directory.
- [LeechListing](https://leechlisting.com) - Free PLG directory.
- [mymultihoster.org](https://mymultihoster.org) - English multihoster reviews.

<details>
  <summary>German-language comparisons</summary>

  - [multihosts.de](https://multihosts.de) - Updated 2026.
  - filehosterz.net
  - multio.ch - Swiss/German.
  - myfilehoster.de - 15 services.
  - beyondo.one - 24 multihosters.
  - [multihoster.org](https://multihoster.org) - German/International A-Z listing.
  - [usefulvid.com](https://usefulvid.com) - German multihoster comparison table.
  - [alternativeer.com](https://alternativeer.com) - 74 alternatives listed for debrid services.
</details>

## Communities
- [Debrid Media Manager & zurg subreddit](https://www.reddit.com/r/debridmediamanager/)
- [Real-Debrid subreddit](https://www.reddit.com/r/RealDebrid/)
- [r/TorBoxApp](https://www.reddit.com/r/TorBoxApp/) - TorBox ecosystem
- [r/StremioAddons](https://www.reddit.com/r/StremioAddons/) - Stremio addons
- [r/Addons4Stremio](https://www.reddit.com/r/Addons4Stremio/) - Stremio addon discussion
- [r/Addons4Kodi](https://www.reddit.com/r/Addons4Kodi/) - Kodi debrid addons
- [r/Piracy](https://www.reddit.com/r/Piracy/) - General (heavy debrid discussion)
- [r/Debrid_Stream_App](https://www.reddit.com/r/Debrid_Stream_App/) - DebridStream app
- [r/DebridVault](https://www.reddit.com/r/DebridVault/) - Debrid Vault + Eclipse
- [r/OnlyDebrid](https://www.reddit.com/r/OnlyDebrid/) - OnlyDebrid service
- [r/SynclerApp](https://www.reddit.com/r/SynclerApp/) - Syncler
- [r/seedboxes](https://www.reddit.com/r/seedboxes/) - Seedbox + cloud torrent discussion
- [r/DataHoarder](https://www.reddit.com/r/DataHoarder/) - Cloud torrent discussions
- [r/strmr](https://www.reddit.com/r/strmr/) - Strmr app
- [plex_debrid Discord](https://discord.gg/gDvqjjD3)
- [ElfHosted Discord](https://discord.elfhosted.com)
- [SeerrBridge Discord](https://discord.gg/seerrbridge)

## Guides and Tutorials
- [A Sailarr's Guide to Plex + Real-Debrid](https://bit.ly/puksthepirate)
- [Streaming from Real-Debrid with Plex (*on ElfHosted*)](https://elfhosted.com/guides/media/stream-from-real-debrid-with-plex/)
- [CoreLab Tech](https://corelab.tech) - DUMB+RD, AIOStreams setup guides
- [Viren070 Guides](https://guides.viren070.me) - Stremio/debrid setup
- [TROYPOINT](https://troypoint.com) - Comparisons, alternatives

## Miscellaneous
- [Awesome *Arr](https://github.com/Ravencentric/awesome-arr)
- [MultiUp](https://multiup.org) - Upload to multiple file hosts simultaneously. Heavily used in German scene.
- [Go4Up](https://go4up.com) - Multi-host upload service.

## Contribution Guidelines
Your contributions are welcome! Please refer to the [contributing guidelines](contributing.md) for information on how to contribute to this list.

## License
This list is available under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/). Feel free to share, modify, or use it as you see fit.

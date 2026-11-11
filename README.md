# awesome-debrid [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of debrid services and the apps tools and guides built around them for streaming and downloading.
Dead parked or hijacked entries are struck through and dated.

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
Debrid services give one account access to many file hosts. You can download or stream through one service
instead of managing each host yourself. They are also called multi one-click hosters or MOCHs.

Many services now finish torrents quickly and return an HTTPS link for the files. This feels like a shared
[seedbox](https://en.wikipedia.org/wiki/Seedbox). Some also handle [Usenet](https://en.wikipedia.org/wiki/Usenet)
and offer video playback. The list below records what each service supports.

## Debrid Services

### Supports Torrent + One-Click Hosters
- [AllDebrid](https://alldebrid.com/?uid=1kk5i&lang=en) - `€2.99/30d` subscription, one-time `€3.99/30d` `€8.99/90d` `€24.99/300d` — torrents, OCH (52 hosts, 18 with daily quotas, e.g. Mega 250GB). `30` active magnets documented (80 ran without error in a test), `1,000` magnets total. API limit `12 req/s` / `600 req/min`. Free trial: 7 days or 25GB, SMS check. Download links work from any IP, but datacenter IPs are blocked and VPN IPs need approval (up to 12h).
- [Debrid-Link](https://debrid-link.com/id/diG1t) - `€3/15d` `€4/30d` `€9/90d` `€16/180d` `€25/300d` — torrents (seeds for 20 days), OCH (42 hosts). `20` active torrents, `1TB` max torrent, `2,500` files per torrent, `50` uncached torrents/day (cached ones don't count), `400GB/day`. Download links work from any IP.
- [Fakir Debrid](https://fakirdebrid.net/) - `$8/7d` `$12/30d` `$30/90d` `$50/180d` `$90/yr`, or `$28` for 200GB used within a year with no daily limit — OCH (63 hosts), torrents. Plans allow `50GB` and `300` links a day, with per-host daily and weekly caps (e.g. Rapidgator 35GB/day, K2S 10GB/day). Best for niche hosters (Filejoker, K2S, Emload). Torrents come zipped and password-protected. ⚠️ Its torrent page says the torrent service is currently unavailable (Nov 2026). 4.1/5 on Trustpilot (40 reviews).
- [LinkSnappy](https://linksnappy.com/) - `$4.99/7d` `$12.99/30d` `$29.99/90d` `$54.99/180d` — OCH (~50 hosts), torrents (no seeding). Data limits on a few hosts only. Links are locked to the IP that generated them; VPN allowed. 1.3/5 on Trustpilot (338 reviews).
- [Mega-Debrid](https://www.mega-debrid.eu/) - `€4/30d` `€9/90d` `€16/180d` — OCH (100 hosts), torrent-to-DDL converter. `20` simultaneous downloads, `500GB` max torrent (auto-splits at 200GB), `100` downloads/day. Good RapidGator support. Free test quota on sign-up.
- [Offcloud](https://offcloud.com/) - `€10/mo` `€40/yr` — torrents, direct links and video sites, cloud upload to FTP/cloud storage. Sold in Jan 2026 and rebuilt by a new team; lifetime plans were ended. Shares Premiumize's torrent cache. Links work from several IPs at once.
- [Opdeb](https://www.opdeb.com/) - `€5/mo` `€20/6mo` `€35/yr` — OCH (50+ hosts), torrents, web player. Per-host daily link limits (e.g. ddownload 10/day). VPN/proxy allowed. Since 2017.
- [ProLeech](https://proleech.link/) - `~€7.60/30d` `€20/90d` `€61/yr` — OCH (50+ hosts), torrents. Per-host daily limits (e.g., Rapidgator 40GB, K2S 5GB). No file storage (proxy-only); links work only for your IP. Android app, browser extensions. 3.1/5 on Trustpilot (19 reviews).
- [Real-Debrid](http://real-debrid.com/?id=20474106) - `€3/15d` `€4/30d` `€9/90d` `€16/180d` — torrents, OCH. `100` active torrents, `2TB` max torrent, 72h to finish a download. No bandwidth cap. Links are tracked per IP and sharing gets accounts flagged; VPS/datacenter use needs paid Remote Traffic (`€3/100GB`). Refuses some releases by name since May 2026 (`451 infringing_file`).
- [RPNet](https://premium.rpnet.biz) - `$7.50/mo` — OCH (55+ hosts), magnet links, VPN included. `500GB` storage, point-based traffic (~1000 pts). Per-host daily limits (e.g., Rapidgator 50GB/day). Torrents don't cost points. Acquired by Premiumize 2022.
- ~~[BOBY](https://boby.sh)~~ - ⚠️ Dead (Nov 2026). boby.sh has no address record on Cloudflare or Google DNS, and no other trace of the service turned up.
- ~~[EasyDebrid](https://easydebrid.com/)~~ - `$4.50/mo` (sold via Paradise-Cloud) — ⚠️ Abandoned (Nov 2026). The site still takes payments, but users report the operator gone and the service not working (r/EasyDebrid, Mar and Jun 2026). Its successor Debrider is listed under Torrent + Usenet. Avoid.

<details>
  <summary>Not yet verified</summary>

  - [BestDebrid](https://bestdebrid.com/) - `€3/15d` `€5/31d` `€25/180d` `€45/yr`, `€4.50/mo` subscription — torrents (seedbox), OCH. VPN/proxy allowed. ⚠️ Scam reports on Reddit; 3.7/5 on Trustpilot from only 12 reviews.
  - [Zevera](https://www.zevera.com/) - pricing page errors out (Nov 2026) — torrents ("Instant Torrent"), cloud import. Relaunched by a new team. ⚠️ 1.1/5 on Trustpilot (141 reviews), not in major comparison guides.
</details>

### Supports Torrent + Usenet
Everything here also takes NZBs; most also unlock one-click hosters.

- [Cocoleech](https://cocoleech.com/) - `$14.99/31d` `$29.99/90d` `$79.99/yr` (one-time, no auto-renewal) — OCH, magnets, Usenet, includes VPN. Per-hoster daily quotas (shown in your account). Accepts card, PayPal, crypto, Paysafecard.
- [DASAN](https://dasan.co) - pay-per-GB, no expiry: `$2.99/35GB` to `$50/2TB`, torrent/Usenet-only `$21/1TB` — torrents, Usenet, OCH (40+ hosts), 600+ video sites. Torrents and Usenet cost 30% less volume. Free: one job up to 500MB per day, no account. `100GB` max file, `10-day` file retention. JDownloader plugin.
- [Deepbrid](https://www.deepbrid.com/) - `€4.50/14d` `€4.99/30d` `€12.99/90d` `€19.99/180d` `€32.99/yr` — torrents, Usenet, OCH (80+ hosts). `50` active torrents, `200GB` max download, unlimited bandwidth. Free tier (5 links/day). VPN allowed for premium. Own Stremio addon with a Usenet mode; users report it much improved in 2026 after an unreliable 2025.
- [High-Way](https://high-way.me/) - `€6.99/mo` `€9.99/mo` `€14.99/mo` `€69/yr` `€99/yr` `€149/yr`, one-time traffic `€9.99/250GB` with no expiry, free tier — torrents, Usenet (25 connections, 50 on Unlimited), OCH (19 hosts), TV recorder for 34 German channels. Monthly file-host traffic `200GB`/`1TB`/fair use (Basic/Pro/Unlimited), counted with a per-host factor; with a subscription, Usenet, torrents and TV don't count. One-time traffic without a subscription also pays for Usenet, torrents and TV, allows `10` active transfers and deletes finished downloads after 2 weeks. `500GB`/`1TB`/`2TB` cloud storage, `300GB` max torrent, `20`/`40`/`80` active transfers. WebDAV, SFTP and a transfer API. German-language; sign-ups are reviewed by hand.
- [premium.to](https://premium.to/) - volume-based `€5/125GB` `€10/300GB` `€25/850GB`, or `€25/1500GB` Usenet + 5-host traffic (no expiration) — torrents, Usenet (4,000 days retention), OCH (8 hosts). Torrents cost ~40% of file size from volume (20% add + 20% download). Multi-IP and simultaneous sharing allowed. Bitcoin accepted.
- [Premiumize](https://www.premiumize.me/) - `€9.99/mo` `€69.99/yr` — torrents, OCH (37 hosts), Usenet (still works, no longer advertised). `1TB` cloud storage. Fair use: `1,000`-point pool, 1 point = 1GiB downloaded (some hosters cost ×2–5). API keys and links work from any IP.
- [TorBox](https://torbox.app/subscription?referral=74ffa560-7381-4a18-adb1-cef97378c670) - **free tier available** `$3/mo` `$5/mo` `$10/mo` `$33/yr` — torrents, Usenet (Pro only), OCH/web downloads (paid plans). `1/3/5/10` active slots by tier (Free/Essential/Standard/Pro), `10GB/200GB/200GB/1TB` max download size. Free: 10 downloads/month, 24h cooldown, no private torrents. No IP restrictions. Has a [dynamic abuse system](https://support.torbox.app/en/articles/10336778-the-torbox-abuse-system) — usage above the 99th percentile triggers warnings (3 warnings then ban). Abuse floors: Free `5TB/mo`, Essential `10TB/mo`, Standard `20TB/mo`, Pro `30TB/mo`. Cached transfers don't count.
- [Torrin](https://torrin.app/) - free 3-day trial / `$2.99/mo` `$5.99/mo` `$11.99/mo` — torrents, OCH (1fichier, Rapidgator, Mega), Usenet through your own provider. `1/2/4/8` downloads at a time, `50GB/100GB/250GB/1TB` max size by tier. Built-in Stremio addon, Kodi plugin, WebDAV and browser player. Open source and self-hostable ([GitHub](https://github.com/torrin-app/torrin), 125★). New in 2026.
- [TransferCloud](https://transfercloud.io) - free (files under 1.5GB) / `$5.99-$15.99/mo` — torrents, Usenet (NZB), direct links, 100+ video sites. `1-10` concurrent downloads, `50GB-2TB` max torrent by tier. Sends files to Google Drive, Dropbox, OneDrive and 25+ other clouds.
- ~~[Debrider](https://debrider.app)~~ - Free trial / `$4.50/mo` `$10/mo` — torrents, Usenet, OCH. EasyDebrid's successor, same operator. ⚠️ Avoid (Nov 2026): the site still sells plans, but users call both services abandoned (r/EasyDebrid, Mar 2026).
- ~~[Furk.net](https://furk.net)~~ - `€9.90-€14.90/mo` — torrents, Usenet, streaming. Operating since 2009. ⚠️ Dead (Nov 2026). DNS resolves, but the server times out from Germany (home and datacenter) and from a browser; unreachable since at least May 2026.

### Supports Torrent Only
- [PikPak](https://mypikpak.com/) - `$6.3/mo` `$63.99/yr` — torrents, magnets, URLs and social-media links. `10TB` storage, `40TB/mo` cloud download, `4TB/mo` downstream bandwidth. WebDAV, Telegram bot, TV app. Xunlei's overseas rebrand.
- [put.io](https://put.io/) - `$0.99` 1-day trial / `$9.99/mo` `$99/yr` (100GB) `$19.99/mo` `$199/yr` (1TB) — torrents, direct URLs. `10/50` active transfers, seeds on private trackers to ratio 2 (100GB plan) or 20 (1TB plan). Family sharing on the 1TB plan. No PayPal.

### Cloud Torrent Services
- [Seedr](https://seedr.cc) - free 2GB / `€7.95/mo` (50GB) `€12.95/mo` (500GB) `€19.95/mo` (2TB) — Chrome extension, in-browser player, WebDAV, Plex/Jellyfin/Roku. Over 2M users.
- [ZbigZ](https://zbigz.com) - free, no sign-up to try / premium (2TB storage, no speed or size limits) — paste a magnet or .torrent, watch in the browser while it downloads or save over HTTPS.
- [Bitport.io](https://bitport.io) - free 1GB / from `$5/mo` (75GB) to `$15/mo` (1TB), billed yearly — online streaming on every plan, Google Drive sync, API.
- [Torcomet](https://torcomet.com) - free 2GB / `$39.99/yr` (1000GB) — upload a .torrent or magnet, download via HTTPS.
- [MultCloud](https://www.multcloud.com) - free 5GB/mo transfer / `$19.99/mo` (100GB) or `$59.99/yr` (1200GB) — "Remote Upload" accepts magnets/.torrent → saves to 30+ cloud services (GDrive/Dropbox/MEGA/OneDrive).
- [FilePax](https://filepax.net) - 6GB free trial, up to 10TB premium — PikPak-adjacent (PaxCloud Limited). WebDAV, Telegram bot, auto video transcoding.
- [SonicBit](https://sonicbit.net) - free 4GB / from `$1.99/mo` (50GB) to `$14.99/mo` (1TB) — cloud torrents with seeding and unlimited traffic on every plan; one-click Plex, Jellyfin, Sonarr and other apps on your storage.
- [Magnet.diy](https://magnet.diy) - free 2.5GB / `$2.99` (30GB for 3 months), one-time crypto payment — private cloud torrent downloader; your IP never reaches peers.
- [TorrentSafe](https://torrentsafe.com) - free (1GB max file) / from `$2.49/mo` (4-year) to `$6.49/mo` — anonymous cloud torrent client, sync to cloud storage.

<details>
  <summary>More cloud torrent services</summary>

  - [SonicSeedBox](https://sonicseedbox.com) - free 4GB / from `$2.15` (20GB) to `$14.95` (500GB) — converts torrents to HTTPS DDL, remote upload to Google Drive, OneDrive, Dropbox, pCloud.
  - [MaxCloudBox](https://maxcloudbox.com) - from `$1/3 days` (20GB) to `$24.68/90 days` — cloud torrent + seedbox, NVMe storage, WebDAV, auto-sync to Google Drive/MEGA.
  - ~~[TorSnatch](https://torsnatch.com)~~ - ⚠️ Dead (Nov 2026). Site says "currently unavailable" and points to partner mobile apps.
  - ~~[Megabox](https://megabox.me)~~ - ⚠️ Dead (Nov 2026). Domain now redirects to a gambling site.
  - ~~[ApexDrive](https://newapexdrive.com)~~ - now redirects to myapexdrive.com, a private photo/file cloud with no torrent or remote download features advertised. ⚠️ Removed (Nov 2026).
  - ~~[TorrentDrive](https://torrentdrive.io)~~ - ⚠️ Dead (Nov 2026). Domain no longer resolves.
  - ~~[CloudPipe](https://cloudpipe.io)~~ - fetches to Google Drive. ⚠️ Dead (404).
  - ~~[ByteBx](https://bytebx.com)~~ - ⚠️ Dead (parked domain).
  - ~~[FileStream.me](https://filestream.me)~~ - ⚠️ Dead (domain no longer resolves).
  - ~~[Fuge.it](https://fuge.it)~~ - ⚠️ Dead (410 Gone).
</details>

### Torrent-to-DDL Converters
- [Webtor.io](https://webtor.io) - free (speed-limited), paid plans for full speed and Vault storage, no registration — stream or download any file in a torrent from the browser, whole torrent as ZIP, WebDAV library, REST API. [Self-hostable](https://github.com/webtor-io/self-hosted).
- [Instant.io](https://instant.io) - free — WebTorrent in the browser; streams from WebRTC peers only. [Open source](https://github.com/webtorrent/instant.io) (3,598★).
- [DirectTorrent.me](https://directtorrent.me) - free 15GB/day / paid 100-300GB/day or pay per GB — torrent, magnet and Mega.nz links to direct downloads, in-browser streaming, up to 150GB per torrent.
- [Bitso.ir](https://bitso.ir) - paid (by disk space, unlimited traffic) — Iranian service. Torrent to direct link, seedbox for private trackers, remote upload to Google Drive/FTP.
- ~~[Direct-Torrents](https://direct-torrents.com)~~ - ⚠️ Dead (Nov 2026). Domain now redirects to speedtorrent.com, a torrent index.

### Supports One-Click Hosters Only
<details>
  <summary>Not what we want, but sure...</summary>

  - [Boxbit.app](https://boxbit.app) - from `€9.99/mo` — 40 hosts incl. K2S, FileJoker, Rapidgator. No published limits. Covers hosters RD doesn't.
  - [CboxEra](https://www.cboxera.com/) - free 25GB/day / `$7/30d` `$13/60d` `$19/90d` (150GB/day) — 50+ hosts.
  - [Cooldebrid](https://cooldebrid.com/) - 63 hosts.
  - [Daily Leech](https://dailyleech.com/) - free account + premium — fresh daily quota, chat-style downloader.
  - [Debridly](https://debridly.com) - `$1.89/2d` `$3.99/7d` `$7.99/30d` `$18.99/90d` `$49.99/yr` (one-time) — 95 hosts, no torrents. Daily cap per host (e.g. Rapidgator 40GB, Mega 100GB, K2S 3GB); links last 24h. New (domain registered Apr 2026), no reviews yet.
  - [DebridItalia](https://www.debriditalia.com/) - 24 hosts. `€21.90/yr` promo.
  - [GeT24](https://get24.org/) - free account + plans — dozens of hosts, EU servers, pay by BLIK, card or crypto.
  - [Juba-Get](https://juba-get.com/) - free + premium — 117+ hosts. Running 10+ years.
  - [Leechall](https://leechall.io/) - paid.
  - [MultiDebrid](https://multidebrid.com) - `$15/30d` `$100/yr` — 52 hosts.
  - [MyDebrid](https://mydebrid.com/) - `$9/mo` — dozens of hosts. 7-day refund.
  - [NeoDebrid](https://neodebrid.com/main) - free account / `€9.99/mo`.
  - [OnlyDebrid](https://onlydebrid.com) - `$6.99/yr`, 50+ hosts. Very cheap.
  - [Prembox](https://prembox.com) - pay-per-package, 40+ hosts, free test transfer. Running 12+ years.
  - [RapidGrab](https://rapidgrab.ovh/) - free — 10GB, 1GB max file.
  - [Simply-Premium](https://simply-premium.com) - from `€5.83/mo`, 19 hosts + Usenet + torrents. Since 2009.
  - [Storage Portal](https://storage-portal.com) - pay-as-you-go from `$1.50` (5GB), no monthly fee — 50+ hosts. JDownloader support.
  - [Vecwire](https://get.vecwire.com) - free (5 links/day on free hosts) + premium (Rapidgator, Nitroflare, K2S, Hot4share).
  - ~~[Ddebrid/Filemium](https://ddebrid.com)~~ - redirects to Filemium. French. ⚠️ Dead.
  - ~~[Debrid.xyz](https://debrid.xyz)~~ - 40 hosts. Spain-based. ⚠️ Dead.
  - ~~[EasyBytez](https://easybytez.com)~~ - ⚠️ Dead.
  - ~~[Grab8](https://www.grab8.com/)~~ - ⚠️ Dead (domain for sale).
  - ~~[Linkifier](https://linkifier.com)~~ - `$9.99/mo`, 9+ major hosts. ⚠️ Dead.
  - ~~[MultiShare](https://www.multishare.cz/en/)~~ - Czech. ⚠️ Dead (Nov 2026, domain no longer resolves).
  - ~~[Prem.link](https://prem.link)~~ - cloud storage + debrid. ⚠️ Domain hijacked.
  - ~~[Simply Debrid](https://simply-debrid.com/)~~ - pivoted to generic video downloader, no longer a debrid service
  - ~~[SMOOZED](https://www.smoozed.biz/)~~ - flagged as scam on GitHub/Tarnkappe.info
  - ~~[Superloading](https://superloading.com)~~ - 24 hosts. ⚠️ Dead (parked domain).
</details>

### Regional Multihosters

<details>
  <summary>Poland 🇵🇱 — 15+ services (richest non-English ecosystem)</summary>

  - [Filebit.pl](https://filebit.pl) - 46 hosts. From 7.99 zł, time or transfer-based pricing.
  - [Rapideo.net](https://rapideo.net) - 57 hosts. 1GB free to start. Since 2009.
  - [TwojLimit.pl](https://twojlimit.pl) - 60 hosts, from 2 zł, up to 5GB free transfer. Chrome extension, JDownloader support.
  - [tb7.pl](https://tb7.pl) - 10GB/24h (rolls over up to 40GB), from 4.99 zł. pyLoad plugin support.
  - [Xt7.pl](https://xt7.pl) - 20GB/24h (rolls over up to 80GB), from 29.99 zł. Built on tb7's infrastructure.
  - [Nopremium.pl](https://nopremium.pl) - 57+ hosts, 1GB on sign-up, transfer from 2.99 zł (2GB). Synology plugin.
  - [Rapids.pl](https://rapids.pl) - transfer packs from 2 zł (5GB).
  - [RapidTraffic.pl](https://rapidtraffic.pl)
  - [Pobierz.biz](https://pobierz.biz)
  - [Rapidox.pl](https://rapidox.pl) - pay per transfer, no account fees. Only 30% of transfer counted 02:00-08:00.
  - [Zapisz.se](https://zapisz.se) - pay only for the GB you use, per-host rates shown before download.
  - [Pliko.pl](https://pliko.pl)
  - [Rapidb.it](https://rapidb.it) - 10 hosts.
  - [DropX](https://dropx.to) - 7 hosts.
  - [Turbix.pl](https://turbix.pl)
  - [Rapids24.pl](https://rapids24.pl)
  - ~~[RapidGrab.pl](https://rapidgrab.pl)~~ - now redirects to Rapideo.net.
  - ~~Fastfiles.pl~~ - ⚠️ Dead.
  - ~~Easyfiles.pl~~ - ⚠️ Dead.
</details>

<details>
  <summary>Czech Republic 🇨🇿</summary>

  - [Esoubory.cz](https://esoubory.cz) - JDownloader support
  - ~~[Superload.cz](https://superload.cz)~~ - partners with Webshare, Fastshare, Edisk, Turbobit. ⚠️ Dead (410 Gone).
  - ~~[Stahomat.cz](https://stahomat.cz)~~ - ⚠️ Dead (domain no longer resolves).
  - ~~[Multishare.cz](https://multishare.cz)~~ - JDownloader + pyLoad support. ⚠️ Dead (domain no longer resolves).
</details>

<details>
  <summary>Brazil 🇧🇷</summary>

  - [Baixarpremium.net](https://baixarpremium.net)
  - [ComprarPremium](https://comprarpremium.com) - sister site of Baixar Premium.
  - [Conexaomega.com](https://conexaomega.com) - 26 hosts.
  - [SuperLinksBR](https://superlinksbr.com) - 20+ hosts. From R$7.90.
  - [Contas Turbo](https://contasturbo.com) - 20+ hosts, one plan. Chrome extension.
  - [Links Premium](https://linkspremium.com.br) - 45+ hosts. From R$39.90.
  - ~~[Libera Premium](https://liberapremium.com)~~ - ⚠️ Dead (Nov 2026, domain expired).
  - ~~[Megarapido.net](https://megarapido.net)~~ - ⚠️ Dead.
  - ~~[Multivip.net](https://multivip.net)~~ - ⚠️ Dead.
  - ~~[Superdown.com.br](https://superdown.com.br)~~ - JDownloader support. ⚠️ Dead (domain now serves a webmail login).
</details>

<details>
  <summary>Other Regional</summary>

  - [Transload.me](https://transload.me) 🇷🇺 - primary Russian debrid, 20 hosts.
  - [Linksvip.net](https://linksvip.net) 🇻🇳 - Fshare, 4share and more.
  - [Fshare](https://fshare.vn) 🇻🇳 - #1 Vietnamese file hosting. FPT Telecom-owned. VIP from `$2.40/mo`.
  - [4share.vn](https://4share.vn) 🇻🇳 - Vietnamese file sharing, now pitched as backup storage; site says the service is being upgraded.
  - [Coc Coc Browser](https://coccoc.com) 🇻🇳 - only Asian browser with native torrent downloading built in.
  - [ShareBox](https://sharebox.co.kr) 🇰🇷 - Korean webhard (paid file sharing) in cloud torrent discussions.
  - [Webhard](https://webhard.co.kr) 🇰🇷 - paid file hosting (웹하드). Korean-unique model.
  - ~~[Fastix.ru](https://fastix.ru) 🇷🇺~~ - JDownloader support. ⚠️ Dead (domain for sale).
  - ~~[TotalDebrid](https://totaldebrid.org) 🇫🇷~~ - ⚠️ Dead (parked domain).
  - ~~[Abracadebrid](https://abracadebrid.com) 🇫🇷~~ - ⚠️ Dead (410 Gone).
  - ~~[ExtreamRapid](https://extreamrapid.com)~~ - ⚠️ Dead (parked domain).
  - ~~[Tenlua](https://tenlua.vn) 🇻🇳~~ - ⚠️ Dead.
</details>

### Chinese Cloud Torrent Services

PikPak is widely reported to be a Xunlei spin-off for overseas markets (Xunlei has never confirmed it). The Chinese "offline download" (离线下载 / 云下载 / 云添加) ecosystem is massive and largely unknown in Western debrid circles. Most of these need a mainland phone number and Chinese payment.

<details>
  <summary>Chinese services</summary>

  - [115](https://115.com) - free 15GB, no cloud download / `¥300/yr` (~$42) VIP, no storage / `¥500/yr` (~$70) VIP + 50TB permanent — "King of offline downloads." Annual VIP gets 1,500 cloud downloads/mo, up to 500GB each. Needs Chinese phone.
  - [Xunlei Cloud](https://pan.xunlei.com) - free 10GB, 0-3 cloud adds/day / Super Member `¥360/yr` (~$50) list — 10TB, 500 cloud adds/day, 2TB/mo fast retrieval. China's largest P2P network. Login accepts international numbers.
  - [Guangya Cloud (光鸭云盘)](https://www.guangyapan.com) - free 2TB / from `¥480/yr` (~$67) list, `¥108` first year at launch — Xunlei's new drive (2026). Batch cloud-add of magnet, ed2k and HTTP links (3/day free), up to 500TB on paid plans. SMS login with a mainland number only.
  - [Quark](https://pan.quark.cn) - free 10GB (throttled) / SVIP up to 6TB — Alibaba-owned. Magnet, ed2k and .torrent offline download. Needs Chinese (+86) phone.
  - [Baidu Pan](https://pan.baidu.com) - 2TB free, SVIP `¥298/yr` (~$42) list (5TB) — largest user base. Cloud add (离线下载) of links and torrents; free users earn adds by watching ads. Severely throttled on free.
  - [BitQiu](https://pan.bitqiu.com) - free 20GB, no cloud download / SVIP `¥298/yr` (~$42), 6TB — "Southern 115." Cloud download is members-only (not on iOS).
  - [123 Cloud](https://123pan.com) - free 2TB "standard" + 50GB "professional" space, 10GB/mo download traffic / VIP 18TB, SVIP 98TB — no speed cap for anyone. HTTP and magnet offline download. WebDAV.
  - [Weiyun](https://weiyun.com) - free 5GB, no offline download / SVIP `¥30/mo` (~$4), 6TB — Tencent. 40-75 offline downloads/day (links or .torrent) for SVIP; not on iOS.
  - [TeraBox](https://terabox.com) - 1TB free — Baidu international. Remote upload (magnet/torrent) removed in 2023, with no plans to return.
  - ~~[Guangniao](https://pan.gny.net)~~ - ⚠️ Dead (Oct 2026). Database breached and wiped; the company is closing and offering partial refunds.
</details>

### Free Premium Link Generators

> **Scam Warning:** MaxDebrid, HotDebrid, YouDebrid, OkDebrid and AnyDebrid all pitch "free unlimited premium links" (100+ hosts). Trustpilot reviewers describe the same routine on each: page after page of ads, then a file of the right size that will not open. DebridLeech and PrimeLeech share one 228-host template; their reviewers report fake human verification and offer walls with no file at the end. Avoid them all.

<details>
  <summary>Free PLGs</summary>

  - [World-Debrid](https://world-debrid.com) 🇫🇷 - free, 70+ hosts plus torrents/magnets.
  - [MixDebrid](https://mixdebrid.com) - 100+ hosts. Refuses non-residential IPs (VPN/datacenter).
  - [UploadedPremiumLink](https://www.uploadedpremiumlink.net) - free ad-supported, 15GB/day traffic. IP-locked links.
  - [JetLeech](https://jetleech.net) - 42 hosts, 1GB, 40/day
  - [GigaLeecher](https://gigaleecher.com) - Uploaded, Rapidgator, DepositFiles, FileFactory and more.
  - [AlemdarLeech](https://alemdarleech.net) - Turkish CBox.
  - [Leech Space](https://leech.space) - directory/PLG
  - [TurkDown](https://turkdown.com) - 33 hosts, free, torrent section. Hoster list outdated (includes defunct hosts).
  - [VNZLeech](https://vnzleech.com) - 43 hosts, 10GB — Vietnamese.
  - [KingOfDown](https://kingofdown.com) - 21 hosts, 2GB, 3hr cooldown.
  - [MultiLeech](https://multileech.net) - CBox, 20 hosts.
  - [PremiumLinkGenerator.com](https://premiumlinkgenerator.com) - free. The bare domain bounces through a vk.com redirect to ww.premiumlinkgenerator.com.
  - ~~[AnyDebrid](https://anydebrid.com/)~~ - see the scam warning above.
  - ~~[DebridLeech](https://debridleech.com)~~ - see the scam warning above.
  - ~~[PrimeLeech](https://primeleech.com)~~ - see the scam warning above.
  - ~~[UpDebrid](https://updebrid.com/)~~ - ⚠️ Dead (Nov 2026, parked domain).
  - ~~[LeechNinja](https://leechninja.com)~~ - ⚠️ Dead (Nov 2026). Domain now redirects to ad spam.
  - ~~[Debrid-File](https://debrid-file.com)~~ - ⚠️ Dead (Nov 2026, parked domain).
  - ~~[HyperDebrid](https://hyperdebrid.com)~~ - ⚠️ Dead (Nov 2026, domain for sale).
  - ~~[Downloader.guru](https://downloader.guru)~~ - ⚠️ Dead (Nov 2026, domain no longer resolves).
  - ~~[Prem](https://prem.link)~~ - 80+ hosts. ⚠️ Domain hijacked (redirects to ad networks).
  - ~~[BackupPremium](https://backuppremium.com)~~ - 50+ hosts. ⚠️ Dead.
  - ~~[Uppremium](https://uppremium.link)~~ - 50+ hosts, 5GB, 5/day. ⚠️ Dead.
  - ~~[PremiumLeech](https://premiumleech.eu)~~ - 3 hosts, 1GB. ⚠️ Dead.
  - ~~[GetLinkPro](https://getlinkpro.com)~~ - ⚠️ Dead.
</details>

### Self-Hosted Cloud Torrent
Deploy on any VPS to run your own cloud torrent service. Free (open source) — only pay for hosting.

- [TorrServer](https://github.com/YouROK/TorrServer) - (3,185★) Go — torrent stream server: play files while they download, through the web UI, players or Smart TVs. Optional DLNA server. Builds for Linux, Windows, macOS and Android; Docker.
- [Cloud Torrent](https://github.com/jpillora/cloud-torrent) - (6,247★) Go — self-hosted remote torrent client: add magnets or .torrent files, download to the server, browse and stream the files over HTTP. Built-in torrent search. 2025–26 ground-up rewrite (Vue 3 UI, single binary); Linux, macOS and Windows binaries.
- [Webtor (self-hosted)](https://github.com/webtor-io/self-hosted) - (718★) all-in-one Docker image of webtor.io — direct download links for any file in a torrent, instant audio/video streaming, whole torrent as ZIP, personal library, OpenSubtitles, Stremio addon.
- [Torrin](https://github.com/torrin-app/torrin) - (125★) Go — open-source debrid you host yourself: add a magnet, NZB or hoster link and stream it over HTTPS; downloads run behind a VPN and land in S3-compatible storage. Stremio addon, WebDAV, web UI, RSS. Hosted instance at [torrin.app](https://torrin.app).
- [BitPlay](https://github.com/aculix/bitplay) - (1,717★) Go — stream video from magnets or .torrent files in the browser. MKV remuxed on the fly, audio track picker, subtitles, SOCKS5 proxy, Prowlarr/Jackett search, optional basic auth. Docker.
- [RapidBay](https://github.com/hauxir/rapidbay) - (903★) Python — search via Jackett/Prowlarr, pick a file, and it downloads and converts it to play in any browser or cast to Chromecast/Apple TV. Kodi support, automatic subtitles and disk cleanup.
- [peerflix-server](https://github.com/asapach/peerflix-server) - (1,313★) Node.js — streaming torrent client with a web UI. Docker.
- [Seedbox Lite](https://github.com/hotheadhacker/seedbox-lite) - (4,533★) Node.js/React — Netflix-style torrent streaming UI with instant playback. Docker. Non-commercial license.
- [Torranor](https://github.com/Zhoros/Torranor) - (80★) Go — downloads a torrent on the server and streams it straight to your browser as a normal download; seeds for a set time, then deletes the files. Docker.
- [Exatorrent](https://github.com/varbhat/exatorrent) - (1,967★) Go — self-hostable torrent client with web UI; stream files in the browser or a media player. Archived (May 2025).
- [Simple Torrent](https://github.com/boypt/simple-torrent) - (975★) Go — fork of Cloud Torrent with RSS and a mobile-friendly UI. Archived (Jul 2024); Cloud Torrent above is maintained again.
- [Autolycus](https://github.com/algofly-oss/autolycus) - (39★) Seedr-style web app: your server downloads the torrent, then you stream or download the files from the browser, including zipped folders. FTP browsing. Docker. (Earlier repo: [imneonizer/autolycus](https://github.com/imneonizer/autolycus), 136★, last push Feb 2025.)

### Hosting Providers (VPS, Seedbox..)

- [ElfHosted](https://elfhosted.com/) - from `$9/mo`, 7-day trials for `$1` — managed Stremio addons with bundled TorBox and Usenet accounts (from `$9/mo`), full Plex/Jellyfin/Emby stacks with debrid storage (from `$19/mo`), and standalone [Zurg](https://store.elfhosted.com/product/zurg/) (`$19/mo`) or NzbDav (`$9/mo`). The old "Infinite Streaming" bundle is discontinued.

## *Arr Stack & Automation
- [rdt-client](https://github.com/rogerfar/rdt-client) - (1,599★) Drop-in torrent client replacement for *arr. Implements a fake qBittorrent API so you can hook up Sonarr, Radarr or Couchpotato, and downloads finished files to your machine. Supports RD, AllDebrid, Premiumize, TorBox, Debrid-Link and HIGHWAY; NZBs on TorBox, Premiumize and HIGHWAY.
- [Decypharr](https://github.com/sirrobot01/decypharr) - (925★) Go-based media gateway for debrid and Usenet. Mock qBittorrent and SABnzbd APIs for Sonarr/Radarr/Lidarr, direct Usenet streaming over NNTP, optional NFS/SMB shares. Supports RD, TorBox, AllDebrid, Debrid-Link, Premiumize.
- [DUMB](https://github.com/I-am-PUID-0/DUMB) - (497★) Distributed Unlimited Media Bridge — AIO Docker platform that installs and wires Riven, CLI Debrid, Decypharr, Zurg, rclone, AIOStreams, the *arrs, Plex, Jellyfin, Emby and more from one dashboard. Supersedes pd_zurg and DMB (both archived).
- [CineSync](https://github.com/sureshfizzy/CineSync) - (374★) Organize debrid and local libraries with symlinks, no Sonarr/Radarr needed. Web UI, RD and TorBox mounts, RD repair.
- [Riven](https://github.com/rivenmedia/riven) - (821★) All-in-one media automation: list polling, indexer search, debrid integration, symlink creation, media server management. Supports RD, AllDebrid. Last release Aug 2025; a TypeScript rewrite ([riven-ts](https://github.com/rivenmedia/riven-ts)) is in progress. Formerly known as Iceberg.
- [SeerrBridge](https://github.com/Woahai321/SeerrBridge) - (308★) Browser automation bridging Jellyseerr/Overseerr with Debrid Media Manager. Listens to movie/TV requests via webhook and auto-fetches through DMM.
- [CLI Debrid](https://github.com/godver3/cli_debrid) - (196★) Watches your lists, picks the best cached release and keeps Plex, Jellyfin or Emby up to date. Supports RD, TorBox, AllDebrid, Premiumize, Debrid-Link and Usenet. One of plex_debrid's successors.
- [DebriDav](https://github.com/skjaere/DebriDav) - (158★) Kotlin app that emulates the qBittorrent and SABnzbd APIs and exposes debrid files over WebDAV, with fallback between providers. Supports RD, Premiumize, TorBox, Easynews.
- [InfiniDysk](https://github.com/infinidysk/infinidysk) - (280★) NzbDAV's successor, rewritten in Rust (2.0 beta). Sonarr/Radarr add it as a SABnzbd download client; it never downloads the release and streams the files from Usenet over a FUSE mount or WebDAV. Docker.
- [AltMount](https://github.com/kipsilabs/altmount) - (323★) Go WebDAV server backed by Usenet. SABnzbd-compatible API for the *arrs, streams from inside RAR/7z sets (including password-protected ones), symlinks or .strm files, health checks with automatic repair, and Stremio stream URLs from an uploaded NZB.
- [NzbDAV](https://github.com/nzbdav-dev/nzbdav) - (1,191★) The original Usenet WebDAV server: mounts NZBs without downloading, streams and seeks inside RAR/7z, SABnzbd-compatible API for Sonarr/Radarr. No longer maintained (Sep 2026); its README points to InfiniDysk, NzbDavEx and AltMount.
- [NzbDavEx](https://github.com/qooode/nzbdavex) - (124★) NzbDAV fork with failover across several NNTP providers, an indexer manager and a watchdog that re-checks and re-fetches broken files.
- [Premiumizearr-Nova](https://github.com/ensingerphilipp/Premiumizearr-Nova) - (44★) Blackhole download client that sends .magnet, .torrent and .nzb files from Sonarr, Radarr and Lidarr to Premiumize and pulls the results down. Pauses when the fair-use quota runs out. Maintained fork of the archived Premiumizearr.
- [ListSync](https://github.com/Woahai321/list-sync) - (342★) Automates importing media from lists (Trakt, IMDb, etc.) into Jellyseerr/Overseerr. Companion to SeerrBridge.
- [TorBoxarr](https://github.com/MrJoiny/TorBoxarr) - (22★) Pretends to be qBittorrent or SABnzbd so Sonarr/Radarr can use TorBox as a download backend; pulls finished files to local storage.
- [qBitdebrid](https://github.com/akhil-rana/qbitdebrid) - (18★) Downloads cached TorBox files inside qBittorrent through web seeds.
- [alfred](https://github.com/Pukabyte/alfred) - (54★) Symlink manager for RD and the *arr ecosystem.
- [Patbrid](https://github.com/mgoodings/patbrid) - (30★) RD blackhole + aria2. Unmaintained since 2023.
- [Babysitarr](https://github.com/DAdjadj/Babysitarr) - (27★) Self-healing daemon for Radarr/Sonarr + RD setups (Zurg + Decypharr): unsticks downloads, breaks grab loops, re-searches expired files.
- [n8n-nodes-torbox](https://github.com/Automations-Project/n8n-nodes-torbox) - (9★) TorBox for n8n workflows: torrents, Usenet, web downloads.
- [Pachelarr](https://github.com/northernpowerhouse/pachelarr) - (13★) Proxy between Prowlarr and the *arrs that pushes results already cached on TorBox to the top.
- [Vadarr](https://github.com/Woahai321/Vadarr) - (0★) IMDB/Trakt/AniList → Overseerr → DMM+RD. No *arr needed.
- ~~[plex_debrid](https://github.com/itsToggle/plex_debrid)~~ - (1,650★) Archived. Development continues in [DMM's fork](https://github.com/debridmediamanager/plex_debrid) (26★). Alternatives: Riven, Decypharr, CLI Debrid.
- [Cinephage](https://github.com/Cinephage/Cinephage) - (898★) One self-hosted app in place of Sonarr, Radarr, Prowlarr, Bazarr and Overseerr. Sends releases to RD or TorBox (or qBittorrent, SABnzbd, NZBGet), streams Usenet NZBs without downloading them, writes .strm files, has live TV. Docker.
- [Shelfmark](https://github.com/calibrain/shelfmark) - (4,107★) Self-hosted book and audiobook search and request tool. AllDebrid, Real-Debrid, TorBox or Debrid-Link work as download clients next to torrent and Usenet clients; imports into Calibre, Calibre-Web or Audiobookshelf.
- [Mydia](https://github.com/getmydia/mydia) - (805★) Self-hosted movie and TV manager in the Sonarr/Radarr mould, with RD, AD, PM and TorBox as download clients. Early development (0.x).
- [Narratarr](https://github.com/narratarr/narratarr) - (103★) *arr-style audiobook manager with a built-in player. Free LibriVox and Old-Time Radio books, plus AudiobookBay torrents fetched through RD, AD, TorBox or PM.
- [westsurname/scripts](https://github.com/westsurname/scripts) - (164★) Python scripts for the *arrs: an RD and TorBox torrent blackhole, symlink repair, import of torrent folders, cleanup of broken links.
- [plundrio](https://github.com/elsbrock/plundrio) - (48★) put.io download client for Sonarr, Radarr and Lidarr (speaks Transmission RPC). Adds transfers to put.io and downloads finished files to disk.
- [putioarr](https://github.com/wouterdebie/putioarr) - (51★) Rust proxy that lets Sonarr, Radarr and Whisparr use put.io as a Transmission download client.
- [Mediarium](https://github.com/rdborg/Mediarium) - (294★) One self-hosted app in place of Radarr, Sonarr, Prowlarr, SABnzbd, a torrent client and Bazarr, for movies, TV, music, ebooks and audiobooks. RD, TorBox or Premiumize can download torrents instead of the built-in client, and Mediarium fetches the finished files over HTTPS. Docker; new (Sep 2026).
- [ddlarr-suite](https://github.com/z-m-g/ddlarr-suite) - (14★) French. Torznab indexer for French direct-download (DDL) sites plus a stand-in qBittorrent client, so Sonarr and Radarr can grab DDL releases; hoster links are unlocked through AllDebrid, RD or PM, and real torrents can go to the same services. Docker.
- [SchröDrive](https://github.com/moderniselife/SchroDrive) - (8★) Takes Overseerr requests, searches Prowlarr or Jackett and adds the chosen release to your debrid service, for an rclone mount that Plex, Jellyfin or Emby read. TorBox, RD and AD tested; PM, DL, Deepbrid, Offcloud, put.io, Mega-Debrid, Seedr and PikPak written but untested.
- [Easynews as Indexer](https://github.com/Sanket9225/Easynews_as_indexer) - (82★) Turns Easynews search into a Newznab-style indexer you add to Prowlarr, so the *arrs can grab NZBs from Easynews. Docker. By the UsenetStreamer author.

## Stremio Addons
- [AIOStreams](https://github.com/Viren070/AIOStreams) - (3,096★) Puts your Stremio addons, debrid services and Usenet into one filtered, sorted list. Built-in scrapers, add any addon by URL, proxying via its own proxy, MediaFlow Proxy or StremThru. 17 services: RD, AD, PM, DL, TorBox, Torrin, Offcloud, put.io, EasyDebrid, Debrider, PikPak, Seedr, plus Easynews, NzbDAV, AltMount, NNTP and StremThru Newz for Usenet.
- [Torrentio](https://torrentio.strem.fun/) - The most-used torrent scraper addon (scraper code: [torrentio-scraper](https://github.com/TheBeastLT/torrentio-scraper), 1,341★). Free public instance. Supports RD, PM, AD, DL, EasyDebrid, Offcloud, TorBox, put.io, High-Way. The free instance goes down under load; since May 2026 Real-Debrid refuses many cached releases by filename, so Torrentio with RD shows fewer results than with TorBox or AllDebrid.
- [Comet](https://github.com/g0ldyy/comet) - (1,136★) Fast torrent/debrid search addon. Self-hostable, proxies debrid streams so one account works from several IPs, also ships a Kodi addon and a Torznab API. Supports RD, AD, PM, TorBox, DL, Debrider, EasyDebrid, Offcloud, PikPak. Usenet support is on a development branch, not in the release.
- [MediaFusion](https://github.com/mhdzumair/MediaFusion) - (964★) Torrent + debrid addon for movies, series, live TV and sports. Works in Stremio, Kodi and the browser. Available via ElfHosted or self-hosted. Supports RD, AD, PM, DL, TorBox, Offcloud, PikPak, Seedr, Torrin, EasyDebrid, StremThru and P2P.
- [StremThru](https://github.com/MunifTanjim/stremthru) - (560★) Self-hosted companion: one API for 10 debrid services (RD, AD, PM, DL, TorBox, Offcloud, PikPak, EasyDebrid, Debrider, Torrin), content proxy, and built-in Store, Wrap, Torz, Newz (Usenet) and List addons.
- [StremThru Torz](https://stremthru.13377001.xyz/stremio/torz/configure) - Torrent addon built on StremThru's crowdsourced hash database. Works with any StremThru-supported debrid.
- [TorrentsDB](https://torrentsdb.com/) - Torrentio-style scraper addon with 23 sources. Supports RD, PM, AD, TorBox, EasyDebrid, Debrider, put.io, DL, Offcloud.
- [Sootio](https://github.com/sooti/sootio-stremio-addon) - (157★) Searches your debrid services for cached torrents and ranks the best quality first. Also Newznab + SABnzbd Usenet and Easynews. Supports RD, AD, TorBox, PM, Offcloud, DL, Debrider.
- [Meteor](https://stremio-addons.net/addons/meteor-midnightignite) - Hosted torrent addon with franchise-aware matching, run by MidnightIgnite. No public source. Supports RD, AD, TorBox, PM, DL, Debrider, EasyDebrid, Offcloud; Usenet results with TorBox Pro.
- [Peerflix](https://peerflix.mov/) - Spanish and English links. Hosted. Supports RD, PM, AD, DL, Offcloud, put.io, TorBox.
- [Debridio](https://debridio.com) - Paid addon bundle (scraper, catalogs, live TV). $9.99/year or $79.99 lifetime. Works with RD, AD, DL, PM, TorBox, EasyDebrid, Debrider. Not a debrid service itself.
- [Orion](https://orionoid.com) - Community index of torrent, Usenet and hoster links; free and premium accounts (free accounts get debrid resolving throttled at peak times). [Stremio addon](https://github.com/gorlev/orion-stremio-addon) (99★, unmaintained since 2023, still online) plays cached links via RD, AD, DL, PM, Offcloud.
- [Magnetio](https://github.com/peterdsp/Magnetio) - (49★) Self-hosted torrent addon with 22+ providers. Supports RD, PM, AD, DL, EasyDebrid, Offcloud, TorBox, put.io.
- [Intelligent Debrid Search](https://github.com/NepiRaw/Stremio-IntellDebridSearch) - (31★) Shows what is already in your debrid cloud as streams, matched to the title. Supports AD, RD, PM, TorBox (incl. Usenet downloads), DL.
- [Debrid Search](https://github.com/MrMonkey42/stremio-addon-debrid-search) - (156★) Shows downloads and torrents already in your debrid cloud. Supports RD, AD, PM, TorBox, DL. Unmaintained since 2024.
- [Jackettio](https://github.com/arvida42/jackettio) - (130★) Resolves streams using your Jackett indexers (incl. private trackers) + debrid. Supports RD, AD, PM, DL. Unmaintained since 2024.
- [Deflix](https://github.com/doingodswork/deflix-stremio) - (197★) Multiple sources, Go-based. Supports RD, AD, PM. Unmaintained since 2023.
- [Usenet-Ultimate](https://github.com/DSmart33/Usenet-Ultimate) - (174★) Self-hosted Usenet addon: searches Newznab indexers, Prowlarr or NZBHydra2 and streams through NzbDAV or Easynews. Also hosted by ElfHosted.
- [UsenetStreamer](https://github.com/Sanket9225/UsenetStreamer) - (396★) Streams NZBs into Stremio: searches Prowlarr/NZBHydra2 (plus built-in Easynews) and plays through NzbDAV.
- [StreamNZB](https://github.com/Gaisberg/streamnzb) - (89★) Self-hosted Usenet streaming: one place for providers and indexers, serves a full Stremio addon plus a Newznab API, Jellyfin endpoint and NNTP proxy. Also hosted by ElfHosted.
- [Frenchio](https://github.com/aymene69/frenchio) - (90★) French private trackers (UNIT3D, YGG, ABNormal, C411, Torr9). Supports AD, TorBox, DL, RD, plus qBittorrent for uncached torrents.
- [YARR!](https://github.com/spookyhost1/yarr-stremio) - (47★) 60+ torrent sources plus Prowlarr/Jackett. Supports RD, PM, AD, DL, TorBox, PikPak.
- [StreamFusion](https://github.com/Telkaoss/stream-fusion) - (20★) French-optimized. French indexers, Jackett, Zilean. Supports RD, AD, PM, TorBox, EasyDebrid, DL, Offcloud, PikPak. A separate rewrite ships as [Stream Fusion Reborn](https://hub.docker.com/r/limedrive/stream-fusion-reborn) (Docker only).
- [Barestreams](https://github.com/nanstate/barestreams) - (42★) Lightweight addon returning normalized P2P torrent streams from public sources. No debrid.
- [AutoStream](https://github.com/keypop3750/AutoStream) - (28★) Picks the best stream for you instead of a long list. Supports AD, RD, PM, TorBox, Offcloud.
- [Davio](https://github.com/arvida42/davio) - (37★) Self-hosted addon that resolves streams from any WebDAV server. By the Jackettio dev. Unmaintained since 2024.
- [Annatar](https://github.com/g0ldyy/annatar) - (105★) Fast Jackett fanout with caching. Supports RD, AD, PM, DL. Unmaintained since 2024.
- [Knightcrawler](https://github.com/knightcrawler-stremio/knightcrawler) - (407★) Self-hostable Torrentio fork. Supports RD, AD, PM, DL, Offcloud, put.io. Unmaintained since 2024; the ElfHosted instance is retired.
- [Comet Uncached](https://github.com/Zaarrg/comet-uncached) - (20★) Comet fork that also shows uncached results. Archived (Feb 2025).
- [TorrentClaw](https://torrentclaw.com/stremio) - Torrent search engine with a Stremio addon that scores each release 0-100 and checks it against the real file. Free: 15 streams per title, no account. PRO (`$3.99/mo`, `$69.90` lifetime) adds 50 streams, subtitles and Torznab. Works without debrid; uses RD, AD, TorBox or PM when you add a key. No public source.
- [Cauldron](https://github.com/wizaarddlabs/cauldron) - (24★) Self-hosted torrent + debrid search addon that also exposes a REST API. Supports RD, AD, PM, TorBox, Torrin, Offcloud.
- [Easynews+](https://github.com/sleeyax/stremio-easynews-addon) - (76★) Open-source Easynews addon with a search catalog; public instance or self-hosted. Needs an Easynews account. Fork with custom titles: [Easynews++](https://github.com/panteLx/easynews-plus-plus) (99★).
- [Stremio NZB Addon](https://github.com/sleeyax/stremio-nzb-addon) - (33★) Self-hosted Usenet addon: searches your own indexers or NZBHydra2 and hands Stremio's built-in Usenet player your NNTP servers. No WebDAV server needed.
- [Stremio Jackett](https://github.com/aymene69/stremio-jackett) - (303★) Self-hosted addon that searches your own Jackett server. Optional RD, AD, PM or TorBox. Last update Dec 2025.

### Stremio Addons — Regional & Niche
- [MammaMia](https://github.com/UrloMythus/MammaMia) - (163★) Italian. Direct HTTPS streams (no debrid).
- [stremio-ncore](https://github.com/detarkende/stremio-ncore-addon) - (142★) Hungarian. Self-hosted, streams from the nCore private tracker.
- [IlCorsaroViola](https://icv.stremio-italia.eu/) - Italian. UIndex, CorsaroNero, Knaben and Jackettio, with or without RD, TorBox, AD.
- [GuIndex](https://github.com/GuickerZ/guindex) - (24★) Brazilian. RD/TorBox.
- [BRASIL-RD-ADDON](https://github.com/onikopolar/BRASIL-RD-ADDON) - (44★) Brazilian. TorBox.
- [DubLuck](https://github.com/zLuckKing/DubLuck) - (1★) Brazilian Portuguese dubbed content. RD, AD, PM, DL.
- [Amatsu](https://github.com/mralanbourne/Amatsu) - (17★) Anime and live action from Nyaa. RD/TorBox or P2P. Archived (Apr 2026).
- [AniScraper](https://github.com/vanomarb/aniscraper-stremio-addon) - (21★) Anime from Nyaa, AnimeTosho, AniRena, TsukiHime. RD or P2P.
- [Yukistreams](https://github.com/kunolabs/yukistreams-addon) - (29★) Anime and Asian drama plus movies and series. Optional RD/TorBox.
- [YggPocket](https://github.com/Telkaoss/YggPocket) - (4★) French (YggTorrent). Runs natively on Android via Termux. RD, AD, DL, PM direct; PikPak, TorBox, EasyDebrid, Offcloud via StremThru.
- [TamilStream](https://github.com/koddamani1/tamilstream-addon) - (2★) Tamil movies and series. TorBox.
- [NoTorrent](https://stremio-addons.net/addons/notorrent) - Direct streams (no torrent/debrid). 25K+ movies and series from major streaming platforms, English and Spanish.
- [HdHub](https://stremio-addons.net/addons/hdhub) - HTTP streams from HdHub, with optional TorBox streams.
- [Formulio](https://stremio-addons.net/addons/formulio) - F1 and MotoGP replays. Debrid via StremThru.
- [StremVerse](https://stremio-addons.net/addons/stremverse) - Live sports events, replays and highlights.
- [Yomi](https://github.com/mralanbourne/Yomi) - (15★) Adult (Sukebei). RD/TorBox or P2P. Archived (Apr 2026).
- ~~[Leviathan](https://github.com/semiBE/stremio-leviathan-addon)~~ - Italian. RD/AD/TorBox. ⚠️ Dead (Nov 2026). Original repo and hosted instance (leviathanaddon.dpdns.org) are gone; a 4★ copy remains.
- ~~[Stremify](https://github.com/stremify/stremify)~~ - (99★) Multi-language HTTP sources. ⚠️ Dead (Nov 2026). Repo archived May 2025; the ElfHosted instance now redirects to the store.

### Stremio Utility Addons
- [AIOMetadata](https://github.com/cedya77/aiometadata) - (558★) Metadata addon: pick TMDB, TVDB, TVMaze, MyAnimeList, IMDb or Fanart.tv per type. Hosted by ElfHosted and others.
- [AIOManager](https://github.com/Sonicx161/AIOManager) - (365★) Manage addons across several Stremio accounts, sync between devices, failover rules.
- [AIOLists](https://github.com/SebastianMorel/AIOLists) - (179★) MDBList and Trakt list management. ElfHosted retired its instance; others remain.
- [SEL Filtering and Sorting](https://github.com/Tam-Taro/SEL-Filtering-and-Sorting) - (884★) Ready-made AIOStreams templates and AIOMetadata configs.
- [Stremio Status](https://github.com/SolitudePy/stremio-status) - (94★) Addon and status page showing whether Stremio addons and debrid services are up.
- [Statusio](https://github.com/ARandomAddonDev/Statusio) - (17★) Shows premium days left for RD, AD, PM, TorBox, DL inside Stremio.
- [EasyTorbox](https://github.com/easy-torbox/stremio) - (83★) Browser-only tool that sets up Stremio with a TorBox API key in one click.
- [DMM Cast](https://debridmediamanager.com/stremio) - Stream your DMM library and members' casts in Stremio. RD, AD, TorBox, PM, Offcloud, DL.
- [SubMaker](https://github.com/xtremexq/StremioSubMaker) - (150★) Subtitles from several sources plus AI translation with your own key.
- [SubSense](https://github.com/NepiRaw/Stremio-SubSense) - (42★) Subtitle aggregator: OpenSubtitles, SubDL, SubSource, AnimeTosho and more.
- [FilmWhisper](https://filmwhisper.dev) - AI movie/show search and recommendations with your own AI key.
- [xTremio](https://github.com/izemhsn/xTremio-stremio-addon) - (15★) Turns an Xtream Codes IPTV account into Stremio catalogs. Self-hosted.
- [TOP Streaming](https://top-streaming.stream/) - Top 10 lists from 48 streaming platforms in 93 countries.
- [Bitgraph](https://github.com/kiskey/stremio-bitgraph) - (0★) Bitmagnet integration with RD. Work in progress.
- ~~[SubHero v2](https://stremio-addons.net/addons/subhero-v2)~~ - Multi-source subtitles via Wyzie. ⚠️ Dead (Nov 2026). Both hosted instances (subhero.chromeknight.dev, subhero.onrender.com) are down.
- [Stremio Account Bootstrapper](https://github.com/DryKillLogic/stremio-account-bootstrapper) - (275★) Sets up a Stremio or Nuvio account from a preset (minimal to all-in-one, nine languages) in a few clicks, with RD, AD, PM, DL, Offcloud, TorBox or Easynews. Wipes the existing setup. [Web version](https://bootstrapper.stremx.net).
- [Core Builds](https://github.com/brevityA/Core-Builds) - (62★) AIOStreams templates tuned for smooth playback: bitrate caps, deduplication, sorting. r/CoreBuilds.
- [Local Cache](https://github.com/heroiamarelo1/Local-Cache) - (22★) Android TV app that runs a Stremio addon on the TV and saves debrid or torrent streams to USB, so you watch while it downloads and without buffering.
- [Vidhin's Regexes](https://github.com/Vidhin05/Releases-Regex) - (260★) Release regexes and ranked stream expressions based on TRaSH Guides, for sorting movie, TV and anime results. Loads as an AIOStreams template and syncs updates automatically.
- [IntroHater](https://introhater.com/configure.html) - Skips intros, recaps and outros by re-serving your AIOStreams streams as an edited HLS stream. Needs RD, TorBox, PM or AD. [Source](https://github.com/introhaterapp/IntroHater) (32★).

## Kodi Addons
- [Debrid Media Manager](https://debridmediamanager.com/kodi) - Browse and search films and shows in Kodi and play the cached releases DMM knows of and what members have cast, through your own account. Link Kodi with a code. RD, TorBox, AD, PM, Offcloud, DL.
- [Umbrella](https://github.com/umbrellaplug/umbrellaplug.github.io) - (290★) Actively updated (6.7.99, Oct 2026). Supports RD, AD, PM, Offcloud, TorBox, EasyDebrid, Easynews.
- [POV](https://github.com/kodifitzwell/repo) - Fen fork. No external scraper needed; can pull sources from AIOStreams. Supports RD, AD, PM, Offcloud, TorBox, Easynews.
- [FenLight+](https://github.com/thejason40/FenLightPlus) - (46★) Maintained fork of FenLight, whose original was discontinued in May 2026. Supports RD, AD, PM, Offcloud, TorBox, EasyDebrid, Easynews. Tikipeter's own [Fen 4](https://tikipeter.github.io/) now only plays your PM, Offcloud, TorBox and Easynews clouds.
- [Red Light](https://github.com/The-Red-Wizard/TheRedWizard) - (57★) Another FenLight fork, by The Red Wizard.
- [Jacktook](https://github.com/Sam-Max/plugin.video.jacktook) - (128★) Aggregates Stremio addons, Jackett/Prowlarr, Easynews and debrid. Supports RD, AD, PM, Offcloud, TorBox.
- [Comet](https://github.com/g0ldyy/comet/tree/main/kodi) - Official Kodi addon for a Comet instance. Same debrid support as the Stremio addon.
- [MediaFusion](https://github.com/mhdzumair/MediaFusion) - (964★) Also works with Stremio. Supports RD, AD, PM, DL, TorBox, Offcloud, PikPak, Seedr, Torrin, EasyDebrid.
- [The Crew](https://team-crew.github.io/) - Movies, TV and live TV. Supports RD, AD, PM, TorBox.
- [Otaku](https://github.com/Goldenfreddy0703/Otaku) - (180★) Anime. Supports RD, AD, PM, DL, TorBox, EasyDebrid.
- [MegaNexus](https://github.com/MegaNexusMediaPlayer/MegaNexus) - (31★) Runs Stremio and Nuvio addons inside Kodi. Debrid built in: TorBox, PM, Offcloud, RD, AD, Easynews.
- [a4kStreaming](https://github.com/a4k-openproject/a4kStreaming) - (58★) IMDb-based browser. Supports PM, AD.
- [Seren](https://github.com/nixgates/plugin.video.seren) - (333★) Debrid-first. Supports RD, PM, AD. Unmaintained since 2024; a [maintained fork](https://github.com/klass-723/plugin.video.seren) fixes the 2026 Trakt changes.
- [ResolveURL](https://github.com/Gujal00/ResolveURL) - (236★) Dependency that resolves hoster and debrid links for Fen, Umbrella, The Crew and others. RD, AD, PM, DL, Offcloud, TorBox, LinkSnappy, MegaDebrid, RPnet, SimplyDebrid.
- [Bingie](https://github.com/matke-84/skin.bingie) - (58★) Netflix-style skin. Optimized for low-power devices.
- [NeNeTeePee Stream](https://github.com/Appz4Fun/NeNeTeePee-Stream-Kodi) - (14★) Kodi 21 addon that streams from Usenet: searches NZBHydra2 and plays through NzbDAV's WebDAV. TMDb Helper player.
- [EasyNews Kodi](https://github.com/tetsuosoft/EasyNewsKodi) - (28★) Searches Easynews and plays its streams in Kodi, with saved newsgroups. Kodi 19+, Easynews account needed.
- [Account Manager Lite](https://github.com/Zaxxon709/accountmanager) - (35★) Authorize RD, PM, AD, TorBox, Offcloud, Easynews, Trakt and MDBList once and push the tokens into Fen Light, Umbrella, POV, Seren, Otaku, a4kStreaming, ResolveURL and about a dozen other addons. QR sign-in.
- [Gaia](https://gaiakodi.com) - Movies and shows from torrent, Usenet and hoster sources. Supports PM, Offcloud, RD, TorBox, AD, DL and Debrider, plus Easynews and Orion; limited support for LinkSnappy, Mega-Debrid and a few others. Kodi 21+. [Repo](https://github.com/gaiakodi/gaiamain) (11★).
- [Prism](https://github.com/Goldenfreddy0703/Prism) - (19★) Seren fork from the Otaku developer: movies, shows and anime in one addon, with Simkl. Supports RD, PM, AD, TorBox, Offcloud (optional). Early release.

## Proxy & Infrastructure
- [MediaFlow Proxy](https://github.com/mhdzumair/mediaflow-proxy) - (832★) Streaming proxy for HTTP(S), HLS and MPEG-DASH with ClearKey DRM decryption. Enables Stremio addons to proxy debrid streams, bypassing IP restrictions. Also supports IPTV (Xtream Codes), Acestream.
- [StremThru](https://github.com/MunifTanjim/stremthru) - (560★) Wraps Stremio addons, proxies streams, manages debrid library. Supports RD, AllDebrid, TorBox, Premiumize, Debrid-Link, Offcloud, EasyDebrid, PikPak and more.
- [Warpbox](https://github.com/mainlink0435/warpbox) - (45★) WebDAV proxy for TorBox so rclone library scans stop hitting API rate limits. Cached torrents and Usenet downloads.
- [Stremio Stack](https://github.com/ImJustDoingMyPart/stremio-stack) - (42★) Self-hosted Stremio backend for RD: Comet, Jackett, Zilean and a PostgreSQL cache in one Docker stack.
- [DavDebrid](https://github.com/arvida42/davdebrid) - (19★) WebDAV for Debrid-Link. Auto-organizes movies and shows. Unmaintained since 2024.
- [self-debrid](https://github.com/an0mal1a/self-debrid) - (51★) Use your own infrastructure as debrid in Kodi. Answers AllDebrid/RD API calls locally.
- Beemio - Self-hosted Stremio companion server.

## Media Server Integration
- [rex](https://rex.debridmediamanager.com/) - A media server that owns no files. Any source in every Plex app: zurg, Stremio addons or your own app. Nothing to download and nothing to scan. Free for personal use.
- [rex-stremio](https://github.com/debridmediamanager/rex-stremio) - Your Stremio addons' catalogs as rex libraries, played from your stream addons and never downloaded.
- [Ether](https://github.com/braedonsaunders/ether) - (174★) On-demand server that streams the TMDB catalogue into Plex, Jellyfin, Emby, Infuse, Swiftfin, Silo and Stremio apps from your debrid accounts and Usenet providers.
- [TMDB-To-VOD](https://github.com/gogetta69/TMDB-To-VOD-Playlist) - (330★) TMDB+debrid → Xtream Codes/M3U playlists for movies, series and live TV.
- [RoboFuse](https://github.com/itsrenoria/robofuse) - (114★) RD .strm generator, rewritten in Go. Library repair. Inspired by zurg. Supports Plex/JF/Emby.
- [jf-resolve](https://github.com/vicking20/jf-resolve) - (48★) Browse TMDB and play from Stremio addons in the browser or through Jellyfin. Also available as a Jellyfin plugin.
- [JellyGrail](https://github.com/philamp/jellygrail) - (44★) Modified JF Docker. Virtual filesystem. Supports JF/Kodi/Plex.
- [Fetcherr](https://github.com/goneturbo/fetcherr) - (37★) Jellyfin-compatible bridge for Infuse and VidHub. Syncs Trakt watchlists and plays RD or TorBox streams from Stremio addons.
- [Polyfin](https://github.com/moodiness/polyfin) - (32★) Self-hosted server that brings your Stremio addons and IPTV to any Jellyfin app.
- [rd_symlink_manager](https://github.com/ericvlog/rd_symlink_manager) - (23★) Single-click symlink automation. Plex/Emby/Jellyfin.
- [Mycelium](https://github.com/corveck79/mycelium) - (23★) Watchlist → TorBox or RD → Jellyfin/Plex streams. No *arr, FUSE or rclone needed.
- [Litterbox](https://github.com/elfhosted/litterbox) - (18★) RD library cleanup. OAuth sign-in, bulk-delete broken entries.
- [DebridMovieMapper](https://github.com/phrontizo/DebridMovieMapper) - (7★) RD or TorBox library → WebDAV with TMDB identification. JF/Plex.
- [vibeDebrid](https://github.com/vibeMonarch/vibeDebrid) - (2★) Anime-friendly DMM. Self-hosted. Plex/JF.
- [Synology RD v2](https://github.com/max13fr/synology-real-debrid-v2) - (22★) RD file host module for Synology Download Station. Unmaintained since 2016.
- [Remux](https://github.com/lostb1t/remux) - (648★) Rust media server with a Jellyfin-compatible API: plays Stremio addon streams, WebDAV, torrents and local files in Infuse, Swiftfin and other Jellyfin apps. Desktop tray app or Docker. Hosted by ElfHosted.
- [Hound](https://github.com/Hound-Media-Server/hound) - (474★) Go media server with built-in tracking: streams from your drives, torrents, debrid and Usenet through Stremio addons (AIOStreams). Desktop, Android/Android TV, iOS/tvOS clients.
- [Gelato](https://github.com/lostb1t/Gelato) - (868★) Jellyfin plugin that brings your AIOStreams addon into Jellyfin: Jellyfin search finds its titles, catalogs are imported as normal library items, streams are found when you press play and go through Jellyfin, so your debrid service sees one IP. Seerr requests add titles. Jellyfin 12. Same author as Remux.
- [mediastorm](https://github.com/godver3/mediastorm) - (147★) Self-hosted streaming server from the CLI Debrid author, with native iOS, tvOS, Android and Android TV apps. Streams from RD, TorBox, AD, PM, Torrin or Usenet (built-in NNTP, NzbDAV, AltMount, Decypharr) alongside Plex and Jellyfin libraries; live TV and DVR, profiles, Trakt.
- [jfresolve](https://github.com/vicking20/jfresolve) - (40★) Jellyfin plugin (12.4+) that adds TMDB movies and shows to your library and plays them through a Stremio addon (AIOStreams, Torrentio, Comet...) with your debrid key. Nothing is downloaded; resumes when the debrid host drops the connection.
- [Synology Put.io](https://github.com/barisariburnu/synology-putio) - (23★) File host module for Synology Download Station: downloads files, MP4 conversions and zip streams from your put.io account to the NAS.
- [AioFin](https://github.com/tweakapps/aiofin) - (13★) AIOStreams with a Jellyfin-compatible API, so Infuse, SenPlayer and other Jellyfin apps see your AIOStreams catalogs as libraries and play straight from the debrid or Usenet link. Nothing is transcoded; progress is kept per profile. Docker image replaces the AIOStreams one.

## File System
- [rclone](https://github.com/rclone/rclone) - (60,776★) a command-line program to mount cloud storage providers to your computer (like Dropbox)
- [rclone_RD](https://github.com/itsToggle/rclone_RD) - (222★) RClone Fork that implements RealDebrid. Archived.
- [bclone](https://github.com/BenjiThatFoxGuy/bclone) - (94★) rclone fork with an AllDebrid backend (plus Alist, Terabox and others).
- [TorBox Media Center](https://github.com/TorBox-App/torbox-media-center) - (289★) Official TorBox tool that mounts your TorBox media as organized folders for Plex, Jellyfin and Emby.
- [zurg](https://zurg.debridmediamanager.com/) - Every debrid account and Usenet in one folder that Plex, Jellyfin, Emby and Infuse read like a normal drive. Mount it with rclone. The [public release](https://github.com/debridmediamanager/zurg-public) is Real-Debrid only. Nightlies with every supported debrid service and Usenet are for sponsors.

## Content Managers
- [Debrid Media Manager](https://debridmediamanager.com/) - Find movies and shows and keep them in your debrid library. RD/AD/TB/PM/OC/DL. Share libraries as [hashlists](https://hashlists.debridmediamanager.com/).
- [Unchained](https://github.com/LivingWithHippos/unchained-android) - (649★) Android app for RD: torrents and magnets, hoster links, streaming to mpv/VLC, search plugins. On F-Droid and Google Play.
- [TorBox Manager](https://github.com/jittarao/torbox-app) - (187★) Web UI alternative for TorBox. Batch-add torrents, magnets, hoster links and NZBs; pick files across torrents.
- [atba](https://github.com/93Pd9s8Jt/atba) - (183★) Android client for TorBox with streaming. Android TV support is partial.
- [utac](https://github.com/ech0devv/utac) - (81★) Android client for TorBox.
- [nullseek](https://github.com/LivingWithHippos/nullseek) - (41★) Android app for TorBox, by the Unchained developer.
- [Real Debrid Manager](https://github.com/AyushSehrawat/rdm) - (88★) Web UI to search and manage RD downloads and torrents. Archived.
- [DebridUI](https://github.com/viperadnan-git/debridui) - (106★) Web debrid client: manage files across several accounts, discover trending titles, stream to your player, addon support. RD, TorBox, AD. Hosted at [debridui.viperadnan.com](https://debridui.viperadnan.com).
- [Piko](https://github.com/NihilDigit/piko) - (657★) Fast PikPak client for Android and Windows (macOS, Linux experimental). Parses magnets, torrents and share links with per-file selection, multi-connection transfers, drive-wide search.
- [DebForge](https://github.com/AbhinavXT/debforge) - (11★) Android/Android TV app for TorBox, RD, AD, PM and DL: library with posters, built-in player, 16-connection downloads, auto-download new episodes. On [F-Droid](https://f-droid.org/packages/com.abhinavxt.debforge).
- [TorBox Desktop](https://github.com/jkalasas/torbox-app) - (27★) Native TorBox client for Windows, Linux and Android: torrents and web downloads, file picker, local transfers with bandwidth cap.
- [Premiumize.me app](https://play.google.com/store/apps/details?id=me.premiumize.app) - Official Android app (10K+ installs, 4.6★): browse your cloud, add torrents and hoster links, magnet handler. Paid account needed.
- [TorBox Companion](https://github.com/crazycacti/torbox-companion) - (24★) Rust rewrite of TorBox Manager: torrents, web downloads and Usenet, search with add-to-library, a player, uploads to Google Drive, Dropbox or OneDrive, automation rules. Docker.
- [AllDebrid Mobile App](https://alldebrid.com/m/) - Official mobile web app: add links and magnets, get notified when a torrent is ready, stream to your local player.

## Streaming Apps
- [Seanime](https://github.com/5rahim/seanime) - (4,303★) Anime/manga media server. Desktop+Web. Streams torrents through RD, TorBox, AllDebrid, Premiumize. Mobile and TV client: [Tenji](https://github.com/5rahim/seanime-tenji) (92★, iOS, Android, tvOS, Android TV).
- [Debrify](https://github.com/varunsalian/debrify) - (638★) Open-source media hub with a built-in player: debrid accounts, WebDAV, IPTV and Stremio addon catalogs in one app. Supports RD, TorBox, Premiumize, PikPak, AllDebrid. Android, Android TV, iOS, Apple TV, Windows, macOS, Linux. Flutter.
- [WuPlay](https://github.com/wuplayapp/wuplay-releases) - (566★) Android TV. Plays Stremio addons with profiles, watchlists and multi-device sync. No account needed.
- [Lumera](https://github.com/LumeraD3v/Lumera) - (238★) Android TV. Consumes Stremio addons without Stremio; imports your Stremio account.
- [DodoStream](https://github.com/DodoraApp/DodoStream) - (247★) Open-source Android TV/Android media hub for Stremio addons. Profiles, no accounts.
- [Ferrite](https://github.com/Ferrite-iOS/Ferrite) - (190★) iOS. Media search engine with plugins. Supports RD, AllDebrid, Premiumize, TorBox, Offcloud.
- [Orivio TV](https://github.com/prehakanson-art/OrivioTVAppleTV) - (126★) tvOS. Addon + debrid streaming with Trakt/TMDB. Sideloaded.
- [Flixorent](https://github.com/Hashaleen420/Flixorent) - (101★) Android/Android TV. Netflix-style app for RD, TorBox, AllDebrid with a built-in downloader.
- [Nuvio](https://nuvio.tv) - Free, open-source app that plays your Stremio-compatible addons with profiles, watch progress and Trakt. Android ([4,390★](https://github.com/NuvioMedia/NuvioMobile)), Android TV ([3,349★](https://github.com/NuvioMedia/NuvioTV)), webOS/Tizen, iOS via AltStore; desktop in alpha.
- [Syncler](https://syncler.net/) - Android, Android TV and Fire TV. Debrid suite, link filtering and auto-select, multiple profiles with locks, Trakt/Simkl sync. Paid Syncler+ tier.
- [wako](https://www.wako.app/) - iPhone, iPad, Mac, Android, Android TV. Tracks what you watch and plays your sources in one tap. Free download, 7-day trial.
- [PlayTorrio](https://playtorrio.pages.dev/) - Windows, Android/Fire TV, macOS, Linux, iOS. Stremio addons, IPTV, manga, music. Supports RD, AllDebrid, Premiumize, TorBox.
- [DebridStream](https://debridstream.com/) - Android TV, Fire TV, mobile. Netflix-like. Built-in debrid manager, addon support, profiles. Free tier + Pro subscription. r/Debrid_Stream_App.
- [Odin](https://github.com/ad-on-is/odin-server) - (171★) Self-hosted FOSS. Jackett+RD. Server + [Android TV app](https://github.com/ad-on-is/odin-tv). Both repos archived.
- [Debrid Vault](https://debridvault.elfhosted.com/) - Web. Manages music, movies/shows, games, audiobooks, books and comics with TorBox or RD. Playlists, Last.fm, live lyrics.
- [Eclipse](https://eclipsemusic.app/) - Music player for iOS, macOS, Android, Android TV, Windows and web. Streams from TorBox through its Nebula addon.
- [InkShelf](https://books.tbm.tools/) - Web. Stremio-style app for books and audiobooks. Early access.
- [Pageturner](https://apps.apple.com/us/app/pageturner/id6758014135) - iPhone. Audiobook player with your own sources, including debrid. Free, Pro $7.99.
- [Strmr](https://github.com/strmrdev/strmr-releases) - (128★) Android TV. Trakt sync, continue watching. Supports RD, AllDebrid, Premiumize. r/strmr.
- [Kinema](https://github.com/ThilinaTLM/kinema) - (9★) Pre-1.0 desktop app (Windows/macOS/Linux). Torrentio sources via RD/AllDebrid → embedded mpv or VLC.
- [webdav-browser](https://github.com/0xSilentNeo/WEBDAV-browser-MPV) - (22★) mpv script: browse, search and play your RD WebDAV library inside mpv, as posters or a two-panel list. Works with any WebDAV server.
- [ARVIO](https://github.com/ProdigyV21/ARVIO) - (801★) Media hub for Android TV, Fire TV and phones (Google Play or APK), plus a self-hostable web app. Plays Stremio-compatible addons through RD, AD, PM or TorBox, and video from your Telegram channels.
- [SceneBox](https://github.com/donbytyqi/scenebox) - (133★) Torrent streaming app for iPhone, iPad, Apple TV and Mac, fed by Stremio addons. Releases cached on RD, AD, PM, DL or TorBox play straight over HTTPS.
- [Harbor](https://github.com/Harborofficial/Harbor) - (189★) Desktop Stremio-addon client for Windows and macOS (community Linux packages): stream ranking, watch parties, live TV, availability checks and playback through RD, AD, PM, DL or TorBox. Beta.
- [AudioYam](https://github.com/drdilips1/Audiohub) - (14★) Audiobook, ebook and podcast app for Android and the [web](https://listen.audiohubapp.com/). Plays from Audiobookshelf and streams books from your TorBox or RD cloud.
- [Compass](https://compass.sarl/) - Desktop Stremio-addon client for Windows and macOS (plus a browser version and community Linux packages): stream ranking, watch parties, live TV and DVR, Jellyfin/Plex libraries. Checks RD, AD, PM, DL and TorBox caches itself and cross-checks your debrid library. [Source](https://github.com/compassstremio/Compass) (50★).
- [Rattin](https://github.com/narzaut/rattin-public) - (164★) Desktop torrent streaming app for Windows and Linux built on libmpv: TMDB browsing, binge mode with intro skipping, phone remote. Optional RD or TorBox cache for instant playback with no peers.
- [RogPlay](https://github.com/kunwarxshashank/rogplay) - (107★) Android and Android TV player for Stremio and Nuvio addons, IPTV and local files; resolves magnets itself through RD, AD, PM or TorBox. Watch parties. Uses Google sign-in and Firebase analytics.
- [Magnolia](https://github.com/magnolia-org/magnolia) - (21★) Torrent streaming app for Windows, macOS and Linux with built-in search and mpv playback; TorBox built in, other debrid services through extensions.
- [Enve](https://envemedia.com/books/) - Audiobook, ebook, comic and podcast app for iOS and Android. Reads Audiobookshelf, Plex, Jellyfin, Komga and others, plus books stored on Premiumize, RD or TorBox. No ads or analytics. [Source](https://github.com/opisaac9001/Enve-Book-Player) (43★).

<details>
  <summary>More streaming apps</summary>

  - [Debrid'em All](https://play.google.com/store/apps/details?id=com.yablio.debridemall) - Android TV. Stream torrents via AllDebrid. By Yablio.
  - [Unreal Debrid](https://play.google.com/store/apps/details?id=com.yablio.realdebridtv) - Android/ATV. RD streaming. Episode tracking, intro skip. By Yablio.
  - [Stremize](https://stremize.com/) - Android phone, tablet, Android TV, Fire TV. Addons, debrid and Xtream/M3U playlists. Subscription.
  - [Weyd](https://weyd.app/) - Android TV/Fire TV. Trakt-based streaming with Premiumize, TorBox or Offcloud. From $5 per 3 months, 7-day trial.
  - [StreamVault](https://github.com/vitobotta/streamvault) - (36★) Self-hosted web app. RD with Torrentio/Comet sources.
  - [DuckFlix Lite](https://github.com/discoduckasaurus/duckflix-lite) - (2★) Android TV. Netflix-like RD interface.
  - [FireFlix](https://github.com/luckygreen/FireFlix) - (5★) Fire TV. Transform Fire Stick into Netflix with RD+Kodi.
  - ~~Cyberflix~~ - Android. RD integration. ⚠️ Dead (Nov 2026). [cyberflix.io](https://www.cyberflix.io/) says operations are indefinitely suspended.
  - ~~[Omni](https://omni-site.pages.dev/)~~ - Apple TV/iOS. Content hub. Infuse+RD. ⚠️ Dead (Nov 2026). Pulled from the App Store; the site's download link returns 404.
</details>

## Download Managers
- [pyLoad](https://github.com/pyload/pyload) - (3,905★) Download manager with 100+ host plugins. Multihoster support.
- [Cyberdrop-DL](https://github.com/Cyberdrop-DL/cyberdrop-dl) - (917★) Bulk downloader for file hosts and galleries. Add an RD token and it also downloads from the 250+ hosts RD supports.
- [pikpakcli](https://github.com/52funny/pikpakcli) - (261★) Go command-line tool for PikPak: download, upload, share.
- [BATorrent](https://github.com/BATorrent-app/BATorrent) - (164★) Desktop torrent client (Windows, macOS, Linux) that shows downloads as cover art and plays them while they download. Torrents already cached on RD or TorBox stream from there, with nothing downloaded or seeded.
- [rdcli](https://github.com/johackim/rdcli) - (152★) Node.js command-line tool (npm): unrestricts hoster links, torrents and magnets through RD and downloads them.
- [DebridDownloader](https://github.com/CasaVargas/DebridDownloader) - (98★) Free, open-source desktop downloader for RD, TorBox and Premiumize. Resumable multi-connection downloads.
- [kaput](https://github.com/davidchalifoux/kaput-cli) - (81★) Rust command-line client for put.io: manage files and transfers, download.
- [TorrentDownloaderRD](https://github.com/ItsYeBoi20/TorrentDownloaderRD) - (65★) RD/AD torrent searcher+downloader. Windows desktop.
- [putio-sync](https://github.com/putdotio/putio-sync) - (60★) Official put.io tool that keeps a folder in sync between put.io and your computer. CLI, plus a [desktop app](https://github.com/putdotio/putio-sync-desktop) for macOS and Windows.
- [OneDL](https://github.com/ellite/OneDL) - (59★) Universal CLI downloader — torrents, hosters, MEGA, HTTP(S). Supports RD, AD, Premiumize, TorBox, DebridLink.
- [AllDebrid-Watcher](https://github.com/vlacour97/alldebrid-watcher) - (56★) Monitors+downloads AD transfers automatically.
- [torrent-hound](https://github.com/baddymaster/torrent-hound) - (34★) Terminal torrent search across several trackers; one key sends a result to RD and hands the links to your download tool, another opens it in Seedr.
- [Ultimate Downloader](https://github.com/xersbtt/ultimate-downloader-colab) - (30★) Google Colab notebook that downloads from Gofile, Pixeldrain, Mega, YouTube, PikPak and others into your Google Drive, named for Plex. RD or TorBox for premium hosts and magnets.
- [Knightloader](https://github.com/junkerderprovinz/knightloader) - (13★) Self-hosted download manager for hosters, debrid, torrents, Usenet and videos.
- [ClicknDebrid](https://github.com/XaverLeet/clickndebrid) - (10★) Click'n'Load proxy: catches CNL links from file-host pages, unlocks them through RD and forwards them to pyLoad or JDownloader. Docker.
- [Mediarr](https://github.com/wjH-3/Mediarr) - (8★) Windows CLI. RD+IMDb+TVMaze+DMM+MPV. Unmaintained since 2024.
- [Real_Debrid_Toolbox](https://github.com/arlcodes/Real_Debrid_Toolbox) - (7★) Python script: uploads .torrent files, tracks and downloads torrents, unrestricts hoster links, removes duplicates by hash. RD.
- [LazyDebrid](https://onurhanak.github.io/lazydebrid/) - (5★) Terminal-based interface for managing RD torrents/downloads. Archived.
- [littlejohn](https://github.com/mat-lo/littlejohn) - (1★) Rust terminal app: torrent search, file picker and built-in downloader through RD.

<details>
  <summary>Games and consoles</summary>

  - [Hydra Launcher](https://github.com/hydralauncher/hydra) - (17,602★) Game launcher and catalogue for Windows and Linux. Downloads through its built-in torrent client or through RD, AD, PM or TorBox.
  - [Fit Launcher](https://github.com/CarrotRub/Fit-Launcher) - (1,398★) Browse, download and install FitGirl repacks (Windows, Linux). Downloads can go through RD or TorBox since v4.0 (Dec 2025).
  - [Orbit Store](https://github.com/saawant12/orbit-store-ps5) - (1,324★) Download manager for jailbroken PS5s, with a companion app for Mac, Windows and Linux. Can download through TorBox.
  - [DirectPackageInstaller](https://github.com/marcussacana/DirectPackageInstaller) - (557★) Sends PKG files from direct links to a PS4 or PS5; resolves hoster links through AllDebrid, Real-Debrid or Debrid-Link.
  - [Project GLD](https://github.com/Y0URD34TH/Project-GLD) - (528★) Windows game library and launcher; community Lua scripts find downloads, and its built-in torrent client can use RD or TorBox.
  - [Pegasus DL+](https://github.com/pegasus-ps5/pegasus-dl) - (456★) PS5 homebrew: browse catalogs, download and install packages with a controller. Links RD or TorBox from your phone.
  - [RGSX](https://github.com/RetroGameSets/RGSX) - (437★) ROM downloader for Batocera, Knulli and RetroBat; unlocks 1fichier with its own API, falling back to AD, DL, RD or TorBox.
  - [Ascendara](https://ascendara.app) - Game library and installer for Windows and Linux that downloads pre-installed games so there is no setup step. Can fetch through TorBox. [Source](https://github.com/Ascendara/ascendara) (321★).
  - [PS5 Library](https://github.com/deox1111/ps5-library) - (307★) Game library for jailbroken PS5s that downloads, unpacks and installs on the console; AllDebrid, Real-Debrid or TorBox fetch from supported hosts.
  - [SSPI](https://github.com/Xyhlo/SSPI) - (153★) Package installer for jailbroken PS4s: search, download and extract (multi-part RAR/7z) through RD, TorBox, AD or PM. Builds are closed; the repo is a source overview.
  - [OpenGameInstaller](https://github.com/Nat3z/OpenGameInstaller) - (122★) Addon-based game installer for Windows with RD, AllDebrid and TorBox support.
  - [Yamata Launcher](https://github.com/Gr3gorywolf/Yamata-launcher) - (122★) Game launcher for Windows, macOS, Linux and Android (also Batocera and SteamOS) that reads Hydra-compatible download sources; downloads through AD, RD or TorBox.
  - [romgi](https://github.com/caprado/romgi) - (112★) ROM downloader for Android handhelds (Retroid, Anbernic, AYN); torrent links resolve through RD or TorBox since v1.7 (Aug 2026).
  - [The Goonies App](https://github.com/GoodmanBCN10/The-Goonies-APP) - (45★) Spanish. Content installer for modded Nintendo Switch consoles; RD as a download engine since v2.1.4 (Jul 2026).
  - [TorBox Tinfoil Server](https://github.com/TorBox-App/torbox-tinfoil-server) - (39★) Official. Serves your TorBox downloads as a custom Tinfoil shop on a Nintendo Switch. Paid plan, Docker. Last updated May 2025.
  - [GODsend 360](https://github.com/ghostyshell/GODSend-360) - (29★) Xbox 360 game manager for the Aurora dashboard: a desktop backend fetches games, converts ISOs to GOD and sends them over FTP. RD or TorBox can fetch the torrents first for faster downloads.
</details>

## Browser Extensions
- [Magnetar](https://github.com/ArrCee76/magnetar) - (91★) [Firefox](https://addons.mozilla.org/firefox/addon/magnetar/)+[Chrome](https://chromewebstore.google.com/detail/magnetar/cllbehlfiahgijdojkopgnnmcoenhlla). Hash detect → RD, TorBox, AllDebrid, Premiumize, RDT Client or a local client. Popup blocker.
- [AllDebrid Extension](https://chromewebstore.google.com/detail/alldebrid-extension/mdjbgnpehbhpibonmjjjbjaoechnlcaf) - Official. Chrome (40,000 users)/[Firefox](https://addons.mozilla.org/firefox/addon/alldebrid-addon/).
- [Debrid-Link Extension](https://chromewebstore.google.com/detail/debrid-link/nfdhjpliieckopfcpeglebihglikgojn) - Official. Chrome (10,000 users)/[Firefox](https://addons.mozilla.org/firefox/addon/debrid-link-plugin/).
- [Real Debrid Download Manager](https://chromewebstore.google.com/detail/khglpdagpjepfkjnnjcpiciekjoailhf) - Chrome (10,000 users)/[Firefox](https://addons.mozilla.org/firefox/addon/real-debrid-download-manager/). Send torrents to RD and download the results.
- [NZBDonkey](https://github.com/Tensai75/NZBDonkey) - (119★) Chrome/Firefox. Grabs NZBs and sends them to TorBox, Premiumize, SABnzbd, NZBGet and others.
- [Mega-Debrid Extension](https://chromewebstore.google.com/detail/gakkobdjiifadnllomenhnpojjdaoaad) - Official. Chrome (4,000 users)/[Firefox](https://addons.mozilla.org/firefox/addon/mega-debrid-plugin/). Unrestricts links through Mega-Debrid.
- [TorBox Control](https://chromewebstore.google.com/detail/ofjikipldidgfpjchdgnfbaklkbkfkgf) - Chrome/[Firefox](https://addons.mozilla.org/firefox/addon/torbox-downloader/). Send URLs, magnets and NZBs to TorBox and manage the queue. Third-party.
- [Debrid Media Manager Extension](https://github.com/debridmediamanager/browser-extension) - (10★) Chrome/[Firefox](https://addons.mozilla.org/firefox/addon/debrid-media-manager/) (1,481 users)/userscript. Debrid Media Manager buttons on IMDb, Trakt and other movie and TV sites.
- [Real-Debrid Manager](https://addons.mozilla.org/firefox/addon/real-debrid-manager/) - Firefox/[Chrome](https://chromewebstore.google.com/detail/jjbadgfkgdiegemfoelphaeknpkcofjn). Manage RD torrents and links, bulk-copy links, MyJDownloader. Source now private ([issue tracker](https://github.com/techstacktony/real-debrid-manager-public)).
- [RD Chrome Extension](https://github.com/JDevlieghere/Real-Debrid) - (31★) Chrome. Unmaintained since 2019.
- [RD Safari Extension](https://github.com/ClosestStorm/MacOS-iOS-Real-Debrid-Safari-Extension) - (15★) Safari Mac/iOS. Unmaintained since 2022.
- [Magnet-to-RD](https://github.com/Pahiro/Magnet-to-RD) - (21★) Userscript. Send magnets to RD from any page, skip duplicates, pick file types.
- [DMM Res Sections](https://github.com/Woahai321/dmm-res-sections) - (7★) Chrome. Resolution sections for DMM. Unmaintained since 2024.
- [RD Utils](https://github.com/LOCKhart07/real-debrid-utils) - (5★) [Firefox](https://addons.mozilla.org/firefox/addon/real-debrid-utilities/). "Get All Links" button on RD's downloader page.
- [RD Tools](https://github.com/SlothEater/Real-Debrid-Tools) - (5★) Chrome. Magnet context menu backed by a local helper app. Unmaintained since 2023.
- [RD VLC Extension](https://github.com/siddmo/real_debrid_vlc_extension) - (0★) VLC extension for macOS: paste a magnet and it plays the largest file through RD, reusing torrents already in your cloud.
- [RD Magnet](https://github.com/sarkivs/RD_Magnet) - (0★) Unpacked Chrome extension. Click or right-click a magnet or .torrent to send it to RD: all files, video only, or pick files.
- [RD Raycast](https://www.raycast.com/Yamen/real-debrid-manager) - macOS Raycast extension (864 installs). Add torrents or links, view downloads, torrents and traffic. No feature updates since its 2023 release.
- [TorBox Raycast](https://www.raycast.com/baradusov/torbox) - macOS Raycast extension. Search downloads, add torrents and web downloads.
- [DMM Top Filter Buttons](https://greasyfork.org/scripts/546847-dmm-top-filter-buttons-stable-cached) - Userscript (143 installs). One-click DMM filters: instantRD, Cached, 4K, 1080p, 720p, Dolby Vision, HDR, Remux.
- [PikPak Extension](https://chromewebstore.google.com/detail/ohpgjiplhigpfcioaeakjfjnkbgjpgbl) - Official. Chrome (100,000 users). Save links and magnets to your PikPak drive.
- [Deepbrid Extension](https://chromewebstore.google.com/detail/ampccappllebdaplacfcopfdgofmohmh) - Official. Chrome (819 users)/[Firefox](https://addons.mozilla.org/firefox/addon/deepbrid-browser-extension/). Detects supported links, manages downloads. Premium only.
- [PikPak Enhancement Master](https://github.com/digbug82/PikPak_Enhancement_Master) - (403★) Userscript for PikPak web: drive-wide search, advanced path bar, batch operations, mobile layout. Chinese/English.
- [put.io Extension](https://chromewebstore.google.com/detail/gmlaklldebhgnhfoppklejnjcmndcehf) - Official. Chrome (2,000 users)/[Firefox](https://addons.mozilla.org/firefox/addon/put-io/). Right-click a link or magnet to send it to put.io.

## Telegram & Discord Bots

### Telegram
- [unchained-bot-kotlin](https://github.com/LivingWithHippos/unchained-bot-kotlin) - (29★) RD. Unmaintained since 2022.
- [DebridBot](https://github.com/Oihalitz/DebridBot) - (6★) RD, AD, TorBox, PM, DL, Mega-Debrid, Deepbrid, High-Way. Hoster links, magnets, torrents, FileCrypt folders.
- [alldebridBot](https://github.com/Bildcraft1/alldebridBot) - (3★) AD. Unmaintained since 2024.
- [rdctl-bot](https://github.com/crazyuploader/rdctl-bot) - (2★) RD
- [debrid-bot](https://github.com/shahdab212/debrid.link-bot) - (2★) DL (Cloudflare Worker proxy)
- [RD Cache Bot](https://gitlab.com/lucasliet/real-debrid-cache-telegram-bot) - RD (GitLab). Adds each Switch game file (nsp/xci) to RD as its own torrent so WebDAV shows no RAR archives. Portuguese.
- [Deepbrid Bot](https://t.me/DeepbridTBot) - Official Deepbrid
- [TorBox Bot](https://t.me/torboxapp_command_bot) - Official TorBox bot: add and list downloads, pay, get account notifications. Link it under TorBox's Integration settings.
- [SeedrccBot](https://github.com/hemantapkh/SeedrccBot) - (95★) Manage one or more Seedr accounts from Telegram.
- [mirror-leech-telegram-bot](https://github.com/anasty17/mirror-leech-telegram-bot) - (4,350★) Self-hosted bot that mirrors or leeches links, torrents and NZBs to Google Drive, Telegram or any rclone remote. Optional AllDebrid key for hoster links and magnets.
- [WZML-X](https://github.com/SilentDemonSD/WZML-X) - (1,531★) mirror-leech bot fork; the `-ad` flag unlocks hoster links or runs magnets entirely on AllDebrid and downloads from its CDN.

### Discord
- [AllDebrid Bot](https://top.gg/bot/1046107001584881734) - AD (top.gg). Not affiliated with AllDebrid.
- [Deepbrid Bot](https://www.deepbrid.com/page/discord-bot) - Official Deepbrid
- [disbox](https://github.com/gabrieljcodes/disbox) - (3★) TorBox
- [NyaaScraperRD](https://github.com/Anezium/NyaaScraperRD) - RD+Nyaa. Unmaintained since 2024.

## API Libraries
- [TorBox SDKs](https://github.com/TorBox-App/torbox-sdk-py) - Official. [Python](https://github.com/TorBox-App/torbox-sdk-py), [JavaScript](https://github.com/TorBox-App/torbox-sdk-js), [Go](https://github.com/TorBox-App/torbox-sdk-go). TorBox.
- [go-debrid](https://github.com/Deflix-tv/go-debrid) - (36★) Go. RD/AD/PM. Used by Deflix. Unmaintained since 2021.
- [rd_api_py](https://github.com/s-krilla/rd_api_py) - (19★) Python. RD. Unmaintained since 2023.
- [RD.NET](https://github.com/rogerfar/RD.NET) - (14★) C#. RD. Same author: [Alldebrid.NET](https://github.com/rogerfar/Alldebrid.NET) (AD), [Premiumize.NET](https://github.com/rogerfar/Premiumize.NET) (PM).
- [open-alldebrid](https://github.com/pierre-emmanuelJ/open-alldebrid) - (13★) OpenAPI 3.1 spec of the AllDebrid API, checked against the live API, with Go, TypeScript, Python, Kotlin, PHP, Rust, C# and Swift SDKs. AD.
- [torbox-kmp-client](https://github.com/LivingWithHippos/torbox-kmp-client) - (13★) Kotlin Multiplatform. TorBox.
- [node-all-debrid](https://github.com/TheBeastLT/node-all-debrid) - (6★) JavaScript. AD. Same author: [node-premiumize](https://github.com/TheBeastLT/node-premiumize) (PM), [node-debrid-link](https://github.com/TheBeastLT/node-debrid-link) (DL).
- [node-torbox-api](https://www.npmjs.com/package/node-torbox-api) - JavaScript. TorBox. Last release v0.1.4 (Nov 2024).
- [debrid-ts](https://www.npmjs.com/package/debrid-ts) - TypeScript. RD/AD/PM.
- [seedrcc](https://github.com/hemantapkh/seedrcc) - (95★) Python. Seedr.
- [put.io SDKs](https://github.com/putdotio) - Official. TypeScript (24★), Go (21★), Swift (19★). put.io.

## Deployment Stacks
- [sailarr-installer](https://github.com/JaviPege/sailarr-installer) - (74★) One-command installer for the Sailarr's Guide stack: RD, the *arrs and Plex.
- [TorBox-Media-Server](https://github.com/nordicnode/TorBox-Media-Server) - (55★) Zero-local-storage. One script sets up a TorBox-powered Docker media server (Linux/Windows).
- [Naralux/mediacenter](https://github.com/Naralux/mediacenter) - (41★) RD+*Arr infinite streaming docker-compose.
- [Surge](https://github.com/amcgready/Surge) - (33★) Docker deployment toolkit for Plex/Jellyfin/Emby stacks with Decypharr, cli_debrid and Zurg.
- [debrid-umbrel-app-store](https://github.com/Deudly/debrid-umbrel-app-store) - (0★) Debrid apps (Comet) for Umbrel. Unmaintained since 2024.
- [Maestro](https://github.com/clayboicardi/maestro) - (0★) MCP server: lets an AI agent read, audit and edit your Stremio addon configs (AIOStreams) for RD.
- [Easy AIOStreams](https://github.com/alpinezx/easy-aiostreams) - (57★) One-command installer for your own AIOStreams instance on a VPS or a home computer: Docker, Caddy with automatic HTTPS, login, backup/restore; home installs via Cloudflare Tunnel.
- [Viren's Docker Compose Template](https://github.com/Viren070/docker-compose-template) - (216★) From the AIOStreams author: Docker Compose files with Traefik and Authelia for 100+ apps, among them AIOStreams, Comet, MediaFusion, StremThru, Zurg, Decypharr, DebriDav, NzbDAV, AltMount, TorBox Manager and the *arrs.

## Comparison & Reference
- [Debrid Services Comparison](https://github.com/fynks/debrid-services-comparison) - (632★) Interactive web app comparing pricing, features, and 300+ supported hosts across all debrid services. [debridcompare.pages.dev](https://debridcompare.pages.dev)
- [FMHY: Debrid / Leeches](https://fmhy.net/downloading#debrid-leeches) - Free Media Heck Yeah's maintained section of debrid services, managers and leech tools.
- [StreamStack](https://streamstack.media) - 20+ tools documented, a debrid provider comparison table, and setup guides for Plex, Jellyfin, Kodi, Infuse, Stremio, Riven, TorBox and ElfHosted.
- [Savvy Guides](https://savvyguides.wiki) - Sailarr's Guide, Zurg and Riven guides.
- [stremio-addons.net](https://stremio-addons.net) - Community Stremio addon directory; successor to the [stremio-addons-list](https://github.com/stremio-community/stremio-addons-list) repo (1,149★, archived Nov 2025).
- [LeechListing](https://leechlisting.com) - Free PLG directory.
- [alternativeer.com](https://alternativeer.com/mydebrid) - 74 debrid and premium link generator alternatives with user ratings.
- [multihoster.org](https://multihoster.org) - English reviews of file hosts and multihosters. Dated: still covers Zippyshare, Openload and Zevera.
- ~~[mymultihoster.org](https://mymultihoster.org)~~ - English multihoster reviews. ⚠️ Dead (Nov 2026). Cloudflare 522, origin down; last archived Apr 2026.
- [TorBox Post-Mortems](https://github.com/TorBox-App/torbox-post-mortems) - (16★) Official write-ups of TorBox's large outages (Apr and Jun 2026).

<details>
  <summary>German-language comparisons</summary>

  - [multihosts.de](https://multihosts.de) - Multihoster tests since 2019, updated 2026.
  - [beyondo.one](https://www.beyondo.one/hosting/multihoster/) - 24 multihosters with filters for price, torrent and Usenet support.
  - [myfilehoster.de](https://www.myfilehoster.de/multihoster/) - 14 multihosters with host lists, Usenet/torrent support and prices.
  - [multio.ch](https://multio.ch) - Swiss multihoster ranking (2026); ranks High-Way first by its own stated choice.
  - [usefulvid.com](https://usefulvid.com/multihoster-sharehoster-im-vergleich-tabelle/) - Multihoster comparison table (last updated 2024).
  - [filehosterz.net](https://www.filehosterz.net/multihoster) - Multihoster comparison (last updated 2022).
</details>

## Communities
- [Debrid Media Manager + zurg + rex subreddit](https://www.reddit.com/r/debridmediamanager/)
- [Debrid Media Manager + zurg + rex Discord](https://discord.com/invite/7u4YjMThXP)
- [Real-Debrid subreddit](https://www.reddit.com/r/RealDebrid/) - (106k) Unofficial
- [r/TorBoxApp](https://www.reddit.com/r/TorBoxApp/) - (34k) TorBox ecosystem
- [r/AllDebrid](https://www.reddit.com/r/AllDebrid/) - (5.2k) Unofficial AllDebrid community
- [r/Premiumize](https://www.reddit.com/r/Premiumize/) - (14k) Official Premiumize community
- [r/StremioAddons](https://www.reddit.com/r/StremioAddons/) - (294k) Stremio addons
- [r/Stremio](https://www.reddit.com/r/Stremio/) - (232k) Stremio app
- [r/aiostreams](https://www.reddit.com/r/aiostreams/) - (7.8k) AIOStreams help forum
- [r/torrentio](https://www.reddit.com/r/torrentio/) - (16k) Unofficial Torrentio community
- [r/Nuvio](https://www.reddit.com/r/Nuvio/) - (66k) Nuvio, an open-source player for Stremio addons
- [r/Addons4Kodi](https://www.reddit.com/r/Addons4Kodi/) - (231k) Kodi debrid addons
- [r/Piracy](https://www.reddit.com/r/Piracy/) - (3.1M) General (heavy debrid discussion)
- [r/Debrid_Stream_App](https://www.reddit.com/r/Debrid_Stream_App/) - (12k) DebridStream app
- [r/DebridVault](https://www.reddit.com/r/DebridVault/) - (2.8k) Debrid Vault + Eclipse
- [r/SynclerApp](https://www.reddit.com/r/SynclerApp/) - (14k) Syncler
- [r/strmr](https://www.reddit.com/r/strmr/) - (1.8k) Strmr app
- [r/elfhosted](https://www.reddit.com/r/elfhosted/) - (1.4k) ElfHosted
- [r/seedboxes](https://www.reddit.com/r/seedboxes/) - (79k) Seedbox + cloud torrent discussion
- [r/DataHoarder](https://www.reddit.com/r/DataHoarder/) - (1M) Cloud torrent discussions
- ~~[r/Addons4Stremio](https://www.reddit.com/r/Addons4Stremio/)~~ - Stremio addon discussion. ⚠️ Dead (Nov 2026). Reddit: "We couldn't find that community".
- ~~[r/OnlyDebrid](https://www.reddit.com/r/OnlyDebrid/)~~ - OnlyDebrid service. ⚠️ Dead (Nov 2026). Restricted, 76 members, no posts since Jul 2025.
- [TorBox Discord](https://discord.gg/torbox) - (50k) Official
- [Stremio Community Discord](https://discord.stremio-addons.net) - (21k) r/StremioAddons and stremio-addons.net
- [AIOStreams Discord](https://discord.viren070.me) - (23k) AIOStreams and Viren070's addons
- [Comet Discord](https://discord.com/invite/UJEqpT42nb) - (5.1k)
- [Riven Discord](https://discord.riven.tv) - (3.9k)
- [DUMB Discord](https://discord.gg/T6uZGy5XYb) - (2k)
- [cli_debrid Discord](https://discord.gg/ynqnXGJ4hU) - (1.3k)
- [Savvy Servers Discord](https://discord.gg/vMSnNcd7m5) - (1.1k) Savvy Guides / Sailarr's Guide
- [plex_debrid Discord](https://discord.gg/jMpyFryfaj) - (2.7k) Project archived since 2024
- [ElfHosted Discord](https://discord.elfhosted.com) - (6.7k)
- ~~[SeerrBridge Discord](https://discord.gg/seerrbridge)~~ - ⚠️ Dead (Nov 2026). Invite no longer valid; the repo no longer links a Discord.

## Guides and Tutorials
- [A Sailarr's Guide to Plex + Real-Debrid](https://savvyguides.wiki/sailarrsguide/)
- [Streaming from Real-Debrid with Plex (*on ElfHosted*)](https://docs.elfhosted.com/guides/media/stream-from-real-debrid-with-plex/)
- [CoreLab Tech](https://corelab.tech) - Plex/Jellyfin + Real-Debrid with DUMB, Decypharr and Stremio setup guides (2026)
- [Stremio Perfect Setup](https://luckynumb3rs.github.io/stremio-perfect-setup/) - (334★) Beginner's guide to a Stremio/Nuvio setup with debrid and AIOStreams
- [Viren070 Guides](https://guides.viren070.me) - Stremio/debrid setup (Stremio guide last updated Aug 2024)
- [TorBox Help Center](https://support.torbox.app/en/) - Official answers on TorBox limits, features and troubleshooting
- [TROYPOINT](https://troypoint.com/real-debrid/) - Real-Debrid setup guide, comparisons, alternatives
- [Stremio + TorBox Guide](https://stremio-torbox-guide.pages.dev/) - Step-by-step Stremio setup with TorBox, using the Stremio Account Bootstrapper

## Miscellaneous
- [Awesome *Arr](https://github.com/Ravencentric/awesome-arr) - (4,464★)
- [MultiUp](https://multiup.io) - Upload to multiple file hosts simultaneously, plus link debriding. Heavily used in German scene.
- ~~[Go4Up](https://go4up.com)~~ - Multi-host upload service. ⚠️ Dead (Nov 2026). Domain parked (ParkLogic redirect page).

## Contribution Guidelines
Your contributions are welcome! Please refer to the [contributing guidelines](contributing.md) for information on how to contribute to this list.

## License
This list is available under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/). Feel free to share, modify, or use it as you see fit.

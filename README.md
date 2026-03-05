
📖 [View detailed folder documentation](details.md)

---
<a href="https://www.buymeacoffee.com/bol1JWG9V" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

# Portainer V2.5 Templates for Selfhosted Projects/Homelabs
## Latest Service Addition: 05/03/2026
This is a template focused on helping people spin up selfhosted services using Portainer, forked from [Qballjos](https://github.com/Qballjos/portainer_templates).

### Prerequisites

1. A server/NAS with docker installed.
2. A Portainer-CE setup.

### Installing

1. Login to your Portainer setup go to settings
2. Go to:  Application settings > App Templates
3. Add the url: `https://raw.githubusercontent.com/xneo1/portainer_templates/master/Template/template.json` then go to app templates and hit refresh at the top.

### Information
All templates are already configured to bind mount to various places on your drive. The following folders are all created in **/portainer/**

* **Files** - General file storage.
  * **AppData** - Subfolder where application data (unrelated to served data) is stored.
    * **Config** - Subfolder where configuration files for every container are stored.
* **Downloads** - Where bittorrent and usenet downloaders download files to.
* **TV** - Where tv shows are stored/moved to after downloaded.
* **Movies** - Where movies are stored/moved to after downloaded.
* **Music** - Where music is stored/moved to after downloaded.
* **Books** - Where books are stored/moved to after downloaded.
* **Comics** - Where comics are stored/moved to after downloaded.
* **Podcasts** - Where podcasts are stored/moved to after downloaded.

Go to [details page](details.md)


## App List
## 📅 Changelog Timeline

### 🗓️ 2026

| Date | Services Added |
|------|----------------|
| **05 Mar** | Filegator, Filestash, Diskover |
| **13 Feb** | Crowdsec Web UI |
| **09 Feb** | Solidtime, TRIP, Checkle, Lidify-FULL, Lidify, Aurral |
| **06 Feb** | PriceGhost, GoCostWeb |

### 🗓️ 2025

| Month | Date | Services Added |
|-------|------|----------------|
| **December** | 31/12 | Lunalytics |
| | 18/12 | DockerComposeMaker, Arcane |
| **October** | 17/10 | Netbox (Update/Correction) |
| **August** | 27/08 | Marreta |
| **June** | 02/06 | Kestra |
| **May** | 16/05 | Loggifly |
| | 12/05 | Dawarich |
| **March** | 16/03 | Checkmate |
| | 06/03 | Nutify |
| **February** | 19/02 | RomM |
| | 07/02 | Kasm Workspaces |
| **January** | 09/01 | Blinko |

### 🗓️ 2024

| Month | Date | Services Added |
|-------|------|----------------|
| **November** | 07/11 | N8n, Pinchflat |
| **October** | 29/10 | Nexterm |
| | 14/10 | Web Check |
| **September** | 20/09 | TinyMediaManager |
| | 03/09 | Hoarder |
| **August** | 29/08 | Markopolis |
| | 26/08 | Fusion, Medama Analytics |
| **July** | 26/07 | Beszel |
| **June** | 27/06 | Gathio |
| **May** | 27/05 | OpnForm |
| | 23/05 | Speedtest Tracker |
| | 01/05 | TimeTagger |
| **April** | 09/04 | NetAlertX |
| **March** | 11/03 | Stirling-PDF |
| | 04/03 | Pingvin-Share |
| **February** | 26/02 | Chibisafe |
| **January** | 03/01 | Webtrees, Wordpress |

### 🗓️ 2023

| Month | Date | Services Added |
|-------|------|----------------|
| **December** | 12/12 | Dokemon |
| **November** | 19/11 | Dockge |
| | 17/11 | Activepieces, Draw.io, netboot.xyz |
| | 03/11 | pve-exporter |
| **October** | 26/10 | Hauk, Shaarli, FlowiseAI |
| | 24/10 | Plane |
| | 18/10 | Bazarr (Stack Update) |
| | 16/10 | Feedcord, Fetchcord |
| **September** | 26/09 | Pingvin-share |
| **August** | 10/08 | Kapowarr |
| **July** | 10/07 | Mend.io Renovate |
| | 09/07 | Kiwix (ZIM reader) |
| **June** | 27/06 | Grocy |
| | 13/06 | Linkstack |
| | 08/06 | Ansible-semaphore |
| | 02/06 | Shiori |
| **May** | 23/05 | Funkwhale, Airsonic |
| | 09/05 | Tubearchivist |
| **April** | 07/04 | Flood UI with QTorrent |
| | 06/04 | WatchRARr, Unpackerr |
| **March** | 24/03 | Autobrr, Baikal |
| | 15/03 | Glances |
| | 07/03 | Gokapi |
| | 01/03 | Mastodon |
| **February** ⭐ | 21/02 | Snibox, Adguard Home, Overseerr, Organizr, Ombi, Nodered (all Stack), Tailscale |
| | 15/02 | Documize, Dashdot (Updated), Homarr |
| | 11/02 | Tabby, Remotely, Rport, Rust Desk, MeshCentral |
| | 05/02 | UpSnap, Excalidraw |
| | 04/02 | Tooljet |
| | 01/02 | Syncthing, Meilisearch, Ory Kratos (Oathkeeper), Ory Kratos (Standalone), Budibase, AppSmith |
| **January** | 27/01 | Moodle, ProxiTok, Miniflux, Traggo, FreeScout, Wger, Tdarr, Uptime Kuma (Update) |
| | 25/01 | Docker Container Stats |
| | 19/01 | Ferdium, NocoDB |
| | 17/01 | Codex |
| | 16/01 | Monica |
| | 13/01 | Whisparr, Midarr |
| | 03/01 | Signal proxy |

### 🗓️ 2022

| Month | Date | Services Added |
|-------|------|----------------|
| **December** | 25/12 | ChiefOnboarding |
| | 19/12 | Medusa (e-Commerce CMS), Castopod, Mautic |
| | 15/12 | YourSpotify |
| | 13/12 | Influxdb2 & Telegraf, Influxdb2 (standalone) |
| | 12/12 | Grafana (latest) |
| | 08/12 | Silverstripe CMS, FileStash |
| **November** | 30/11 | Readarr |
| | 24/11 | Mailpile, Appwrite |
| | 18/11 | Poste.io |
| | 03/11 | Lazytainer |
| **October** | 14/10 | iperf |
| **September** | 27/09 | Homepage |
| | 26/09 | I hate money |
| | 22/09 | Fireshare |
| **August** | 03/08 | Jump, Filepizza |
| | 01/08 | XWiki |
| **July** | 29/07 | Leantime, Jellyseer, Trudesk [WIP], Dash/Dashdot [WIP] |
| | 28/07 | Koillection [WIP] |
| | 22/07 | Zusam |
| | 21/07 | Vikunja |
| | 05/07 | massCode [no Docker] |
| | 01/07 | Facebox [WIP] |
| **June** | 01/06 | Eufy Security WS |
| **May** | 31/05 | Servas/Wallabag [WIP] |
| | 24/05 | Tandoor |
| | 10/05 | Trilium Notes |
| | 09/05 | Audiobookshelf |
| | 04/05 | Baserow, GoAccess for NPM Logs |
| **March** | 15/03 | Fenrus |
| **February** | 17/02 | Kavita |
| **January** | 28/01 | Pi.alert |
| | 11/01 | Navidrome |

### 🗓️ 2021 🎂 Inception

| Month | Date | Services Added |
|-------|------|----------------|
| **December** | 12/12 | Firefox |
| | 07/12 | Broadlink Manager, Homebridge, NUTS |
| | 06/12 | Dozzle |
| **November** | 16/11 | Flame Dashboard |
| | 12/11 | Snippet Box, Photoprism, Teleport |
| | 08/11 | Aria2 Pro, Apprise-API, Cryptofolio |
| | 05/11 | Umami.is, Matomo, N.eko Rooms, Changedetection.io, Ghost, Monica, Netbox, Freeboard, Nodered, Reveal.js, Statping, Frigate NVR, Ferdi |
| | 04/11 | Uptime-Kuma, Dashy, WebTop [ubuntu-kde], Littlelink-server |

---

## 🗂️ App Categories

<details>
<summary><strong>🔐 Authentication & Security</strong></summary>

- **Authelia** - SSO and 2FA portal
- **Vaultwarden** - Bitwarden-compatible password manager
- **Adguard** / **Adguard Home** - Network-wide ad blocker
- **Crowdsec** / **Crowdsec Web UI** - Collaborative security engine
- **Tailscale** - Zero-config VPN
</details>

<details>
<summary><strong>📊 Monitoring & Analytics</strong></summary>

- **Uptime Kuma** - Monitoring dashboard
- **Beszel** - System monitoring
- **Speedtest Tracker** - Internet speed monitoring
- **NetAlertX** - Network scanner and alerts
- **Glances** - System monitoring
- **Checkmate** - Status page
- **Lunalytics** - Analytics platform
- **Dashdot** / **Dash** - System dashboard
- **Medama Analytics** - Analytics
- **Grafana** - Data visualization
- **Influxdb2** - Time-series database
- **Telegraf** - Metrics collection
</details>

<details>
<summary><strong>🎬 Media & Entertainment</strong></summary>

- **Navidrome** - Music server
- **Audiobookshelf** - Audiobook server
- **Kavita** - Digital library
- **Jellyseer** - Media request manager
- **Bazarr** - Subtitle manager
- **TinyMediaManager** - Media management
- **Pinchflat** - YouTube downloader
- **Tubearchivist** - YouTube archive
- **YourSpotify** - Spotify stats
- **Funkwhale** - Audio streaming
- **Airsonic** - Music streaming
- **Castopod** - Podcast hosting
- **Kapowarr** - Comic book manager
- **Lidify** / **Lidify-FULL** - Music tools
- **Aurral** - Audio tool
</details>

<details>
<summary><strong>☁️ Productivity & Collaboration</strong></summary>

- **N8n** - Workflow automation
- **Plane** - Project management
- **Tooljet** - Low-code platform
- **AppSmith** - Internal tool builder
- **Budibase** - Low-code platform
- **Excalidraw** - Virtual whiteboard
- **Draw.io** - Diagramming tool
- **Solidtime** - Time tracking
- **Checkle** - Checklists
- **TRIP** - Travel/itinerary tool
- **Documize** - Documentation
- **Nextcloud** (implied) - File sync
</details>

<details>
<summary><strong>🧠 Knowledge Management</strong></summary>

- **Hoarder** - Bookmark manager
- **Blinko** - Note-taking
- **Trilium Notes** - Hierarchical notes
- **Bookstack** - Documentation wiki
- **Wiki.js** - Modern wiki
- **TiddlyWiki** - Non-linear notebook
- **XWiki** - Enterprise wiki
- **Shiori** - Bookmark manager
- **Shaarli** - Bookmarking
</details>

<details>
<summary><strong>🔧 Development & DevOps</strong></summary>

- **Portainer** - Container management
- **Dockge** - Docker compose stack manager
- **Kasm Workspaces** - Streaming workspaces
- **Code-Server** - VS Code in browser
- **Kestra** - Workflow orchestration
- **GitLab** / **Gitea** (implied) - Git repositories
- **Jenkins** (implied) - CI/CD automation
- **Ansible-semaphore** - Ansible UI
- **Drone** / **Woodpecker** (implied) - CI/CD
- **Mend.io Renovate** - Dependency updates
- **Docker Container Stats** - Monitoring
</details>

<details>
<summary><strong>🏠 Home Automation</strong></summary>

- **Homebridge** - HomeKit integration
- **Domoticz** - Home automation system
- **Nodered** - Flow-based programming
- **Eufy Security WS** - Security camera integration
- **Broadlink Manager** - IR/RF control
- **NUTS** - UPS monitoring
</details>

<details>
<summary><strong>📥 Download Management</strong></summary>

- **Aria2 Pro** - Download manager
- **Transmission-OpenVPN** - BitTorrent client with VPN
- **Flood UI** - qBittorrent web UI
- **qBittorrent** (implied) - Torrent client
- **Pinchflat** - YouTube downloader
- **Tubearchivist** - YouTube archive
- **WatchRARr** - RAR archive monitor
- **Unpackerr** - Archive extractor
- **Autobrr** - Download automation
- **SABnzbd** / **NZBGet** (implied) - Usenet clients
</details>

<details>
<summary><strong>🌐 Networking & Proxy</strong></summary>

- **Nginx** / **Nginx Proxy Manager** - Reverse proxy
- **Tailscale** - Mesh VPN
- **Netbox** - IPAM and DCIM
- **Lazytainer** - Lazy container starter
- **Dozzle** - Docker logs viewer
- **WireGuard** / **OpenVPN** (implied) - VPN
</details>

<details>
<summary><strong>🗄️ Databases & Storage</strong></summary>

- **InfluxDB2** - Time-series database
- **Grafana** - Data visualization
- **NocoDB** - Airtable alternative
- **Baserow** - Database GUI
- **Meilisearch** - Search engine
- **MariaDB** / **PostgreSQL** / **MySQL** (implied) - SQL databases
- **Redis** / **Memcached** (implied) - Caching
- **MinIO** (implied) - Object storage
</details>

<details>
<summary><strong>📧 Communication</strong></summary>

- **Ferdium** - Messaging aggregator
- **Signal proxy** - Signal proxy server
- **Murmur** - Voice chat server (Mumble)
- **Mattermost** / **Rocket.Chat** (implied) - Team chat
- **Poste.io** - Mail server
- **Mailpile** - Email client
- **FreeScout** - Help desk
</details>

<details>
<summary><strong>🛠️ Utilities & Tools</strong></summary>

- **Stirling-PDF** - PDF manipulation
- **Chibisafe** - File uploader
- **Pingvin-Share** - File sharing
- **FileStash** - File manager
- **Syncthing** - Continuous sync
- **Watchtower** - Container updates
- **Filepizza** - P2P file transfer
- **Gokapi** - Lightweight file server
- **Silverstripe CMS** - Content management
- **Wordpress** - Blogging platform
- **Ghost** - Publishing platform
- **Mastodon** - Social network
- **Lemmy** / **PieFed** (implied) - Reddit alternatives
</details>

<details>
<summary><strong>🎮 Gaming & Fun</strong></summary>

- **RomM** - ROM manager
- **Netboot.xyz** - Network boot
- **Steam** / **RetroArch** (implied) - Gaming
- **Minecraft** / **Terraria** (implied) - Game servers
</details>

<details>
<summary><strong>🔍 Search & Discovery</strong></summary>

- **Overseerr** - Media request
- **Ombi** - Media request
- **Jellyfin** / **Plex** / **Emby** (implied) - Media servers
- **Radarr** / **Sonarr** / **Lidarr** / **Readarr** / **Whisparr** - *arr stack
- **Prowlarr** - Indexer manager
- **Bazarr** - Subtitle manager
</details>

---

## 👥 Authors & Contributors

| Contributor | Role | Profile |
|-------------|------|---------|
| **Vagelis Fragkos** | *Maintainer* | [@xneo1](https://github.com/xneo1) |
| **NASHosted** | *Current Work* | [@nashosted](https://github.com/nashosted) |
| **SelfhostedPro** | *Current Work* | [@SelfhostedPro](https://github.com/SelfhostedPro) |
| **Jos Visser** | *Initial Work* | [@Qballjos](https://github.com/Qballjos) |
| **xe-nvdk** | *Template Conversion* | [@xe-nvdk](https://github.com/xe-nvdk) |
| **tbiering** | *Cleanup & Fixes* | [@tbiering](https://github.com/tbiering) |

[View all contributors](https://github.com/xneo1/portainer_templates/graphs/contributors)

---

<p align="center">
  <sub>Built with ❤️ for the self-hosted community</sub>
</p>

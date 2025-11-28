# Home-Server Development
## Docker Home Server Testing & Setup

Welcome to my home server development repository! Over the past 4-5 years, I’ve tested a wide variety of Docker containers for self-hosting and automation. This repo collects the containers I’ve found most useful, though some may be missing or not actively maintained. My goal is to organize each container into its own folder with a `docker-compose.yml` for easy setup and backup. Some configurations contain private information and will be refined before public release.

Below is a list of containers I’ve tested and recommend for various home server tasks.

- [adguard](./docker-compose/adguard)  
  *Network-wide ad blocker and privacy protection.*
- [amule](./docker-compose/amule)  
  *Peer-to-peer file sharing client for the eDonkey network.*
- [apprise](./docker-compose/apprise)  
  *Unified notification service for multiple platforms.*
- [audiobookshelf](./docker-compose/audiobookshelf)  
  *Self-hosted audiobook server and web player.*
- [authelia](./docker-compose/authelia)  
  *Authentication and authorization server for your applications.*
- [bazarr](./docker-compose/bazarr)  
  *Subtitle management for Radarr and Sonarr.*
- [beets](./docker-compose/beets)  
  *Music library organizer and tagger.*
- [calibre](./docker-compose/calibre)  
  *E-book management software.*
- [calibre-web](./docker-compose/calibre-web)  
  *Web-based interface for Calibre e-book library.*
- [chd-converter](./docker-compose/chd-converter)  
  *Tool for converting disk images to CHD format.*
- [code-server](./docker-compose/code-server)  
  *VS Code running on a remote server accessible through the browser.*
- [ddclient](./docker-compose/ddclient)  
  *Dynamic DNS update client.*
- [deemix](./docker-compose/deemix)  
  *Music downloader for Deezer.*
- [deluge](./docker-compose/deluge)  
  *Lightweight, open-source BitTorrent client.*
- [dillinger](./docker-compose/dillinger)  
  *Online Markdown editor.*
- [doublecommander](./docker-compose/doublecommander)  
  *Cross-platform file manager.*
- [elasticsearch](./docker-compose/elasticsearch)  
  *Distributed search and analytics engine.*
- [filebrowser](./docker-compose/filebrowser)  
  *Web-based file manager for your server.*
- [flaresolverr](./docker-compose/flaresolverr)  
  *Proxy server to bypass Cloudflare protection.*
- [gamevault](./docker-compose/gamevault)  
  *Game library manager.*
- [gameyfin](./docker-compose/gameyfin)  
  *Game streaming server.*
- [gitea](./docker-compose/gitea)  
  *Self-hosted Git service.*
- [glances](./docker-compose/glances)  
  *System monitoring tool.*
- [gluetun](./docker-compose/gluetun)  
  *VPN client for Docker containers.*
- [gmod](./docker-compose/gmod)  
  *Garry's Mod game server.*
- [grafana](./docker-compose/grafana)  
  *Analytics and monitoring dashboard.*
- [grifter](./docker-compose/grifter)  
  *Automation and scripting tool.*
- [headphones](./docker-compose/headphones)  
  *Music download manager for Usenet and torrents.*
- [heimdall](./docker-compose/heimdall)  
  *Application dashboard for your server.*
- [homarr](./docker-compose/homarr)  
  *Modern dashboard for managing your home server.*
- [homeassistant](./docker-compose/homeassistant)  
  *Open-source home automation platform.*
- [homebridge](./docker-compose/homebridge)  
  *HomeKit support for non-Apple devices.*
- [immich](./docker-compose/immich)  
  *Self-hosted photo and video backup solution.*
- [jackett](./docker-compose/jackett)  
  *API support for torrent indexers.*
- [jdownloader](./docker-compose/jdownloader)  
  *Download manager for various file hosts.*
- [jellyfin](./docker-compose/jellyfin)  
  *Open-source media server.*
- [joplin](./docker-compose/joplin)  
  *Note-taking and to-do application.*
- [jupyter](./docker-compose/jupyter)  
  *Interactive notebooks for code and data.*
- [kometa](./docker-compose/kometa)  
  *Media library metadata manager.*
- [lazylibrarian](./docker-compose/lazylibrarian)  
  *Book download and management tool.*
- [libation](./docker-compose/libation)  
  *Audiobook downloader and manager.*
- [lidarr](./docker-compose/lidarr)  
  *Music collection manager for Usenet and torrents.*
- [mailcow](./docker-compose/mailcow)  
  *Self-hosted mail server suite.*
- [mailserver](./docker-compose/mailserver)  
  *General purpose mail server.*
- [mariadb](./docker-compose/mariadb)  
  *Open-source relational database.*
- [mastadon](./docker-compose/mastadon)  
  *Decentralized social network server.*
- [mastodon](./docker-compose/mastodon)  
  *Decentralized social network server.*
- [mealie](./docker-compose/mealie)  
  *Recipe management and meal planning.*
- [mediacms](./docker-compose/mediacms)  
  *Open-source media content management system.*
- [minecraft-paper_itzg](./docker-compose/minecraft-paper_itzg)  
  *Minecraft Paper server by itzg.*
- [mkvtoolnix](./docker-compose/mkvtoolnix)  
  *Tools for working with Matroska media files.*
- [mongodb](./docker-compose/mongodb)  
  *NoSQL document database.*
- [mosquitto-eclipse](./docker-compose/mosquitto-eclipse)  
  *MQTT broker for IoT messaging.*
- [musicbrainz](./docker-compose/musicbrainz)  
  *Open music encyclopedia database.*
- [n8n](./docker-compose/n8n)  
  *Workflow automation tool.*
- [navidrome](./docker-compose/navidrome)  
  *Music streaming server.*
- [netbootxyz](./docker-compose/netbootxyz)  
  *Network boot server for OS installations.*
- [nginxproxymanager](./docker-compose/nginxproxymanager)  
  *Web proxy management with a GUI.*
- [node-red](./docker-compose/node-red)  
  *Flow-based programming for IoT.*
- [nostr-relay](./docker-compose/nostr-relay)  
  *Relay server for Nostr protocol.*
- [notifiarr](./docker-compose/notifiarr)  
  *Notification integration for media servers.*
- [nzbget](./docker-compose/nzbget)  
  *Usenet downloader.*
- [ombi](./docker-compose/ombi)  
  *Media request management for Plex/Emby/Jellyfin.*
- [open-assistant](./docker-compose/open-assistant)  
  *Open-source AI assistant.*
- [openbooks](./docker-compose/openbooks)  
  *Book search and download tool.*
- [organizr](./docker-compose/organizr)  
  *Unified web interface for your services.*
- [paperless-ng](./docker-compose/paperless-ng)  
  *Document management system.*
- [phpmyadmin](./docker-compose/phpmyadmin)  
  *Web-based MySQL/MariaDB administration.*
- [picard](./docker-compose/picard)  
  *Music tagger by MusicBrainz.*
- [pidgin](./docker-compose/pidgin)  
  *Multi-protocol chat client.*
- [plex](./docker-compose/plex)  
  *Media server for streaming your content.*
- [plex-image-cleanup](./docker-compose/plex-image-cleanup)  
  *Tool to clean up Plex image cache.*
- [pms-docker](./docker-compose/pms-docker)  
  *Plex Media Server Docker image.*
- [podgrab](./docker-compose/podgrab)  
  *Podcast downloader and manager.*
- [portainer](./docker-compose/portainer)  
  *Docker management GUI.*
- [portainer-be](./docker-compose/portainer-be)  
  *Portainer backend service.*
- [portainer-ce](./docker-compose/portainer-ce)  
  *Portainer Community Edition.*
- [postgres_data](./docker-compose/postgres_data)  
  *PostgreSQL database data container.*
- [prometheus](./docker-compose/prometheus)  
  *Monitoring and alerting toolkit.*
- [prowlarr](./docker-compose/prowlarr)  
  *Indexer manager for Usenet and torrents.*
- [qbittorrent](./docker-compose/qbittorrent)  
  *Open-source BitTorrent client.*
- [radarr](./docker-compose/radarr)  
  *Movie collection manager for Usenet and torrents.*
- [rainloop](./docker-compose/rainloop)  
  *Webmail client.*
- [readarr](./docker-compose/readarr)  
  *Book collection manager for Usenet and torrents.*
- [recyclarr](./docker-compose/recyclarr)  
  *Syncs trash/recycle settings for media managers.*
- [requestrr](./docker-compose/requestrr)  
  *Discord bot for media requests.*
- [romm](./docker-compose/romm)  
  *Retro game manager.*
- [romvault](./docker-compose/romvault)  
  *ROM management and auditing tool.*
- [sabnzbd](./docker-compose/sabnzbd)  
  *Usenet binary downloader.*
- [shoutrrr](./docker-compose/shoutrrr)  
  *Notification library for various services.*
- [sonarr](./docker-compose/sonarr)  
  *TV series collection manager for Usenet and torrents.*
- [soulseek](./docker-compose/soulseek)  
  *Peer-to-peer music sharing client.*
- [spotify-playlist-generator](./docker-compose/spotify-playlist-generator)  
  *Tool to generate Spotify playlists.*
- [spotisub](./docker-compose/spotisub)  
  *Spotify playlist subscription manager.*
- [sptnr](./docker-compose/sptnr)  
  *Spotify playlist and library manager.*
- [swag-letsencrypt](./docker-compose/swag-letsencrypt)  
  *Secure Web Application Gateway with Let's Encrypt.*
- [swag-letsencrypt_duckdns](./docker-compose/swag-letsencrypt_duckdns)  
  *SWAG with DuckDNS integration.*
- [tautulli](./docker-compose/tautulli)  
  *Plex usage monitoring and analytics.*
- [tdarr](./docker-compose/tdarr)  
  *Distributed media transcoding system.*
- [tellytv](./docker-compose/tellytv)  
  *IPTV proxy for Plex.*
- [traefik](./docker-compose/traefik)  
  *Modern reverse proxy and load balancer.*
- [trilium](./docker-compose/trilium)  
  *Hierarchical note-taking application.*
- [tubearchivist](./docker-compose/tubearchivist)  
  *YouTube archiving and management tool.*
- [tvheadend](./docker-compose/tvheadend)  
  *TV streaming server for DVB, ATSC, IPTV.*
- [unpackerr](./docker-compose/unpackerr)  
  *Automated extraction of archives for media managers.*
- [vscodium](./docker-compose/vscodium)  
  *Open-source build of VS Code.*
- [watchtower](./docker-compose/watchtower)  
  *Automatic update for Docker containers.*
- [web-dev-compose.yml](./docker-compose/web-dev-compose.yml)  
  *Web development Docker Compose setup.*
- [webgrabplus](./docker-compose/webgrabplus)  
  *EPG (Electronic Program Guide) grabber.*
- [wg-easy](./docker-compose/wg-easy)  
  *Simple WireGuard VPN management.*
- [whisper-webui](./docker-compose/whisper-webui)  
  *Web UI for OpenAI Whisper speech-to-text.*
- [wireguard](./docker-compose/wireguard)  
  *Fast, modern VPN tunnel.*
- [wireshark](./docker-compose/wireshark)  
  *Network protocol analyzer.*
- [xbackbone](./docker-compose/xbackbone)  
  *File sharing and image hosting platform.*
- [xteve](./docker-compose/xteve)  
  *IPTV proxy for Plex and Emby.*
- [youtube-dl-material](./docker-compose/youtube-dl-material)  
  *Web UI for youtube-dl downloads.*
- [youtube-dl-server](./docker-compose/youtube-dl-server)  
  *REST API for youtube-dl.*

## How To Use This Repo

### Prerequisites
- [Docker](https://docs.docker.com/get-docker/) installed on your server or local machine.
- [Docker Compose](https://docs.docker.com/compose/install/) (if using `docker-compose.yml` files).
- [Portainer](https://www.portainer.io/) (optional, for managing containers via a web UI).

### Getting Started

1. **Clone the Repository**
   ```sh
   git clone https://github.com/yourusername/home-server.git
   cd home-server
   ```

2. **Choose a Container**
   - Browse the folders listed above.
   - Each folder typically contains a `docker-compose.yml` or instructions for setup.

3. **Configure Environment Variables**
   - Some containers require environment variables or custom configuration files.
   - Review the comments in each `docker-compose.yml` or `.env` file within the container's folder for setup details.
   - Comments are marked with `#` for easy reference.

4. **Start a Container**
   ```sh
   cd <container-folder>
   docker-compose up -d
   ```
   - Or use Portainer to deploy and manage containers/stacks through its web interface.

5. **Access the Service**
   - Most services will be available at `http://localhost:<port>` or via your server’s IP.

### Updating Containers

- To update a running container:
  ```sh
  docker-compose pull
  docker-compose up -d
  ```
- Or use Portainer's update features. Portainer > Stack > Editor > Update The Stack > Tick (Re-pull image and redeploy)
- Or enable automatic updates with Watchtower.  
  Deploy Watchtower to monitor and update your containers automatically:
  ```sh
  docker run -d --name watchtower -v /var/run/docker.sock:/var/run/docker.sock containrrr/watchtower
  ```

### Stopping Containers

- To stop a container:
  ```sh
  docker-compose down
  ```
- Or stop containers from the Portainer dashboard.

### Backup & Restore

- Backup your configuration files and persistent data folders regularly.
- Restore by copying your backups back into the appropriate folders before starting the containers.

---

For container-specific instructions, see the comments within each file.
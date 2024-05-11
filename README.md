# Jellyfin All-In-One

## Environment variables

| Variable | Description | Example Value |
| --------------- | --------------- | --------------- |
| PUID | The User ID the containers will run as (see [https://docs.linuxserver.io/general/understanding-puid-and-pgid/](https://docs.linuxserver.io/general/understanding-puid-and-pgid/)) | 1000 |
| PGID | The group ID the containers will run as (see [https://docs.linuxserver.io/general/understanding-puid-and-pgid/](https://docs.linuxserver.io/general/understanding-puid-and-pgid/)) | 1000 |
| TZ | Your local timezone as per the [tz database](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) | Europe/Paris |
| TV_SHOWS_DIR | The directory where Jellyfin will look for TV shows | /mnt/remote/tvshows |
| MOVIES_DIR | The directory where Jellyfin will look for movies | /mnt/remote/movies |
| DOWNLOADS_DIR | The directory where the torrent client will (temporarily) store downloaded files | /mnt/remote/downloads |
| DOMAIN | The base domain URL that will be used for each service | mywebsite.com |
| SUBDOMAINS | The comma-separated list of subdomains for each service (default: wildcard) | prowlarr,radarr,sonarr,qbittorrent,jellyseerr,jellyfin |
| CERTPROVIDER | The cert provider to use (can be `letsencrypt` or `zerossl`) | zerossl |
| DNSPLUGIN | The DNS provider to use (see: [https://docs.linuxserver.io/general/swag/#create-container-via-dns-validation-with-a-wildcard-cert](https://docs.linuxserver.io/general/swag/#create-container-via-dns-validation-with-a-wildcard-cert)) | cloudflare |
| EMAIL | If using `zerossl` as `CERTPROVIDER`, your ZeroSSL email address | example@email.com |


## How to Setup

Coming soon

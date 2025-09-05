# Compose included
| Compose | Github-Action (Testing) | Github-Action (Merge) |
| ------- | :---------------------: | :-------------------: |
| [audiobooks](https://github.com/jeo1/docker-templates/tree/audiobooks) | ❌ |  |
| [cadvisor](https://github.com/jeo1/docker-templates/tree/cadvisor) | ✅ |  |
| [duckdns](https://github.com/jeo1/docker-templates/tree/duckdns) | ✅ |  |
| [gitea](https://github.com/jeo1/docker-templates/tree/gitea) | ✅ | ✅ |
| [grafana](https://github.com/jeo1/docker-templates/tree/grafana) | ✅ | ✅ |
| [graphite](https://github.com/jeo1/docker-templates/tree/graphite) | ✅ |  |
| [influxdb](https://github.com/jeo1/docker-templates/tree/influxdb) | ✅ |  |
| [jackett](https://github.com/jeo1/docker-templates/tree/jackett) | ✅ | ✅ |
| [jellyfin](https://github.com/jeo1/docker-templates/tree/jellyfin) | ✅ |  |
| [kuma](https://github.com/jeo1/docker-templates/tree/kuma) | ✅ | ✅ |
| [nginx](https://github.com/jeo1/docker-templates/tree/nginx) | ✅ | ✅ |
| [node-exporter-alpine](https://github.com/jeo1/docker-templates/tree/node-exporter-alpine) | ⚠️ |  |
| [node-exporter](https://github.com/jeo1/docker-templates/tree/node-exporter) | ✅ | ✅ |
| [plex](https://github.com/jeo1/docker-templates/tree/plex) | ⚠️ |  |
| [portainer](https://github.com/jeo1/docker-templates/tree/portainer) | ✅ | ✅ |
| [prometheus](https://github.com/jeo1/docker-templates/tree/prometheus) | ✅ | ✅ |
| [qbittorrent](https://github.com/jeo1/docker-templates/tree/qbittorrent) | ✅ |  |
| [radarr](https://github.com/jeo1/docker-templates/tree/radarr) | ✅ | ✅ |
| [sonarr](https://github.com/jeo1/docker-templates/tree/sonarr) | ✅ | ✅ |
| [tautulli](https://github.com/jeo1/docker-templates/tree/tautulli) | ✅ |  |
| [tdarr](https://github.com/jeo1/docker-templates/tree/tdarr) | ✅ |  |
| [twitch-dvr](https://github.com/jeo1/docker-templates/tree/twitch-dvr) | ❌ |  |

# Renovate Prep
| Container | Status | Notes |
| --------- | :----: | ----- |
| audiobooks |  | no github action |
| cadvisor | ❌ | latest did not match (may be out of date) |
| duckdns | ⚠️ | no merge created - now testing with latest |
| gitea | ✅ |  |
| grafana | ✅ |  |
| graphite |  | out of scope |
| influxdb |  | out of scope |
| jacket | ✅ | using latest sha |
| jellyfin | ❕ | using latest sha (untested) |
| kuma | ✅ |  |
| nginx | ✅ |  |
| node-exporter | ✅ |  |
| plex | ❕ | using latest sha (no merge yet) |
| portainer | ✅ |  |
| prometheus | ✅ |  |
| qbittorrent | ⚠️ | error with named verison - now testing with latest |
| radarr | ✅ |  |
| sonarr | ✅ |  |
| tautulli | ⚠️ | no pull with named verison - now testing with latest |
| tdarr | ✅ |  |
| twitch-dvr |  | look into checking if changes to dependencies |

# moved to v2
- audiobooks
- sonarr
- jackett
- nginx
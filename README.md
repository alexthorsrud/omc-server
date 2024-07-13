# omc-server
docker compose deploy stack using [itzg's docker-minecraft-server image](https://github.com/itzg/docker-minecraft-server) and [itzg's docker-mc-backup image](https://github.com/itzg/docker-mc-backup) (not yet implemented).

list of mods to be downloaded from modrinth are stored in `.env`. additional mod jars are loaded from `fabric-server-mods/` and mod configs are copied from `fabric-server-configs/`

docker-minecraft-server is configured to NOT load any dependencies.

note: dependency errors caused by:
- `fabric-seasons-delight-compat`
- `cultural-delights-fabric`

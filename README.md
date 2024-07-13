# omc-server
docker compose deploy stack using [itzg's docker-minecraft-server image](https://github.com/itzg/docker-minecraft-server) and [itzg's docker-mc-backup image](https://github.com/itzg/docker-mc-backup) (not yet implemented).

the list of mods to be downloaded from Modrinth are stored in the `MODRINTH_PROJECTS` environment variable that is set in the `.env` file

any additional mod jars are copied from `fabric-server-mods/` to the server's `mods/` directory

configuration files are copied from `fabric-server-configs/` to the server's `config/` directory

docker-minecraft-server is configured to NOT load any dependencies.

note: dependency errors caused by:
- `fabric-seasons-delight-compat`
- `cultural-delights-fabric`

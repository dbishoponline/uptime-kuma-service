# Uptime Monitoring (Kuma Uptime)

## Requirements

- Docker (latest version)
- Docker Compose (latest version)
- Taskfile (latest version)

## How to use?

Start Uptime monitoring on localhost

```
$ task start
```

Stop Uptime monitoring

```
$ task stop
```

## Backup and Restore

### Backup

1. Go to the running Kuma Uptime Monitoring site and navigate to the settings->backup page - <http://localhost:3001/settings/backup>

2. click "Export" button
3. copy the JSON into the existing `backup.json` file -or- create a new JSON file.

### Restore

1. Got to <http://localhost:3001/settings/backup> and click "Choose file".
2. Then browse and choose the backup.json file previously saved at the root of the project dir.
3. Then click "Import" button

## Resources

Kuma-uptime Github Repo
<https://github.com/louislam/uptime-kuma>

Docker-compose example
<https://github.com/louislam/uptime-kuma/blob/master/docker/docker-compose.yml>

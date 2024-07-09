# nats
Примеры файлов для курса "Телеграм-боты на Python: продвинутый уровень"

Для создания server.conf
1. docker compose up
2. docker volume inspect nats_nats_config
liv@singularity:~/nats$ docker volume inspect nats_nats_config
[
    {
        "CreatedAt": "2024-07-09T10:25:48+07:00",
        "Driver": "local",
        "Labels": {
            "com.docker.compose.project": "nats",
            "com.docker.compose.version": "2.28.1",
            "com.docker.compose.volume": "nats_config"
        },
        "Mountpoint": "/var/lib/docker/volumes/nats_nats_config/_data",
        "Name": "nats_nats_config",
        "Options": null,
        "Scope": "local"
    }
]
3. sudo nano /var/lib/docker/volumes/nats_nats_config/_data/server.conf
  

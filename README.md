# Custom Nextcloud installation

See https://github.com/nextcloud/docker

## Setup

```
echo "POSTGRES_DB_LOCATION=/path/to/database/dir/" > .env
echo "NEXTCLOUD_DATA_LOCATION=/path/to/nextcloud/dir/" >> .env
docker-compose up -d

```

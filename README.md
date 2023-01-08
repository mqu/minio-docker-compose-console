# Description

This project demonstrate how to embeded :

- minio
- minio console with subpath
- nginx

# Usage

```
git clone https://github.com/mqu/minio-docker-compose-console.git minio
cd minio
docker-compose up -d
```

open URL: http://localhost:8888/ ; login: minio / minio1234

You can of course change values : localhost, port (8888) according to your needs.

# Fixme

- Browser server show a  `500` error opening : `http://localhost:8888/console/api/v1/subnet/info`


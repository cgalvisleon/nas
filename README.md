## Deploy local

```bash
docker network create proxy

docker compose -p nas -f ./local.yml up -d
docker compose -p nas -f ./local.yml down
```

### Minio

http://pi.local:9001

USER_NAME=test
USER_PASSWORD=testtest

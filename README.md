## Deploy local

```bash
docker network create proxy

docker compose -p nas -f ./local.yml up -d
docker compose -p nas -f ./local.yml down
```

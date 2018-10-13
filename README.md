# Example config for ceriwi

## How to use this config
```bash
docker-compose up -d
docker exec myceriwi run --db-migration
cat config/blog-1.json | docker exec -i myceriwi run --config
```

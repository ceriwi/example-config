# Example config for ceriwi

## How to install ceriwi crawler

```bash
docker-compose up -d
docker-compose exec myceriwi run --db-migration
```

## How to run ceriwi crawler with a file config

```bash
cat config/blog-1.json | docker-compose exec -T myceriwi run --config
```

## How to test config without save data

```bash
cat config/blog-2.json | docker-compose exec -T myceriwi run --config-test
```

## How to download file after run crawler

```bash
cat config/intermediate-remove-after-select-1.json | docker-compose exec -T myceriwi run --config
cat config/intermediate-remove-after-select-1.json | docker-compose exec -T myceriwi run --config-download
```

## Link on this project

Documentation : [https://ceriwi.github.io/ceriwi/](https://ceriwi.github.io/ceriwi/).  
Page for test : [https://ceriwi.github.io/test/](https://ceriwi.github.io/test/).  
sample config : [https://github.com/ceriwi/example-config/tree/master/config](https://github.com/ceriwi/example-config/tree/master/config)


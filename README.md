# Redash Docker That Runs

How to run redash docker with this image

I still don't know why we need this folder, probably we don't since it stays empy, but it was present in developer version of the docker.

1. Setup database:
```
docker-compose run --rm server create_db
```

2. Run the docker:
```
docker-compose up -d
```
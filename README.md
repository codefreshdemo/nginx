* Build image

```
docker build -t nginx_image -f Dockerfile.openresty .
```

* Run composition

```
docker-compose -f docker-compose.yml up
```
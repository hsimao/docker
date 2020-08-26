# Start Develop Container

```bash
docker-compose up

# close
docker-compose down
```

# Build Production image

```bash
# copy container id for start nginx
docker build .

```

# Start Nginx Container

```bash
docker run -p 8080:80 [containerId]
```

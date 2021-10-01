## Docker Project 3

Starting Development Server
```bash
docker build -f Dockerfile.dev .
docker run -it -p 3000:3000 -v /app/node_modules -v $(pwd):/app <imageid>
```
Using Docker Compose
```bash
docker-compose up
```
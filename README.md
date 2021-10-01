## Docker Project 3

### Starting Development Server
Using Dockerfile
```
docker build -f Dockerfile.dev .
docker run -it -p 3000:3000 -v /app/node_modules -v $(pwd):/app <imageid>
```
Using Docker Compose
```
docker-compose up
```

### Executing Tests
```
docker run -it <imageid> npm run test
```
```
docker-compose up
docker exec -it <containerid> npm run test
```
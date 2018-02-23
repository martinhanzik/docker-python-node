# Node.js with Python based on [python/3.6.4-alpine](https://hub.docker.com/_/python/)
- Node: v9.6.1
- yarn: 1.3.2
- Python: 3.6.4

----
### Pull from Docker Hub
```
docker pull hanziq/python-node:latest
```

### Build from GitHub
```
docker build -t hanziq/python-node github.com/hanziq/docker-python-node
```

### Run image
```
docker run -it hanziq/nodejs-python bash
```

### Use as base image
```Dockerfile
FROM hanziq/python-node:latest
```

## Disclaimer
> This is experimental and might break from time to time. Use at your own risk!

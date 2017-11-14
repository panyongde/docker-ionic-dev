# Latest Ionic
### based on the latest Cordova with the latest Android and the latest Node.js
----
### Pull from Docker Hub
```
docker pull panyongde/ionic:latest
```

### Build from GitHub
```
docker build -t panyongde/ionic github.com/panyongde/docker-ionic
```

### Run image
```
docker run -it panyongde/ionic bash
```

### Use as base image
```Dockerfile
FROM panyongde/ionic:latest
```
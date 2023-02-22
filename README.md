# comp-flower

## Docker ビルド
```
docker-compose up -d --build
```

## Docker images
```
% docker images
REPOSITORY           TAG       IMAGE ID       CREATED        SIZE
training-flower-cafe   latest    95a716d797ca   2 months ago   375MB
```

## Docker ps
```
% docker ps -a 
CONTAINER ID   IMAGE                COMMAND                  CREATED         STATUS         PORTS                NAMES
9157fd6b4c73   training-flower-cafe   "docker-php-entrypoi…"   2 minutes ago   Up 2 minutes   0.0.0.0:80->80/tcp   training-flower-cafe
```

## URL
```
http://localhost/
```

# comp-flower

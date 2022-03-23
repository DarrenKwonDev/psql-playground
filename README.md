```
  docker-compose up -d --build
  docker exec -it CONTAINER_ID /bin/bash # 컨테이너 내부 접속
  psql -h 127.0.0.1 -U ${username} # 접속
```

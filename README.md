# docker-mysql  

## Usage  
```
docker run --name=mysql-test1 -d \
    -p 12222:22 \
    -p 13308:3306 \
    -e 'DB_REMOTE_ROOT_NAME=root' \
    -e 'DB_REMOTE_ROOT_PASS=654321' \
    -e 'DB_REMOTE_ROOT_HOST=%' \
    cloudcube/mysql
```


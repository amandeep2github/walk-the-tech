## install
either run docker image or download
```
wget https://download.redis.io/redis-stable.tar.gz
tar xzf redis-stable.tar.gz
```

## Info
redis is single threaded from command POV

## commands
redis-server  
redis-benchmark  
redis-cli  

These are installed in /usr/local/bin/redis-server by 
```
make install
```

## redis-cli
> commands
config get dir  
shutdown save  


## storage
key value  
data types can be string, hashes, lists, sets, sorted sets with range queries

## docker
```
docker run --name=redis-devel --publish=6379:6379 --hostname=redis --restart=on-failure --detach redis:latest
```
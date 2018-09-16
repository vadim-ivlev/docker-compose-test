docker-compose test with external networks
--------------------


How to run containers defined in different `docker-compose` files that can talk to each other.


To run:

```sh
docker-compose -f docker-compose-redis.yml up -d
docker-compose  up -d


```

Instead od defining external neworks, you can use 
```sh
network_mode: bridge
```

## How To
run comando

```
docker-compose up -d

```

for init cluster
```
docker exec -it roach1 cockroach init --insecure
```

When for acess dashboard open http://localhost:8080

![dashboard](https://github.com/devalexandre/cockroachdb/blob/master/img/dashboard.png?raw=true)

## Todo
Understand why access to the bank does not only work with access to the dashboard.

[] access database with loadbalance



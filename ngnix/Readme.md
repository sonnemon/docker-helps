**Ngnix**

localhost to url without port.

Get IP from extra_hosts

```bash
    ifconfig en0 | grep inet | grep -v inet6 | awk '{print $2}'
```

Start using

```bash
    docker-compose -f docker-compose.yaml up -d
```

Stop using

```bash
    docker-compose -f docker-compose.yaml down
```
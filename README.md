# docker-files
Docker files for various services.


Bridge network:
```bash
docker network create \
 --driver=bridge \
 --subnet=10.42.0.0/24 \
 --gateway=10.42.0.1 \
dbridge```
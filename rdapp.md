Após subir os containers do RDAPP pela primeira vez execute os seguintes comandos:

```bash
docker exec -it dspace /dspace/bin/dspace registry-loader -m /dspace/config/registries/local-types.xml

docker exec -it dspace bash

apt-get update
apt-get install -y imagemagick ghostscript

```

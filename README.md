###  Vanilla forum docker image based on webdevops.io for freundeskreis jahrtausendfeld e.V..
---

to use with  [nginx-proxy](https://github.com/nginx-proxy/nginx-proxy) & [docker-letsencrypt-nginx-proxy-companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion) 

---
change  **docker-compose.yml**
```
...
      VIRTUAL_HOST: board.jahr1000feld.de
      VIRTUAL_PORT: 80
      LETSENCRYPT_HOST: board.jahr1000feld.de
...
```
to
```
...
      VIRTUAL_HOST: your.domain.tld
      VIRTUAL_PORT: 80
      LETSENCRYPT_HOST: your.domain.tld
...
```


###  [Vanilla](https://github.com/vanilla/vanilla) forum docker image based on webdevops.io for freundeskreis jahrtausendfeld e.V..
---
![docker pulls](https://img.shields.io/docker/pulls/lokke/vanilla.svg) ![docker automated](https://img.shields.io/docker/automated/lokke/vanilla.svg) ![docker cloud](https://img.shields.io/docker/cloud/build/lokke/vanilla.svg) 


to use with  [nginx-proxy](https://github.com/nginx-proxy/nginx-proxy) & [docker-letsencrypt-nginx-proxy-companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion) 

---
change  **docker-compose.yml**
```
...
      VIRTUAL_HOST: jahr1000feld.de
      VIRTUAL_PORT: 80
      LETSENCRYPT_HOST: jahr1000feld.de
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


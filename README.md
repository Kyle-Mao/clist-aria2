### A docker Image with a pre-installed `aria2` for blist

#### Usage

```bash
docker run -d --restart=always -v /etc/blist:/opt/blist/data -p 5244:5244 -e PUID=0 -e PGID=0 -e UMASK=022 --name="blist" xhofe/blist-aria2:latest
```
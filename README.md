### Plex media server

![Plex logo](https://raw.githubusercontent.com/HipsterWhale/docker-plex-server/master/plex-logo.jpg)

#### Information

This image of plex will :

 - Use Plex Version `1.2.2.2857-d34b464` (it will be maintained up to date)
 - Store plex configuration in `/etc/plex`

#### Usage

```
#!/bin/bash
docker run -d \
  -v /mnt/volumes/plex:/etc/plex \
  -v /mnt/my_medias:/medias \
  --name=plex bahaika/plex-server
```

# Services

# Public Privacy Services
## Homepage
- Domain: exonip.de
- Host: 0.0.0.0:80, 0.0.0.0:443
- Directory: /var/www/exonip.de/, /etc/nginx/sites-enabled/

## Invidious
- Domain: invidious.exonip.de
- Host: 127.0.0.1:2000, 127.0.0.1:2001 (database), 193.37.152.198:2000 (contabo server), tav72y9sv.exonip.de (heroku eu: see notes in /etc/nginx/nginx.conf)
- Directory: /home/docker/invidious, /etc/nginx/sites-enabled, /etc/nginx/

## Nitter
- Domain: nitter.exonip.de
- Host: 127.0.0.1:2002
- Directory: /home/docker/nitter, /etc/nginx/sites-enabled

## Bibliogram
- Domain: bibliogram.exonip.de
- Host: 127.0.0.1:2003
- Directory: /home/docker/bibliogram, /etc/nginx/sites-enabled

## Libreddit
- Domain: libreddit.exonip.de
- Host: 127.0.0.1:2004
- Directory: /home/docker/libreddit, /etc/nginx/sites-enabled

## Whoogle
- Domain: search.exonip.de
- Host: 127.0.0.1:2005
- Directory: /home/docker/whoogle, /etc/nginx/sites-enabled
- 
## Searx
- Domain: searx.exonip.de
- Host: 127.0.0.1:2006 (searx), 127.0.0.1:2007 (morty)
- Directory: /home/docker/searx
- 
## Bitwarden
- Domain: bitwarden.exonip.de
- Host: 127.0.0.1:2008
- Directory: /home/bitwarden/

## Teddit
- Domain: teddit.exonip.de
- Host: 127.0.0.1:2009
- Directory: /home/docker/teddit

# Private Services
## Cloud
- Domain: cloud.exonip.de
- Host 127.0.0.1:3000 -> / , 127.0.0.1:3001 -> /seafhttp, 0.0.0.0:81
- Directory: /home/docker/seafile, /etc/nginx/sites-enabled/

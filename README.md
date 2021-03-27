# Docker container for Opencart

- PHP-FPM 7.3
- Nginx
- MySQL 5.7
- Adminer
- xDebug 3 

## MySQL settings
host: **db** (container name)

user: **admin**

pass: **1234567**

## Hostname: oc.dev

## Adminer host: localhost:8080

## xDebug
**Need to set:**

xdebug.client_host (*images/php/mods/xdebug.ini*) = container IP (Linux)

xdebug.client_host = host.docker.internal (Win|Mac)

#### PhpStom
idekey = PHPSTORM
Server name = Docker
 


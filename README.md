# dockerized-docs-percona-server

# What is it? #
Dockerzied Percona-Server documentation for offline use.

# Image description #
- Base image: Base image: `httpd:2.4.25-alpine`
- The most current `5.7` branch is cloned and built using sphinx
- Percona-Server documentation directory (`/percona-server/doc/build/html`) is linked to httpd `DocumentRoot` (`/var/www/html`)  

# How to use this image #

```console
$ docker run -d genadipost/dockerized-docs-percona-server

```

You can test it by visiting http://container-ip:80

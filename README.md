# apache2-php7-phalcon
Apache+PHP7 with a catchall virtual host and Phalcon 2.1.x installed

Based off of debian:latest

Running this is easy:
```
docker run -p 80:80 -v /var/www:/var/www -p 80:80 cbaldwinson/server-phalcon
```
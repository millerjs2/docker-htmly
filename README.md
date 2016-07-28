# Docker image based on Alpine linux, with nginx and php-fpm

Lightwight Docker image for the (latest) PHP-FPM and Nginx based on [AlpineLinux](http://alpinelinux.org)

* Small image: 45MB
* New packages (alpine:latest) 2015-04-03:
  
### Usage
```bash
sudo docker run -v /data:/DATA -p 80:80 psitrax/php-nginx
```

Browse to http://dockerip/index.php to view the phpinfo() output.

### Volume structure

* `htdocs`: Webroot
* `logs`: Nginx/PHP error logs

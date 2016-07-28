# Docker image based on Alpine linux, with nginx and php-fpm

Lightwight Docker image for the (latest) PHP-FPM and Nginx based on [AlpineLinux](http://alpinelinux.org)

* Small image: 45MB
* New packages (alpine:latest)
  
### Usage
Build the image:
```bash
docker build -t you/imagename
```
Start the image:
```bash
docker run -v /data:/data -p 80:80 you/imagename
```

Browse to http://dockerip/index.php to view the phpinfo() output.

### Volume structure

* `htdocs`: Webroot
* `logs`: Nginx/PHP error logs

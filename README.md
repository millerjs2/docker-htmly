# Docker image for [HTMLy](https://github.com/danpros/htmly) blogging platform

Currently doesn't work - in progress.

### Usage
Build the image:
```bash
docker build -t you/imagename .
```
Start the image:
```bash
docker run -v /data:/data -p 80:80 you/imagename
```

Browse to http://dockerip/installer.php to start the install process.

### Volume structure

* `htdocs`: Webroot
* `logs`: Nginx/PHP error logs

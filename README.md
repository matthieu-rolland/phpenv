## BASIC Debian PHP / symfony dev environment

### Includes:

- PHP 8.1
- Nginx
- MySQL 8
- Misc: Symfony installer, git...

### Getting started:

From the root of this project:

`docker-compose up -d --build`

### Configuration: 

Nginx is configured with root being `/var/www`, this can be changed in `nginx/default.conf`, see the `root` parameter. (don't forget to restart then).
 

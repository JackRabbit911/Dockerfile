# Dockerfile
Dockerfile for apache + php 8.1 + php extensions

### Example
FROM jackrabbit911/apache_php8.1_plus_extensions:latest
RUN mkdir -p /var/www/htdocs/www
COPY default.conf /etc/apache2/sites-available/000-default.conf

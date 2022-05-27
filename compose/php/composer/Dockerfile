FROM composer:latest

# ADD and set Group
RUN addgroup -g 1000 laravel && adduser -G laravel -g laravel -s /bin/sh -D laravel

# Set Profile to All Files
#RUN chown -R laravel:laravel /var/www/html
RUN whoami 
RUN id -u
WORKDIR /var/www/html

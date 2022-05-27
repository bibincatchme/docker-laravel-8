FROM nginx:stable-alpine

# ADD Custom Config
#ADD ./compose/nginx/nginx.conf /etc/nginx/nginx.conf
ADD ./compose/nginx/default.conf /etc/nginx/conf.d/default.conf

# Make Directory - Workspace
RUN mkdir -p /var/www/html

# ADD and set Group
RUN addgroup -g 1000 laravel && adduser -G laravel -g laravel -s /bin/sh -D laravel
#COPY ./code /var/www/html
# Set Group to Workspace
RUN chown laravel:laravel /var/www/html
RUN ls -l
RUN pwd
#RUN pwd \
#  sudo find ./ -type f -exec chmod 644 {} \; \
#  sudo find ./ -type d -exec chmod 755 {} \;
#RUN chmod -R 777 /var/www/html/storage


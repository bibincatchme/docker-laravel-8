FROM php:7.4-fpm-alpine

COPY ./compose/workspace/run.sh /tmp
RUN chmod 777 /tmp/run.sh
RUN cat /tmp/run.sh
WORKDIR /var/www/html

#ENTRYPOINT ["/tmp/run.sh"]

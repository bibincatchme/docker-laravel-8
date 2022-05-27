FROM node:16.6.1
COPY ./compose/npm/run.sh /tmp
# Run in work space
WORKDIR /var/www/html
RUN  chmod +x /tmp/run.sh
ENTRYPOINT ["/tmp/run.sh"]

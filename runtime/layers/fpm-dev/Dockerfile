ARG LAYER_IMAGE
FROM $LAYER_IMAGE

COPY ./php-fpm.conf /opt/bref/etc/php-fpm.conf
EXPOSE 9000
CMD /opt/bin/php-fpm --nodaemonize --fpm-config /opt/bref/etc/php-fpm.conf

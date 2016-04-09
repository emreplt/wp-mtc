FROM wordpress

RUN usermod -u 1000 www-data
RUN chmod -R 777 /var/www/html

# RUN apt-get update && \
#     apt-get -y install php5-xdebug
#
# # # RUN DOCKER_HOST_IP=$(netstat -nr | grep '^0\.0\.0\.0' | awk '{print $2}')
# # RUN echo "xdebug.remote_enable=on" >> /etc/php5/mods-available/xdebug.ini
# # RUN echo "xdebug.remote_host=192.168.99.1" >> /etc/php5/mods-available/xdebug.ini
# # RUN echo "xdebug.remote_port=9000" >> /etc/php5/mods-available/xdebug.ini
#
# RUN echo "[xdebug]" >> /usr/local/etc/php/php.ini
# RUN echo "xdebug.default_enable=1" >> /usr/local/etc/php/php.ini
# RUN echo "xdebug.remote_enable=1" >> /usr/local/etc/php/php.ini
# RUN echo "xdebug.remote_host=192.168.99.1" >> /usr/local/etc/php/php.ini
# RUN echo "xdebug.remote_port=9000" >> /usr/local/etc/php/php.ini
# RUN echo "xdebug.remote_handler=dbgp" >> /usr/local/etc/php/php.ini
# RUN echo "xdebug.remote_autostart=1" >> /usr/local/etc/php/php.ini
# RUN echo "zend_extension=/usr/lib/php5/20131226/xdebug.so" >> /usr/local/etc/php/php.ini
#
#
#
# ENV XDEBUG_PORT 9000

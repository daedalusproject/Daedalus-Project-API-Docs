FROM daedalusproject/base_nginx_light
MAINTAINER Álvaro Castellano Vela <alvaro.castellano.vela@gmail.com>

COPY containers/common/nginx/vhost /etc/nginx/sites-enabled/default
COPY --chown=www-data:www-data web_deploy /var/www/daedalus-core-docs

# forward request and error logs to docker log collector
RUN ln -sf /dev/stdout /var/log/nginx/access.log \
	&& ln -sf /dev/stderr /var/log/nginx/error.log

EXPOSE 80

STOPSIGNAL SIGTERM

CMD ["nginx", "-g", "daemon off;"]

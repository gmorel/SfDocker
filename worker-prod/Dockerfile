FROM symfony/worker-base

MAINTAINER Markus Weiland <mw@graph-ix.net>

########

RUN mkdir -p /var/www/api
ADD code.tar.gz /var/www/api

RUN chown -R www-data:www-data /var/www/api/app/cache /var/www/api/app/logs

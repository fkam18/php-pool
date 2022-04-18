# php-pool
docker-compose setup for a pool of php containers 

Based on: https://github.com/mzazon/php-apache-mysql-containerized

The idea is to use proxypass to forward http request to respective php containers taking advantage of specific container setup for certain URL's

Based on mzazon's setpu, two php containers php1 and php2 are configured.

Different volumes are assigned to each, but mapped via apache proxy to the same DocumentRoot space.


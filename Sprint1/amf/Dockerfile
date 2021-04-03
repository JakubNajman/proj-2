FROM ubuntu:groovy

RUN apt-get -y update
RUN apt-get -y install nginx

COPY index.html /tmp/index.html
COPY default /etc/nginx/sites-available/default

EXPOSE 80/tcp

CMD /usr/sbin/nginx && tail -f /dev/null


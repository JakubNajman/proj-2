From ubuntu

#Install NGINX
RUN apt-get -y update && apt-get -y install nginx

#Copy the local index.html to /tmp
COPY index.html /tmp/index.html
COPY default /etc/nginx/sites-available/default

EXPOSE 80/tcp

CMD /usr/sbin/nginx && tail -f /dev/null

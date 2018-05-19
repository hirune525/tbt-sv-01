# ./websv01/Dockerfile
FROM nginx:alpine
LABEL maintainer "rtbt <hirune525@gmail.com>"
COPY ./root/default.conf /etc/nginx/conf.d/
RUN mkdir -p /var/www
COPY ./root/var/www/ /var/www/

FROM nginx:alpine

RUN rm -fr /etc/nginx/conf.d/default.conf
COPY html /usr/share/nginx/html
COPY docker/nginx/nginx.conf /etc/nginx/conf.d

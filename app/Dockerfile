FROM nginx:1.23-alpine

RUN sed -E 's/80;/8080;/' -i /etc/nginx/conf.d/default.conf

COPY index.html /usr/share/nginx/html/index.html

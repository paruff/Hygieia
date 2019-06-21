FROM docker.io/nginx:latest

COPY default.conf /etc/nginx/conf.d/default.conf
COPY html /usr/share/nginx/html
RUN chown -R nginx:nginx /usr/share/nginx/html/

EXPOSE 80 443

CMD nginx -g "daemon off;"

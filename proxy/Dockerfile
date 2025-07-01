FROM nginx:mainline

RUN [ "rm", "-rf", "/etc/nginx/conf.d/default.conf" ]
COPY ./nginx-settings/*.conf /etc/nginx/conf.d/

EXPOSE 80 443 8080
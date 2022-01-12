FROM nginx:latest

COPY ./default.conf /etc/nginx/conf.d/default.conf
COPY ./includes/ /etc/nginx/includes/

COPY ./404.html /var/www/html/404.html
# copy chứng chỉ ssl cho server nginx
COPY ./ssl/ /etc/ssl/certs/nginx/
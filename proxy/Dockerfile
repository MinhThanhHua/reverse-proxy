FROM nginx:latest

COPY ./default.conf /etc/nginx/conf.d/default.conf

COPY ./backend-not-found.html /var/www/html/backend-not-found.html

COPY ./includes/ /etc/nginx/includes/

# copy chứng chỉ ssl cho server nginx
COPY ./ssl/ /etc/ssl/certs/nginx/
FROM nginx:latest

COPY nginx.conf /etc/nginx/nginx.conf

RUN mkdir /etc/nginx/ssl
COPY ssl/nginx.key /etc/nginx/ssl/nginx.key
COPY ssl/nginx.crt /etc/nginx/ssl/nginx.crt
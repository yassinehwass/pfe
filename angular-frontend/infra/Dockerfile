FROM nginx:1.22.1-alpine
# node:12.12.0-stretch image utilisée pour le build

EXPOSE 80

COPY nginx.conf /etc/nginx/nginx.conf

WORKDIR /usr/share/nginx/html

COPY dist/ .

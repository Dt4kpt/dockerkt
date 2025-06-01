FROM ubuntu:22.04

RUN apt update && apt install -y wget curl nginx

COPY index.html /var/www/html/
COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80 443

CMD ["nginx", "-g", "daemon off;"]

FROM ubuntu
RUN apt-get update && apt-get install nginx -y
ADD index.html /usr/share/nginx/html/
ADD default /etc/nginx/sites-enabled/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

FROM ubuntu
RUN apt-get update && apt-get install nginx -y && echo "Pod: $(hostname)" > /usr/share/nginx/html/index.html
ADD default /etc/nginx/sites-enabled/
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]

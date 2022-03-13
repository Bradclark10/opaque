FROM ubuntu
RUN apt-get update
RUN apt-get install nginx -y
WORKDIR /app
COPY index.html /var/www/html/
COPY about.html /var/www/html/
COPY cat.css /var/www/html/
EXPOSE 80
CMD ["nginx","-g","daemon off;"]

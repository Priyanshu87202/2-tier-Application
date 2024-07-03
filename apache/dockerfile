FROM ubuntu:latest
RUN apt-get update && apt-get install -y apache2
RUN apt install php libapache2-mod-php php-mysql -y
EXPOSE 80
COPY . /var/www/html/
CMD ["apachectl","-D","FOREGROUND"]
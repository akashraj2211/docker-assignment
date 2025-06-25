FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y apache2 && \
    apt-get clean

RUN echo $"<h1>Welcome to My Apache Server - Your Name</h1>" > /var/www/html/index.html


CMD ["apache2ctl", "-DFOREGROUND"]

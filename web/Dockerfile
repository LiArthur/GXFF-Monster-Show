FROM ubuntu:latest
RUN echo Updating existing packages, installing and upgrading python and pip.
RUN apt-get update -y
RUN apt-get install -y apache2
COPY ./index.html /var/www/html/
# Copy files
COPY apache-conf /etc/apache2/apache2.conf

# Expose Apache
EXPOSE 80

# Launch Apache
CMD ["/usr/sbin/apache2ctl", "-DFOREGROUND"]
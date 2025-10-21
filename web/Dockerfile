# Base image HTTP
FROM httpd:alpine

# Copier la page web
COPY index.html /usr/local/apache2/htdocs/
COPY httpd.conf /usr/local/apache2/conf/httpd.conf

# Exposer le port 80
EXPOSE 80

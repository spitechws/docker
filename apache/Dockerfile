FROM httpd:2.4.33-alpine
# Copy apache vhost file to proxy php requests to php-fpm container
COPY pp_new.apache.conf /usr/local/apache2/conf/pp_new.apache.conf
RUN echo "Include /usr/local/apache2/conf/pp_new.apache.conf" \
    >> /usr/local/apache2/conf/httpd.conf
FROM jwilder/nginx-proxy:alpine
LABEL MAINTAINER="BBT Software AG <devadmin@bbtsoftware.ch>"

RUN { \
      echo 'client_max_body_size 0;'; \
    } > /etc/nginx/conf.d/unrestricted_client_body_size.conf
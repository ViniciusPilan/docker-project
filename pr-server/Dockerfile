FROM nginxinc/nginx-unprivileged:1.22

USER root

COPY /conf.d/* /etc/nginx/conf.d

RUN mkdir /usr/share/nginx/html/help /usr/share/nginx/html/index

COPY /html/help/* /usr/share/nginx/html/help 
COPY /html/index/* /usr/share/nginx/html/index

USER nginx
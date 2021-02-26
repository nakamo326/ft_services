FROM alpine

RUN		apk update \
		&& apk add nginx

RUN		mkdir -p /etc/nginx/sites-available
RUN		mkdir -p /run/nginx

COPY	nginx.conf /etc/nginx/sites-available/default

RUN		chmod +r /etc/nginx/sites-available/default

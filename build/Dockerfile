FROM nginx:alpine

WORKDIR /jumpwebgame
COPY jumpwebgame/ .

WORKDIR /etc/nginx/conf.d
RUN rm default.conf
COPY jumpwebgame.conf jumpwebgame.conf

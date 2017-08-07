FROM alpine:3.3
MAINTAINER hedcler.m@gmail.com

RUN apk add --update curl

COPY ./tasks/ /etc/periodic/
RUN chmod -R +x /etc/periodic/

ADD ./root /var/spool/cron/crontabs/

CMD ["crond", "-f", "-d", "8"]
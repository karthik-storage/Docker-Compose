FROM mongo

RUN apt-get update -y

RUN apt-get install systemd -y

RUN apt-get install vim -y

RUN sed -i 's/127.0.0.1/54.174.125.167/g' /etc/mongod.conf.orig

EXPOSE 27017


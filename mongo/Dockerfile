FROM mongo

RUN apt-get update -y

RUN apt-get install systemd -y

RUN apt-get install vim -y

RUN sed -i 's/127.0.0.1/0.0.0.0/g' /etc/mongod.conf.orig

EXPOSE 27017


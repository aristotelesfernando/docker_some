FROM alpine:3.9
MAINTAINER A.Fernando de Oliveira Jr
RUN apk add --no-cache mongodb
VOLUME /data/db
EXPOSE 27017
CMD [ "/usr/bin/mongod", "--bind-ip", "0.0.0.0" ]
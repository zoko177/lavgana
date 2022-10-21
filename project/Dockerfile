
FROM openjdk:8-jre-alpine

WORKDIR /lav


COPY ./target/lavagna-jetty-console.war .
COPY ./entrypoint.sh .

#RUN apk update && apk add ca-certificates && update-ca-certificates && apk add openssl

ENTRYPOINT [ "sh", "./entrypoint.sh" ]

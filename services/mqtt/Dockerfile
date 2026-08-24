FROM eclipse-mosquitto:2.1.2-alpine

RUN apk add --no-cache gettext-envsubst
COPY mosquitto.conf.template /mosquitto/config
COPY ./docker-entrypoint.sh /
RUN chmod 555 /docker-entrypoint.sh

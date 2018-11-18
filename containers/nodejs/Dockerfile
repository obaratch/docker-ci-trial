FROM node:8-alpine

RUN set -x
# RUN echo "test" > /myvol/hey

RUN apk --update add bash bash-completion curl

VOLUME /app
COPY app /app

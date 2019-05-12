FROM python:3.8.0a4-alpine3.9

RUN apk --no-cache update && \
    apk --no-cache add ca-certificates groff less && \
    pip3 --no-cache-dir install && \
    rm -rf /var/cache/apk/*

WORKDIR /data
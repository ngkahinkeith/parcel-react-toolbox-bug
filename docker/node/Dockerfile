FROM node:14-alpine3.13
RUN apk --no-cache update \
    && apk --no-cache add make bash python3 g++ zlib-dev libpng-dev git yarn \
    && rm -fr /var/cache/apk/*

WORKDIR /application


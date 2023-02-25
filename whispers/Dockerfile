FROM alpine:3.17.1
RUN apk update \
    && apk upgrade \
    && apk add python3 py-pip git --no-cache -q \
    && pip3 install whispers

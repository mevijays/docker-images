FROM alpine:3.17.1
RUN apk update && apk upgrade \
    &&  apk add --no-cache nginx bash helm wget curl git docker-cli -q  \
    &&  curl -LO https://dl.k8s.io/release/v1.26.0/bin/linux/amd64/kubectl \
    && chmod +x kubectl \
    && mv kubectl /usr/local/bin/


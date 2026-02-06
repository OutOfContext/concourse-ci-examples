FROM alpine:3.19

RUN apk add --no-cache bash jq

COPY assets/ /opt/resource/
RUN chmod +x /opt/resource/* \
 && sed -i 's/\r$//' /opt/resource/*

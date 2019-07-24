FROM golang:1.11.12
COPY operator-sdk /usr/local/bin/
RUN chmod +x /usr/local/bin/operator-sdk \
& cd /go/src \
& operator-sdk new demo

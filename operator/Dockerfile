FROM golang:1.11.12
COPY operator-sdk /usr/local/bin/
RUN chmod +x /usr/local/bin/operator-sdk
RUN cd $GOPATH/src
RUN go env
RUN operator-sdk new demo

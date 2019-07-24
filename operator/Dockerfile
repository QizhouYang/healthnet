FROM golang:1.11.12
COPY operator-sdk /usr/local/bin/
RUN chmod +x /usr/local/bin/operator-sdk
RUN cd $GOPATH/src
RUN export GO111MODULE=on
RUN pwd
WORKDIR $GOPATH/src
RUN operator-sdk new demo

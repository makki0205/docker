FROM golang:1.14.4-alpine
ENV GO111MODULE on
RUN go get github.com/golang/mock/mockgen@v1.4.3
RUN apk update
RUN apk add --no-cache protobuf
RUN rm -rf $GOPATH
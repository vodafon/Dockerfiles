# Golang for testing with linters and assert
FROM golang:1.7-alpine

MAINTAINER IV version: 0.1

RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh

RUN go get -u github.com/stretchr/testify
RUN go get -u github.com/alecthomas/gometalinter
RUN gometalinter --install

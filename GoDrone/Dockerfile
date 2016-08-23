# Golang for testing with linters and assert
FROM golang:1.7-alpine

MAINTAINER IV version: 0.1

RUN apk update && apk upgrade && \
    apk add --no-cache bash git openssh

RUN go get -u github.com/labstack/echo/...
RUN go get github.com/jinzhu/gorm
RUN go get golang.org/x/crypto/bcrypt
RUN go get github.com/dchest/uniuri
RUN go get github.com/stretchr/testify
RUN go get github.com/stretchr/testify/assert
RUN go get -u github.com/alecthomas/gometalinter
RUN go get -u github.com/pquerna/ffjson
RUN go get gopkg.in/yaml.v2
RUN go get github.com/Sirupsen/logrus
RUN go get github.com/lib/pq
RUN go get github.com/lib/pq/hstore
RUN gometalinter --install

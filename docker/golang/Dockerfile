FROM golang:1.15-alpine

LABEL maintainer="Ryan Durham <ryan@stagerightlabs.com>"

RUN apk update && apk upgrade && apk add --no-cache git openssh

WORKDIR /app

EXPOSE 8080

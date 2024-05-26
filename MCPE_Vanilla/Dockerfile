# syntax=docker/dockerfile:1

FROM ubuntu:latest
WORKDIR /app
COPY . .

RUN chmod 771 run.sh
RUN apt update
RUN apt install libcurl4-openssl-dev -y

EXPOSE 19132

ENTRYPOINT ./bedrock_server


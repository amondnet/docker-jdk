FROM openjdk:8-jdk-alpine

RUN apk add --no-cache tzdata
ENV TZ=Asia/Seoul
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

FROM adoptopenjdk/openjdk11-openj9:alpine-jre

ENV TZ=Asia/Seoul
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

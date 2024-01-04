FROM alpine
WORKDIR /app

ENV TZ=Europe/Moscow

RUN apk add --no-cache tzdata
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
FROM alpine:3.3
RUN apk -U add openjdk7 tzdata
RUN cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
                && echo "Asia/Shanghai" > /etc/timezone\
                && apk del tzdata
RUN rm -rf /tmp/*

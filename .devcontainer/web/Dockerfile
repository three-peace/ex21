FROM php:7.4-apache

#tzdata,xdebugのインストール
RUN apt-get update && \
    apt-get install -y tzdata && \
    pecl install xdebug && \
    rm -rf /var/lib/apt/lists/*

# TimeZone
ENV TZ=Asia/Tokyo

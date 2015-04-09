FROM    ubuntu:14.04

MAINTAINER Stephane Jolicoeur <stephane@brit.co>

RUN     apt-get update && apt-get install -y apt-utils \
            && apt-get install -y \
            libmysqlclient-dev \
            python-setuptools \
            libevent-2.0-5 \
            libevent-dev \
            libjpeg-dev \
            libyaml-dev \
            libtiff5-dev \
            libpng12-dev \
            python2.7 \
            python-dev \
            python-imaging \
            python-gevent \
            curl \
            nginx \
            git \
            redis-server \
            memcached \
            supervisor \
            sqlite3 \
            && curl -sL https://deb.nodesource.com/setup | bash - && apt-get install -y nodejs \
            && apt-get -y autoremove \
            && apt-get clean \
            && mkdir -p /opt/britco/current  \
            && rm -rf /usr/share/doc /usr/share/man

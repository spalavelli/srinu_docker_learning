FROM komljen/nodejs
MAINTAINER Srinivas <srinivasr6551@gmail.com>

RUN \
  npm install hipache -g

COPY config.json config.json
COPY start.sh start.sh

RUN rm /usr/sbin/policy-rc.d
CMD ["/start.sh"]

EXPOSE 80

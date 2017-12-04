
#redis-socketio Dockerfile

FROM redis:alpine
MAINTAINER ierturk

ADD conf /usr/local/etc/redis/
CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]
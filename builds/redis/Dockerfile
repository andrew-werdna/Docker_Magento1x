FROM redis:latest
RUN apt-get update -y
ADD ./redis.conf /usr/local/etc/redis.conf
CMD [ "redis-server", "/usr/local/etc/redis.conf" ]
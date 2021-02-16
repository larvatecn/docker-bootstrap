FROM ubuntu:14.04

LABEL maintainer="support@larva.com.cn"

ENV TERM="linux" \
	LANG="C.UTF-8" \
	LC_ALL="C.UTF-8"

RUN set -x \
	&& apt-get update \
	&& apt-get install -y --no-install-recommends make unzip curl ca-certificates apt-transport-https \
	&& rm -r /var/lib/apt/lists/* \
	&& ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime

FROM centos:8.3.2011

LABEL maintainer="support@larva.com.cn"

ENV TERM="linux" \
	LANG="en_US.UTF-8" \
	LC_ALL="en_US.UTF-8"

RUN set -x \
	&& yum update -y \
	&& rm -rf /var/cache/yum/* \
	&& ln -sf /usr/share/zoneinfo/Asia/Shanghai  /etc/localtime

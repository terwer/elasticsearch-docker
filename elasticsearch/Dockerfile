# 依赖的镜像
FROM elasticsearch:7.17.5

# 镜像创建者的信息
MAINTAINER terwer "youweics@163.com"

# 设置编码
ENV LANG C.UTF-8

# 设置时区
ENV TZ Asia/Shanghai

RUN elasticsearch -version

# ENV VERSION=7.17.5
# https://github.com/medcl/elasticsearch-analysis-ik/releases
# ADD https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v${VERSION}/elasticsearch-analysis-ik-$VERSION.zip /tmp/
# RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install -b file:///tmp/elasticsearch-analysis-ik-$VERSION.zip
#
# RUN rm -rf /tmp/*
# https://github.com/pipizhang/docker-elasticsearch-analysis-ik

# 安装 ik
# docker exec -it es-container bash
# elasticsearch-plugin install https://ghproxy.com/https://github.com/medcl/elasticsearch-analysis-ik/releases/download/v7.17.5/elasticsearch-analysis-ik-7.17.5.zip

# 安装 ansj
# elasticsearch-plugin install https://ghproxy.com/https://github.com/NLPchina/elasticsearch-analysis-ansj/releases/download/v7.17.5/elasticsearch-analysis-ansj-7.17.5.0-release.zip


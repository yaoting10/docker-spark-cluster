FROM registry.cn-hangzhou.aliyuncs.com/matt/spark-hadoop:1.0.0

MAINTAINER Tim <412857135@qq.com>

COPY master.sh /

ENV SPARK_MASTER_PORT 7077
ENV SPARK_MASTER_WEBUI_PORT 8080
ENV SPARK_MASTER_LOG /spark/logs

EXPOSE 8080 7077 6066

CMD ["/bin/bash","/master.sh"]


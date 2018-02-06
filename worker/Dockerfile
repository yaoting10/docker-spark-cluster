FROM registry.cn-hangzhou.aliyuncs.com/matt/spark-hadoop:1.0.0

MAINTAINER Tim <412857135@qq.com>

COPY worker.sh /

ENV SPARK_WORKER_WEBUI_PORT 8081
ENV SPARK_WORKER_LOG /spark/logs
ENV SPARK_MASTER "spark://spark-master:32769"

EXPOSE 8081

CMD ["/bin/bash","/worker.sh"]


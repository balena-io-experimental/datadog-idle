FROM datadog/agent:latest

RUN    mkdir /host \
   && ln -s /proc /host/proc \
   && ln -s /sys /host/sys

COPY docker.yaml /conf.d/

CMD /init

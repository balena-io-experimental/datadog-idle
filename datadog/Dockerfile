FROM datadog/agent:6.6.0

RUN    mkdir /host \
   && ln -s /proc /host/proc \
   && ln -s /sys /host/sys

COPY docker.yaml /conf.d/

CMD /init

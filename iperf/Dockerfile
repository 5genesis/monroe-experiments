FROM monroe/base

MAINTAINER Jonas.Karlsson@kau.se

RUN pip install "flatten_json==0.1.7"

COPY files/* /opt/monroe/

ENTRYPOINT ["dumb-init", "--", "/usr/bin/python", "/opt/monroe/experiment.py"]

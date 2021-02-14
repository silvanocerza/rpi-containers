FROM python:3-buster

RUN pip install beancount fava fava-investor

ARG port=5000

ENV FAVA_HOST=0.0.0.0
ENV FAVA_PORT=$port

EXPOSE $port

ENTRYPOINT [ "fava" ]

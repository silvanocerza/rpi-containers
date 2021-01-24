FROM python:3-buster

ARG port

RUN pip install beancount fava fava-investor

ENV FAVA_HOST=localhost
ENV FAVA_PORT=$port

EXPOSE $port

ENTRYPOINT [ "fava" ]

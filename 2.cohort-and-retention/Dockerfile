FROM python:3-slim
MAINTAINER x0rzkov <x0rzkov@protonmail.com>

RUN apt-get install -y nano bash jq ca-certificates git

WORKDIR /opt/service

COPY . .

CMD ["/bin/bqsh"]

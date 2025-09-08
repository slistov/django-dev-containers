FROM python:3.11

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
ENV LC_ALL=C.UTF-8

# Yes we are using the root user now, it's not encouraged but this is only for demo purposes
RUN mkdir -p /root/.vscode-server/extensions /root/.vscode-server-insiders/extensions


WORKDIR /app

COPY requirements.txt /app/

RUN pip install -r requirements.txt

FROM python:3.11-alpine3.18
WORKDIR /usr/src/app

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUUNBUFFERED 1

COPY . .

RUN pip install --upgrade pip
RUN pip install -r requirements.txt


ENTRYPOINT ["/usr/src/app/entrypoint.sh"]


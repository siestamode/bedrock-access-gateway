FROM python:3.12-slim

COPY ./api ./api

COPY requirements.txt .

RUN pip3 install -r requirements.txt -U --no-cache-dir

EXPOSE 8000

CMD [ "api.app.handler" ]

FROM python:3.7.7-buster

WORKDIR /workdir

COPY ./ ./

RUN pip3 install -r requirements.txt

EXPOSE 9080

CMD ["sh", "-c", "gunicorn --workers=2 productpage:app"]

FROM python:3.10

WORKDIR /workdir

COPY ./ ./

RUN pip3 install -r requirements.txt

EXPOSE 9080

CMD ["sh", "-c", "gunicorn --workers=2"]

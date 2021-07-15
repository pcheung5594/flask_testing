FROM python:3.9-alpine

RUN mkdir /app

WORKDIR /app

COPY *.py .

RUN pip install flask

EXPOSE 5000

CMD [ "python", "hello.py"]
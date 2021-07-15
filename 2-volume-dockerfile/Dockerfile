FROM python:3.9-alpine

RUN mkdir /app

WORKDIR /app

COPY . .

RUN echo "hello world" >> /app/test.txt

CMD ["python", "read.py"]

# RUN cat /app/test.txt

# CMD ["tail", "-f","/dev/null"]

FROM ruby:3.4.4

RUN mkdir /app
WORKDIR /app

ADD Procfile Procfile
ADD entrypoint entrypoint
ADD app.json app.json

ENTRYPOINT ["./entrypoint"]

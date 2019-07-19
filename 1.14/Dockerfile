FROM ruby:2.6.0

WORKDIR /usr/app
COPY . .

RUN apt-get update && apt-get install nodejs -y && gem install bundler && bundle install &&  rails db:migrate

CMD rails s

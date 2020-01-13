FROM ruby:2.6.0

WORKDIR /app
COPY . .
RUN apt update
RUN apt install -y nodejs
RUN gem install bundler
RUN bundle install
RUN rails db:migrate
CMD rails s

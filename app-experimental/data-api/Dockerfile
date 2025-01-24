FROM ruby:3.3.7-bookworm

WORKDIR /usr/src/app
COPY src/ ./

RUN gem install bundler
RUN bundle install

EXPOSE 4567

CMD [ "ruby", "server.rb" ]
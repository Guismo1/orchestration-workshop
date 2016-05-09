<<<<<<< HEAD
FROM ruby
ENV HTTP_PROXY http://proxy-wsa.esl.cisco.com:80/
ENV HTTPS_PROXY http://proxy-wsa.esl.cisco.com:80/
=======
FROM ruby:alpine
RUN apk add --update build-base
>>>>>>> f2ccd65b341ed0995160c17611c77765c38472a5
RUN gem install sinatra
RUN gem install thin
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 80

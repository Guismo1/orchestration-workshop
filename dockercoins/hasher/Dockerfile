FROM ruby
ENV HTTP_PROXY http://proxy-wsa.esl.cisco.com:80/
ENV HTTPS_PROXY http://proxy-wsa.esl.cisco.com:80/
RUN gem install sinatra
RUN gem install thin
ADD hasher.rb /
CMD ["ruby", "hasher.rb"]
EXPOSE 80

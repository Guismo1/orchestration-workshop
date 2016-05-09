FROM node:4
ENV HTTP_PROXY http://proxy-wsa.esl.cisco.com:80/
ENV HTTPS_PROXY http://proxy-wsa.esl.cisco.com:80/
RUN npm install express
RUN npm install redis
COPY files/ /files/
COPY webui.js /
CMD ["node", "webui.js"]
EXPOSE 80

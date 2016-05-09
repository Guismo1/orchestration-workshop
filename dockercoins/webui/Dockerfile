<<<<<<< HEAD
FROM node:4
ENV HTTP_PROXY http://proxy-wsa.esl.cisco.com:80/
ENV HTTPS_PROXY http://proxy-wsa.esl.cisco.com:80/
=======
FROM node:4-slim
>>>>>>> f2ccd65b341ed0995160c17611c77765c38472a5
RUN npm install express
RUN npm install redis
COPY files/ /files/
COPY webui.js /
CMD ["node", "webui.js"]
EXPOSE 80

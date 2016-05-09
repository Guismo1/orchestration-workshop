<<<<<<< HEAD
FROM python
RUN export HTTPS_PROXY=http://proxy-wsa.esl.cisco.com:80/ ; pip install redis
RUN export HTTPS_PROXY=http://proxy-wsa.esl.cisco.com:80/ ; pip install requests
=======
FROM python:alpine
RUN pip install redis
RUN pip install requests
>>>>>>> f2ccd65b341ed0995160c17611c77765c38472a5
COPY worker.py /
CMD ["python", "worker.py"]

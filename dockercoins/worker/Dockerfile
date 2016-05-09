FROM python
RUN export HTTPS_PROXY=http://proxy-wsa.esl.cisco.com:80/ ; pip install redis
RUN export HTTPS_PROXY=http://proxy-wsa.esl.cisco.com:80/ ; pip install requests
COPY worker.py /
CMD ["python", "worker.py"]

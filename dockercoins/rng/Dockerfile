<<<<<<< HEAD
FROM python
ENV HTTP_PROXY http://proxy-wsa.esl.cisco.com:80/
ENV HTTPS_PROXY http://proxy-wsa.esl.cisco.com:80/
=======
FROM python:alpine
>>>>>>> f2ccd65b341ed0995160c17611c77765c38472a5
RUN pip install Flask
COPY rng.py /
CMD ["python", "rng.py"]
EXPOSE 80

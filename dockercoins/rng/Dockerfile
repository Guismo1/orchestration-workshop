FROM python
ENV HTTP_PROXY http://proxy-wsa.esl.cisco.com:80/
ENV HTTPS_PROXY http://proxy-wsa.esl.cisco.com:80/
RUN pip install Flask
COPY rng.py /
CMD ["python", "rng.py"]
EXPOSE 80

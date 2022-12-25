FROM python:latest

ADD server.py /server/
ADD index.html /server/

WORKDIR /server/

#RUN python ./server.py

CMD ["python", "./server.py"]

EXPOSE 1234
